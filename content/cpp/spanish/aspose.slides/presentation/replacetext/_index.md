---
title: ReplaceText()
second_title: Referencia de API de Aspose.Slides para C++
description: Reemplaza todas las apariciones del texto especificado con otro texto especificado.
type: docs
weight: 521
url: /es/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) método

Reemplaza todas las apariciones del texto especificado con otro texto especificado.

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | La cadena a reemplazar. |
| newText | [System::String](../../../system/string/) | La cadena que reemplaza todas las apariciones de oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opciones de búsqueda de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | El objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../ifindresultcallback/). |
## Observaciones

El siguiente código de ejemplo muestra cómo reemplazar una cadena especificada por otra cadena especificada. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Reemplaza todas las apariciones separadas de 'the' con '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)