---
title: GetHeight()
second_title: مرجع API Aspose.Slides برای C++
description: فاصله خطوط قلم نمایانده شده توسط شیء فعلی را در واحد جاری یک شیء Graphics مشخص برمی‌گرداند.
type: docs
weight: 14
url: /fa/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) متد

ارتفاع خطوط قلم نمایانده شده توسط شیء فعلی را برمی‌گرداند، در واحد جاری یک شیء [Graphics](../../graphics/) مشخص.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | شیء [Graphics](../../graphics/) که واحدهای اندازه‌گیری را مشخص می‌کند |

## Font::GetHeight(float) متد

ارتفاع قلم نمایانده شده توسط شیء فعلی را زمانی که بر روی دستگاه نمایشی با وضوح عمودی مشخص رسم می‌شود، برمی‌گرداند.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dpi | **float** | وضوح عمودی دستگاه نمایش |

### مقدار بازگشت

ارتفاع قلم به پیکسل

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Graphics](../../graphics/)
* کلاس [Font](../)
* فضای‌نام [System::Drawing](../../)
* Library [Aspose.Slides](../../../)