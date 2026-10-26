---
title: ExportToHtml()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل الفقرات المحددة إلى HTML ويعيدها ككائن String.
type: docs
weight: 105
url: /ar/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) طريقة

يقوم بتحويل الفقرات المحددة إلى HTML ويعيده ككائن String.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | First paragraph index **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) عدد **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | خيارات التحويل [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Return Value

HTML المولد.

## See Also

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* فئة [IParagraphCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)