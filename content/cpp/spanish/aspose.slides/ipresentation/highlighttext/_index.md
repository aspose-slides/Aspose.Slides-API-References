---
title: HighlightText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Resalta todas las coincidencias del texto de muestra con el color especificado.
type: docs
weight: 456
url: /es/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) método


Resalta todas las coincidencias del texto de muestra con el color especificado.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | El texto a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color para resaltar el texto. |
## Observaciones



El siguiente ejemplo de código muestra cómo resaltar texto en una presentación de PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// highlighting all separate 'the' occurrences
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) método


Resalta todas las coincidencias del texto de muestra con el color especificado.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | El texto a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color para resaltar el texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opciones de búsqueda de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | El objeto de devolución de llamada para recibir los resultados de la búsqueda [IFindResultCallback](../../ifindresultcallback/). |
## Observaciones



El siguiente ejemplo de código muestra cómo resaltar texto en una presentación de PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// resaltando todas las ocurrencias separadas de 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [Color](../../../system.drawing/color/)
* Clase [IPresentation](../)
* Clase [ITextSearchOptions](../../itextsearchoptions/)
* Clase [IFindResultCallback](../../ifindresultcallback/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)