---
title: WriteRaw()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe marcado sin procesar manualmente desde un búfer de caracteres.
type: docs
weight: 417
url: /es/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) método

Escribe marcado sin procesar manualmente desde un búfer de caracteres.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Matriz de caracteres que contiene el texto a escribir. |
| index | **int32_t** | La posición dentro del búfer que indica el inicio del texto a escribir. |
| count | **int32_t** | El número de caracteres a escribir. |

## XmlTextWriter::WriteRaw(const String\&) método

Escribe marcado sin procesar manualmente desde una cadena.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) que contiene el texto a escribir. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [XmlTextWriter](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)