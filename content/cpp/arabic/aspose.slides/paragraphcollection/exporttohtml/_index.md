---
title: ExportToHtml()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل الفقرات المحددة إلى HTML ويعيدها ككائن من نوع String.
type: docs
weight: 170
url: /ar/aspose.slides/paragraphcollection/exporttohtml/
---
## ParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) طريقة


يقوم بتحويل الفقرات المحددة إلى HTML ويعيدها ككائن من نوع String.

```cpp
System::String Aspose::Slides::ParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options) override
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | فهرس الفقرة الأولى **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) عدد **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | خيارات التحويل [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### قيمة الإرجاع

HTML المُولَّد.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* فئة [ParagraphCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)