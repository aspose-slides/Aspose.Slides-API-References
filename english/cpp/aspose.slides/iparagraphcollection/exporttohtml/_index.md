---
title: ExportToHtml()
second_title: Aspose.Slides for C++ API Reference
description: Converts specifying paragraphs to the HTML and returns it as String object.
type: docs
weight: 105
url: /cpp/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(**int32_t**, **int32_t**, [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\>) method


Converts specifying paragraphs to the HTML and returns it as String object.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | First paragraph index **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) count **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Convert options [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Return Value

Generated HTML.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Class [IParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
