---
title: HighlightRegex()
second_title: Referencia de la API de Aspose.Slides para C++
description: Resalta todas las coincidencias de la expresión regular con el color especificado.
type: docs
weight: 157
url: /es/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) método

Resalta todas las coincidencias de la expresión regular con el color especificado.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Texto de la expresión regular para obtener el texto a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color para resaltar el texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opciones de resaltado. |

## Observaciones

Obsoleto
:   Utilice HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) method en su lugar. El método será eliminado después del lanzamiento de la versión 24.10.

El siguiente ejemplo de código muestra cómo resaltar texto en un [TextFrame](../) usando una expresión regular. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// resaltando todas las palabras con 10 o más caracteres
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) método

Resalta todas las coincidencias de la expresión regular con el color especificado.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | La expresión regular [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) para obtener las cadenas a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color para resaltar el texto. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | El objeto de devolución de llamada para recibir los resultados de búsqueda [IFindResultCallback](../../ifindresultcallback/). |

## Observaciones

El siguiente ejemplo de código muestra cómo resaltar texto en un [TextFrame](../) usando una expresión regular. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// resaltando todas las palabras con 10 o más caracteres
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [Color](../../../system.drawing/color/)
* Clase [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Clase [TextFrame](../)
* Clase [Regex](../../../system.text.regularexpressions/regex/)
* Clase [IFindResultCallback](../../ifindresultcallback/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)