---
title: FindShape()
second_title: Aspose.Slides برای C++ مرجع API
description: شکل را بر اساس متن جایگزین در یک ارائه PPTX پیدا می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) متد

شکل را بر اساس متن جایگزین در یک ارائه PPTX پیدا می‌کند.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | ارائه اسکن‌شده. |
| altText | [System::String](../../../system/string/) | متن جایگزین یک شکل. |

### مقدار بازگشت

[Shape](../../../aspose.slides/shape/) یا null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) متد

شکل را بر اساس متن جایگزین در یک اسلاید از ارائه PPTX پیدا می‌کند.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | اسلاید اسکن‌شده. |
| altText | [System::String](../../../system/string/) | متن جایگزین یک شکل. |

### مقدار بازگشت

[Shape](../../../aspose.slides/shape/) یا null.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IShape](../../../aspose.slides/ishape/)
* کلاس [IPresentation](../../../aspose.slides/ipresentation/)
* کلاس [String](../../../system/string/)
* کلاس [SlideUtil](../)
* کلاس [IBaseSlide](../../../aspose.slides/ibaseslide/)
* فضای‌نام [Aspose::Slides::Util](../../)
* کتابخانه [Aspose.Slides](../../../)