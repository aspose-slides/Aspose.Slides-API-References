---
title: AddText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega texto sin formato a los archivos html, reemplazando los caracteres especiales con entidades html. No se reemplazan los saltos de línea ni los espacios en blanco.
type: docs
weight: 92
url: /es/aspose.slides.export/htmlgenerator/addtext/
---
## HtmlGenerator::AddText(System::String) método

Agrega texto simple a los archivos html, reemplazando caracteres especiales con entidades html. Los saltos de línea y los espacios en blanco no se reemplazan.

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::String text) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto a agregar. |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) método

Agrega texto simple a los archivos html, reemplazando caracteres especiales con entidades html. Los saltos de línea y los espacios en blanco no se reemplazan.

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Texto a agregar. |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) método

Agrega texto simple a los archivos html, reemplazando caracteres especiales con entidades html. Los saltos de línea y los espacios en blanco no se reemplazan.

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Texto a agregar. |
| startIndex | **int32_t** | Índice inicial de la porción a agregar. |
| length | **int32_t** | Longitud de la porción a agregar. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [HtmlGenerator](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)