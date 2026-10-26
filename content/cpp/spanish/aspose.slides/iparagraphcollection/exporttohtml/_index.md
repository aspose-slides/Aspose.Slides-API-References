---
title: ExportToHtml()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte los párrafos especificados a HTML y lo devuelve como objeto String.
type: docs
weight: 105
url: /es/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) método


Convierte los párrafos especificados a HTML y lo devuelve como objeto String.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Índice del primer párrafo **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) recuento **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Opciones de conversión [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Valor de retorno

HTML generado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Clase [IParagraphCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)