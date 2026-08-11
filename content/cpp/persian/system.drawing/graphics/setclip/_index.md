---
title: SetClip()
second_title: Aspose.Slides برای C++ مرجع API
description: منطقهٔ برش سطح نقاشی که توسط شیء Graphics فعلی نمایان شده است را به نتیجهٔ عملیات مشخص‌شده‌ای که منطقهٔ برش فعلی و منطقهٔ مشخص‌شده را ترکیب می‌کند، تنظیم می‌کند.
type: docs
weight: 690
url: /fa/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) متد

نقطهٔ برش سطح رسم نشان داده شده توسط شیء [Graphics](../) فعلی را به نتیجهٔ عملیاتی که منطقهٔ برش فعلی و منطقهٔ مشخص‌شده را ترکیب می‌کند، تنظیم می‌کند.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | منطقه‌ای را برای ترکیب مشخص می‌کند |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | عملیات ترکیب را مشخص می‌کند |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) متد

نقطهٔ برش سطح رسم نشان داده شده توسط شیء [Graphics](../) فعلی را به نتیجهٔ عملیاتی که منطقهٔ برش فعلی و منطقهٔ مشخص‌شده را ترکیب می‌کند، تنظیم می‌کند.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | منطقه‌ای را برای ترکیب مشخص می‌کند |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | عملیات ترکیب را مشخص می‌کند |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) متد

نقطهٔ برش سطح رسم نشان داده شده توسط شیء [Graphics](../) فعلی را به نتیجهٔ عملیاتی که منطقهٔ برش فعلی و منطقهٔ مشخص‌شده را ترکیب می‌کند، تنظیم می‌کند.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | منطقه‌ای را برای ترکیب مشخص می‌کند |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | عملیات ترکیب را مشخص می‌کند |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) متد

پیاده‌سازی نشده.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) متد

نقطهٔ برش سطح رسم نشان داده شده توسط شیء [Graphics](../) فعلی را به نتیجهٔ عملیاتی که منطقهٔ برش فعلی و منطقه‌ای که توسط مسیر گرافیکی مشخص شده است را ترکیب می‌کند، تنظیم می‌کند.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | منطقه‌ای را برای ترکیب مشخص می‌کند |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | عملیات ترکیب را مشخص می‌کند |

## موارد مرتبط

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Region](../../region/)
* کلاس [Graphics](../)
* کلاس [Rectangle](../../rectangle/)
* کلاس [RectangleF](../../rectanglef/)
* کلاس [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* فضای نام [System::Drawing](../../)
* Library [Aspose.Slides](../../../)