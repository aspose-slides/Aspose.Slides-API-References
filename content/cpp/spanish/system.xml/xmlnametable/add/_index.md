---
title: Add()
second_title: Aspose.Slides para C++ Referencia de API
description: Cuando se sobrescribe en una clase derivada, atomiza la cadena especificada y la agrega a XmlNameTable.
type: docs
weight: 14
url: /es/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) método

Cuando se sobrescribe en una clase derivada, atomiza la cadena especificada y la agrega a [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | La matriz de caracteres que contiene el nombre a agregar. |
| offset | **int32_t** | Índice basado en cero en la matriz que indica el primer carácter del nombre. |
| length | **int32_t** | El número de caracteres del nombre. |

### Valor de retorno

La nueva cadena atomizada o la existente si ya existe. Si la longitud es cero, se devuelve [String::Empty](../../../system/string/empty/).

## XmlNameTable::Add(const String\&) método

Cuando se sobrescribe en una clase derivada, atomiza la cadena especificada y la agrega a [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | El nombre a agregar. |

### Valor de retorno

La nueva cadena atomizada o la existente si ya existe.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)