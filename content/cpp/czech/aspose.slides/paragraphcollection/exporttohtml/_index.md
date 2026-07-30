---
title: ExportToHtml()
second_title: Aspose.Slides pro C++ referenční API
description: Převádí zadané odstavce do HTML a vrací jej jako objekt String.
type: docs
weight: 170
url: /cs/aspose.slides/paragraphcollection/exporttohtml/
---
## ParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) metoda

Převádí určené odstavce do HTML a vrací jej jako objekt String.

```cpp
System::String Aspose::Slides::ParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Index prvního odstavce **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) počet **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Možnosti převodu [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Návratová hodnota

Vygenerované HTML.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Třída [ParagraphCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)