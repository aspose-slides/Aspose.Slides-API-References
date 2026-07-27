---
title: Version
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un número de versión. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 1470
url: /es/system/version/
---
## Version clase


Representa un número de versión. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca utilice la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Version
```

## Métodos

| Método | Descripción |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Compara las versiones representadas por el objeto actual y el objeto especificado. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Determina si los números de versión representados por los objetos actual y especificado son iguales. |
| int [get_Build](./get_build/)() const | Devuelve el número de compilación. |
| int [get_Major](./get_major/)() const | Devuelve la versión mayor. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Devuelve el valor de 16 bits superiores del número de revisión. |
| int [get_Minor](./get_minor/)() const | Devuelve la versión menor. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Devuelve el valor de 16 bits inferiores del número de revisión. |
| int [get_Revision](./get_revision/)() const | Devuelve el número de revisión. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Convierte la representación en cadena de un número de versión en una instancia equivalente de la clase [Version](./). |
| [String](../string/) [ToString](./tostring/)() const | Devuelve la representación en cadena del número de versión representado por el objeto actual. |
| [String](../string/) [ToString](./tostring/)(int) const | Devuelve la representación en cadena del número especificado de secciones del número de versión representado por el objeto actual. |
|  [Version](./version/)(int, int, int, int) | Construye una instancia que representa los valores especificados de mayor, menor, compilación y revisión. |
|  [Version](./version/)(int, int, int) | Construye una instancia que representa los valores especificados de mayor, menor y compilación. |
|  [Version](./version/)(int, int) | Construye una instancia que representa los valores especificados de mayor y valores. |
|  [Version](./version/)(const [String](../string/)\&) | Construye una instancia que representa el número de versión representado como una cadena. |
|  [Version](./version/)() | Construye una instancia que representa el número de versión 0.0.-1.-1. |
## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)