---
title: ExportToHtml()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar specificerade stycken till HTML och returnerar det som String-objekt.
type: docs
weight: 105
url: /sv/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) metod


Konverterar specificerade stycken till HTML och returnerar det som String-objekt.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Första styckets index **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) antal **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Konverteringsalternativ [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Return Value

Genererad HTML.

## See Also

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Klass [IParagraphCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)