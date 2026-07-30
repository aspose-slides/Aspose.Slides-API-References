---
title: ExportToHtml()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Převede určené odstavce do HTML a vrátí je jako objekt typu String.
type: docs
weight: 105
url: /cs/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) metoda


Převede určené odstavce do HTML a vrátí jej jako objekt typu String.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Index prvního odstavce **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) počet **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Možnosti převodu [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Návratová hodnota

Generated HTML.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Třída [IParagraphCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)