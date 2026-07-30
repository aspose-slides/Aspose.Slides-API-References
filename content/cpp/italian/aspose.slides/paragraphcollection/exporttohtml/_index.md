---
title: ExportToHtml()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte i paragrafi specificati in HTML e lo restituisce come oggetto String.
type: docs
weight: 170
url: /it/aspose.slides/paragraphcollection/exporttohtml/
---
## ParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) method


Converte i paragrafi specificati in HTML e lo restituisce come oggetto String.

```cpp
System::String Aspose::Slides::ParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Indice del primo paragrafo **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) conteggio **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Opzioni di conversione [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Valore di ritorno

HTML generato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Classe [ParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)