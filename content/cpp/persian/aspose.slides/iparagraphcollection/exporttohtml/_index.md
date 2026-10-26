---
title: ExportToHtml()
second_title: مرجع API Aspose.Slides برای C++
description: پاراگراف‌های مشخص‌شده را به HTML تبدیل می‌کند و به‌عنوان شیء String باز می‌گرداند.
type: docs
weight: 105
url: /fa/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) متد

پاراگراف‌های مشخص شده را به HTML تبدیل می‌کند و به عنوان شیء String بازمی‌گرداند.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | اندیس اولین پاراگراف **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) تعداد **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | گزینه‌های تبدیل [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### مقدار بازگشت

HTML تولید شده.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* کلاس [IParagraphCollection](../)
* فضا‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)