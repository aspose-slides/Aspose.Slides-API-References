---
title: HighlightRegex()
second_title: Referencia de la API de Aspose.Slides para C++
description: Resalta todas las coincidencias de la expresión regular con el color especificado.
type: docs
weight: 469
url: /es/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) método


Resalta todas las coincidencias de la expresión regular con el color especificado.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | La expresión regular [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) para obtener las cadenas a resaltar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | El color para resaltar el texto. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | El objeto de devolución de llamada para recibir los resultados de búsqueda [IFindResultCallback](../../ifindresultcallback/). |
## Observaciones



El siguiente ejemplo de código muestra cómo resaltar texto en un PowerPoint [Presentation](../../presentation/) usando una expresión regular. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// resaltando todas las palabras con 10 o más caracteres
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Regex](../../../system.text.regularexpressions/regex/)
* Clase [Color](../../../system.drawing/color/)
* Clase [IFindResultCallback](../../ifindresultcallback/)
* Clase [IPresentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)