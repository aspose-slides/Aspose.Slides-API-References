---
title: Get()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, obtiene la cadena atomizada que contiene los mismos caracteres que el rango especificado de caracteres en la matriz dada.
type: docs
weight: 1
url: /es/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) método

Cuando se sobrescribe en una clase derivada, obtiene la cadena atomizada que contiene los mismos caracteres que el rango especificado de caracteres en la matriz dada.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | La matriz de caracteres que contiene el nombre a buscar. |
| offset | **int32_t** | El índice basado en cero en la matriz que especifica el primer carácter del nombre. |
| length | **int32_t** | El número de caracteres del nombre. |

### Valor de retorno

La cadena atomizada o **nullptr** si la cadena no ha sido atomizada previamente. Si **length** es cero, se devuelve [String::Empty](../../../system/string/empty/).

## XmlNameTable::Get(const String\&) método

Cuando se sobrescribe en una clase derivada, obtiene la cadena atomizada que contiene el mismo valor que la cadena especificada.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | El nombre a buscar. |

### Valor de retorno

La cadena atomizada o **nullptr** si la cadena no ha sido atomizada previamente.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [XmlNameTable](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)