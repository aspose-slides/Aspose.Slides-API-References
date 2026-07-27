---
title: ReplaceText()
second_title: Referencia de API de Aspose.Slides para C++
description: Reemplaza todas las apariciones del texto especificado con otro texto especificado.
type: docs
weight: 482
url: /es/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) método


Reemplaza todas las apariciones del texto especificado con otro texto especificado.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | La cadena a ser reemplazada. |
| newText | [System::String](../../../system/string/) | La cadena que reemplaza todas las apariciones de oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opciones de búsqueda de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | El objeto de devolución de llamada para recibir los resultados de búsqueda [IFindResultCallback](../../ifindresultcallback/). |
## Observaciones



El siguiente código de ejemplo muestra cómo reemplazar una cadena especificada por otra cadena especificada. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Reemplaza todas las ocurrencias separadas de 'the' con '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [ITextSearchOptions](../../itextsearchoptions/)
* Clase [IFindResultCallback](../../ifindresultcallback/)
* Clase [IPresentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)