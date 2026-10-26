---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides برای API مرجع C++
description: تمام فریم‌های متنی موجود در اسلاید مشخص‌شده که شامل متن داده‌شده هستند را برمی‌گرداند.
type: docs
weight: 66
url: /fa/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) متد

تمام فریم‌های متنی موجود در اسلاید مشخص شده که شامل متن داده شده هستند را برمی‌گرداند.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | اسلایدی که باید جستجو شود. |
| text | [System::String](../../../system/string/) | متنی که باید در فریم‌های متنی جستجو شود. |
| checkPlaceholderText | **bool** | مشخص می‌کند آیا فریم‌های متنی خالی که متن نگهدارنده آن‌ها شامل متن جستجو است نیز شامل شوند یا خیر. |

### مقدار بازگشت

آرایه‌ای از اشیاء [ITextFrame](../../../aspose.slides/itextframe/) که متن مشخص شده را شامل می‌شوند.

## همچنین ببینید

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ITextFrame](../../../aspose.slides/itextframe/)
* کلاس [IBaseSlide](../../../aspose.slides/ibaseslide/)
* کلاس [String](../../../system/string/)
* کلاس [SlideUtil](../)
* فضای نام [Aspose::Slides::Util](../../)
* کتابخانه [Aspose.Slides](../../../)