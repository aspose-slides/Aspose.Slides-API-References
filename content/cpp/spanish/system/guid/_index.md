---
title: Guid
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un Identificador Único Global. Este tipo debe asignarse en la pila y pasarse a las funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 885
url: /es/system/guid/
---
## Clase Guid

Representa un Identificador Único Global. Este tipo debe asignarse en la pila y pasarse a las funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Guid
```

## Métodos

| Método | Descripción |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Realiza una comparación aritmética de los GUID representados por el objeto actual y el especificado. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Determina si los GUID representados por el objeto actual y el especificado son iguales. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [Guid](./guid/)() | Construye un objeto que representa un GUID formado solo por ceros. |
| [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Construye un objeto que representa un GUID especificado como una matriz de valores enteros sin signo de 8 bits. |
| [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Construye un objeto que representa un GUID especificado como una vista de matriz de valores enteros sin signo de 8 bits. |
| [Guid](./guid/)(const [String](../string/)\&) | Construye un objeto que representa un GUID especificado como una cadena. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Construye una instancia de la clase [Guid](./) a partir de los componentes GUID especificados. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Construye una instancia de la clase [Guid](./) a partir de los componentes GUID especificados. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Construye una instancia de la clase [Guid](./) a partir de los enteros sin signo y bytes especificados. |
| [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Construye una instancia de la clase [Guid](./) a partir de los enteros sin signo y bytes especificados. |
| [Guid](./guid/)(const [Guid](./)\&) | Construye un objeto que representa el mismo GUID que el objeto especificado. |
| static [Guid](./) [NewGuid](./newguid/)() | Genera un nuevo GUID y devuelve un objeto [Guid](./) que lo representa. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Determina si los GUID representados por el objeto actual y el especificado no son iguales. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Asigna al objeto actual el valor GUID representado por el objeto [Guid](./) especificado. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Determina si los GUID representados por el objeto actual y el especificado son iguales. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Convierte la representación en cadena especificada de un GUID en un objeto [Guid](./) equivalente. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Convierte el GUID representado por el objeto actual en una matriz de bytes. |
| [String](../string/) [ToString](./tostring/)() const | Convierte el GUID representado por el objeto actual a su representación en cadena. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Convierte el GUID representado por el objeto actual a su representación en cadena usando el formato de cadena especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Convierte el GUID representado por el objeto actual a su representación en cadena usando el formato de cadena y la Cultura especificados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Intenta convertir la cadena especificada en un objeto [Guid](./). |
| [~Guid](./~guid/)() | Destructor. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Representa un GUID cuyo valor es 0. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)