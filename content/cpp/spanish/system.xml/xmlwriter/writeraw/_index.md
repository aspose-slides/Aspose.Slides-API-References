---
title: WriteRaw()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, escribe marcado sin procesar manualmente desde un búfer de caracteres.
type: docs
weight: 287
url: /es/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) método

Cuando se sobrescribe en una clase derivada, escribe marcado sin procesar manualmente desde un búfer de caracteres.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Matriz de caracteres que contiene el texto a escribir. |
| index | **int32_t** | La posición dentro del búfer que indica el inicio del texto a escribir. |
| count | **int32_t** | El número de caracteres a escribir. |

## XmlWriter::WriteRaw(const String\&) método

Cuando se sobrescribe en una clase derivada, escribe marcado sin procesar manualmente desde una cadena.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) que contiene el texto a escribir. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [XmlWriter](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)