---
title: HighlightText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Resalta todas las coincidencias del texto de muestra con el color especificado.
type: docs
weight: 105
url: /es/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) método


Resalta todas las coincidencias del texto de muestra con el color especificado.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | El texto a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color con el que se resaltará el texto. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) método


Resalta todas las coincidencias del texto de muestra con el color especificado.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | El texto a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color con el que se resaltará el texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opciones de resaltado. |

Obsoleto
:   Use HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) método instead. El método será eliminado después del lanzamiento de la versión 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) método


Resalta todas las coincidencias del texto de muestra con el color especificado.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | El texto a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color con el que se resaltará el texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opciones de búsqueda de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | El objeto de devolución de llamada para recibir los resultados de la búsqueda [IFindResultCallback](../../ifindresultcallback/). |
## Observaciones



El siguiente ejemplo de código muestra cómo resaltar texto en un [TextFrame](../../textframe/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [Color](../../../system.drawing/color/)
* Clase [ITextFrame](../)
* Clase [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Clase [ITextSearchOptions](../../itextsearchoptions/)
* Clase [IFindResultCallback](../../ifindresultcallback/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)