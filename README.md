import 'package:flutter/material.dart';
void main() => runApp(MyApp());
class MyApp extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return MaterialApp(
 home: RowDemo(),
 );
 }
}
class RowDemo extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return Scaffold(
 appBar: AppBar(title: Text('Row Widget')),
 body: Center(
 child: Row(
 mainAxisAlignment: MainAxisAlignment.spaceEvenly,
 children: [
 Icon(Icons.home, size: 40, color: Colors.blue),
 Icon(Icons.favorite, size: 40, color: Colors.red),
 Icon(Icons.person, size: 40, color: Colors.green),
 ],
 ),
 ),
 );
 }
}
