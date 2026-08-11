---
title: MeasureString()
second_title: مرجع API Aspose.Slides برای C++
description: اندازهٔ رشتهٔ مشخص‌شده را زمانی که با فونت مشخص در قالب مشخص رسم می‌شود، برمی‌گرداند.
type: docs
weight: 521
url: /fa/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

اندازهٔ رشتهٔ مشخص‌شده را زمانی که با فونت مشخص و در قالب مشخص رسم می‌شود، برمی‌گرداند.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | رشته‌ای که اندازه‌اش باید محاسبه شود |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | فونتی که برای رسم رشته استفاده می‌شود |
| origin | [PointF](../../pointf/) const\& | مکان گوشهٔ بالا-چپ رشته را مشخص می‌کند |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | قالب رشته را مشخص می‌کند |

### مقدار بازگشتی

یک شیء [SizeF](../../sizef/) که اندازهٔ رشته را در واحدهای اندازه‌گیری مشخص‌شده توسط ویژگی PageUnit شیء Graphics فعلی نشان می‌دهد.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

اندازهٔ رشتهٔ مشخص‌شده را زمانی که با فونت مشخص و در قالب مشخص رسم می‌شود، برمی‌گرداند.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | رشته‌ای که اندازه‌اش باید محاسبه شود |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | فونتی که برای رسم رشته استفاده می‌شود |
| width | int | حداکثر عرض رشته |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | قالب رشته را مشخص می‌کند |

### مقدار بازگشتی

یک شیء [SizeF](../../sizef/) که اندازهٔ رشته را در واحدهای اندازه‌گیری مشخص‌شده توسط ویژگی PageUnit شیء Graphics فعلی نشان می‌دهد.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

پیاده‌سازی نشده.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

اندازهٔ رشتهٔ مشخص‌شده را زمانی که با فونت مشخص و در قالب مشخص رسم می‌شود، برمی‌گرداند.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | رشته‌ای که اندازه‌اش باید محاسبه شود |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | فونتی که برای رسم رشته استفاده می‌شود |
| layoutArea | [SizeF](../../sizef/) const\& | حداکثر ناحیهٔ چیدمان رشته |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | قالب رشته را مشخص می‌کند |

### مقدار بازگشتی

یک شیء [SizeF](../../sizef/) که اندازهٔ رشته را در واحدهای اندازه‌گیری مشخص‌شده توسط ویژگی PageUnit شیء Graphics فعلی نشان می‌دهد.

## مطالب مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [SizeF](../../sizef/)
* کلاس [String](../../../system/string/)
* کلاس [Font](../../font/)
* کلاس [PointF](../../pointf/)
* کلاس [StringFormat](../../stringformat/)
* کلاس [Graphics](../)
* فضای نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)