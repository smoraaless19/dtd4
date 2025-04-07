<!-- 
Nombre: Sergio Morales 
Curso: ASIR1 
Fecha: 06/04/2025 
Ejercicio: DTD4 
-->

<!-- Documento XML con DTD interna validado correctamente -->

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE biblioteca [
  <!ELEMENT biblioteca (libro+)>
  <!ELEMENT libro (titulo, autor, anio)>
  <!ELEMENT titulo (#PCDATA)>
  <!ELEMENT autor (#PCDATA)>
  <!ELEMENT anio (#PCDATA)>
]>

<!--  Lista de libros en la biblioteca -->
<biblioteca>
  <!--  Libro 1 -->
  <libro>
    <titulo>1984</titulo>
    <autor>George Orwell</autor>
    <anio>1949</anio>
  </libro>

  <!--  Libro 2 -->
  <libro>
    <titulo>Cien Años de Soledad</titulo>
    <autor>Gabriel García Márquez</autor>
    <anio>1967</anio>
  </libro>
</biblioteca>
