---
title: DrawString()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده را در مکان تعیین‌شده با استفاده از قلم و براش مشخص‌شده رسم می‌کند.
type: docs
weight: 365
url: /fa/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) متد

رشتهٔ مشخص‌شده را در مکان مشخص‌شده با استفاده از قلم و براش مشخص‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | رشته‌ای که باید رسم شود |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | قلمی برای استفاده |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | یک شیء [Brush](../../brush/) برای استفاده در رسم |
| topLeft | [PointF](../../pointf/) | مکان گوشهٔ بالایی سمت چپ رشتهٔ رسم‌شده را مشخص می‌کند |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | قالب رشته را مشخص می‌کند |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) متد

رشتهٔ مشخص‌شده را در مستطیل مشخص‌شده با استفاده از قلم و براش مشخص‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | رشته‌ای که باید رسم شود |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | قلمی برای استفاده |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | یک شیء [Brush](../../brush/) برای استفاده در رسم |
| layoutRectangle | [RectangleF](../../rectanglef/) | یک مستطیل را برای رسم رشته داخل آن مشخص می‌کند |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | قالب رشته را مشخص می‌کند |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) متد

رشتهٔ مشخص‌شده را در مکان مشخص‌شده با استفاده از قلم و براش مشخص‌شده رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | رشته‌ای که باید رسم شود |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | قلمی برای استفاده |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | یک شیء [Brush](../../brush/) برای استفاده در رسم |
| x | **float** | مختصات X مکان گوشهٔ بالایی سمت چپ رشتهٔ رسم‌شده |
| y | **float** | مختصات Y مکان گوشهٔ بالایی سمت چپ رشتهٔ رسم‌شده |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | قالب رشته را مشخص می‌کند |

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [Font](../../font/)
* کلاس [Brush](../../brush/)
* کلاس [PointF](../../pointf/)
* کلاس [StringFormat](../../stringformat/)
* کلاس [Graphics](../)
* کلاس [RectangleF](../../rectanglef/)
* فضای‌نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)