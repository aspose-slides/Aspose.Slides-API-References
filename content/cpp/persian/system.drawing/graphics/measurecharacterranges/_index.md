---
title: MeasureCharacterRanges()
second_title: Aspose.Slides برای مرجع API C++
description: آرایه‌ای از نواحی را برمی‌گرداند که هر کدام موقعیت‌های کاراکتر را در رشتهٔ مشخص شده محدود می‌کنند.
type: docs
weight: 508
url: /fa/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) متد

یک آرایه از نواحی که هر کدام موقعیت‌های کاراکتر را در رشتهٔ مشخص شده محدود می‌کند، برمی‌گرداند.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | رشته‌ای که باید اندازه‌گیری شود |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | قلم (فونت) مورد استفاده در هنگام اندازه‌گیری رشته |
| layoutRect | [RectangleF](../../rectanglef/) | مستطیل چیدمان مورد استفاده در هنگام اندازه‌گیری رشته |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | قالب رشته که حوزه‌های کاراکتری که باید اندازه‌گیری شوند را شامل می‌شود |

## مراجع

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Region](../../region/)
* کلاس [String](../../../system/string/)
* کلاس [Font](../../font/)
* کلاس [RectangleF](../../rectanglef/)
* کلاس [StringFormat](../../stringformat/)
* کلاس [Graphics](../)
* فضای‌نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)