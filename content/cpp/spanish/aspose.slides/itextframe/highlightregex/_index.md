---
title: HighlightRegex()
second_title: Referencia de API de Aspose.Slides para C++
description: Resalta todas las coincidencias de la expresión regular con el color especificado.
type: docs
weight: 131
url: /es/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

Resalta todas las coincidencias de la expresión regular con el color especificado.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | La expresión regular [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) para obtener las cadenas a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color para resaltar el texto. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | El objeto de devolución de llamada para recibir los resultados de búsqueda [IFindResultCallback](../../ifindresultcallback/). |
## Observaciones

El siguiente ejemplo de código muestra cómo resaltar texto en un [TextFrame](../../textframe/) usando una expresión regular. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

Resalta todas las coincidencias de la expresión regular con el color especificado.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Texto de la expresión regular para obtener el texto a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color para resaltar el texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opciones de resaltado. |

Obsoleto
:   Utilice el método HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) en su lugar. El método será eliminado después del lanzamiento de la versión 24.10.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Regex](../../../system.text.regularexpressions/regex/)
* Clase [Color](../../../system.drawing/color/)
* Clase [IFindResultCallback](../../ifindresultcallback/)
* Clase [ITextFrame](../)
* Clase [String](../../../system/string/)
* Clase [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)