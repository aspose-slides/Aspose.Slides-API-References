---
title: ReplaceRegex()
second_title: Referencia de API de Aspose.Slides para C++
description: Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.
type: docs
weight: 183
url: /es/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) método

Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | La expresión regular [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) para obtener las cadenas que se reemplazarán. |
| newText | [System::String](../../../system/string/) | La cadena para reemplazar todas las apariciones de las cadenas que se reemplazarán. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objeto de devolución de llamada para guardar el resultado de la operación de reemplazo [IFindResultCallback](../../ifindresultcallback/). |
## Observaciones

El siguiente código de ejemplo muestra cómo reemplazar texto usando una expresión regular con una cadena especificada.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)