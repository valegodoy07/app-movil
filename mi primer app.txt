import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Probando Mi App', // Nombre de la aplicación
      theme: ThemeData(
        primarySwatch: Colors.blue, // Color primario de la aplicación
      ),
      home: Scaffold(
        appBar: AppBar(
          title: const Text('Mi Primera App'), // Título de la AppBar
        ),
        body: const Center(
          child: Text(
            '¡Hola, Mundo!', // Texto principal
            style: TextStyle(
              fontSize: 24, // Tamaño de la fuente
            ),
          ),
        ),
      ),
    );
  }
}