---
title: ReplaceRegex()
second_title: Referencia de la API de Aspose.Slides para C++
description: Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.
type: docs
weight: 534
url: /es/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) método

Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | La expresión regular [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) para obtener las cadenas a reemplazar. |
| newText | [System::String](../../../system/string/) | La cadena para reemplazar todas las ocurrencias de las cadenas a reemplazar. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | El objeto de devolución de llamada para recibir los resultados de búsqueda [IFindResultCallback](../../ifindresultcallback/). |

## Observaciones

El siguiente ejemplo de código muestra cómo reemplazar texto usando una expresión regular con la cadena especificada. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Regex](../../../system.text.regularexpressions/regex/)
* Clase [String](../../../system/string/)
* Clase [IFindResultCallback](../../ifindresultcallback/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)