---
title: ReplaceText()
second_title: Referencia de la API de Aspose.Slides para C++
description: Reemplaza todas las apariciones del texto especificado con otro texto especificado.
type: docs
weight: 170
url: /es/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method

Reemplaza todas las apariciones del texto especificado con otro texto especificado.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | La cadena a ser reemplazada. |
| newText | [System::String](../../../system/string/) | La cadena que reemplaza todas las apariciones de oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opciones de búsqueda de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objeto de devolución de llamada para guardar el resultado de la operación de reemplazo [IFindResultCallback](../../ifindresultcallback/). |
## Observaciones



El siguiente código de ejemplo muestra cómo reemplazar una cadena especificada por otra cadena especificada. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Reemplaza todas las ocurrencias separadas de 'the' con '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [ITextSearchOptions](../../itextsearchoptions/)
* Clase [IFindResultCallback](../../ifindresultcallback/)
* Clase [TextFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)