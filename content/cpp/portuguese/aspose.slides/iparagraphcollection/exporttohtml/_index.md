---
title: ExportToHtml()
second_title: Referência da API Aspose.Slides para C++
description: Converte os parágrafos especificados para HTML e o retorna como objeto String.
type: docs
weight: 105
url: /pt/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) método

Converte os parágrafos especificados para HTML e o devolve como um objeto String.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Índice do primeiro parágrafo **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) contagem **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Opções de conversão [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Valor de retorno

HTML gerado.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Classe [IParagraphCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)