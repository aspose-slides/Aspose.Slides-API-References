---
title: DrawArc()
second_title: مستندات API Aspose.Slides برای C++
description: قوس مشخص را با استفاده از قلم مشخص روی سطحی که توسط شیء جاری نمایان شده است، رسم می‌کند.
type: docs
weight: 248
url: /fa/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) متد


قوس مشخص را با استفاده از قلم مشخص روی سطحی که توسط شیء جاری نمایان شده است، رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلمی برای استفاده هنگام رسم قوس |
| x | **int32_t** | مختصات X گوشهٔ بالایی چپ مستطیلی که بیضی را تعریف می‌کند |
| y | **int32_t** | مختصات Y گوشهٔ بالایی چپ مستطیلی که بیضی را تعریف می‌کند |
| width | **int32_t** | عرض مستطیلی که بیضی را تعریف می‌کند |
| height | **int32_t** | ارتفاع مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **int32_t** | زاویه به درجه اندازه‌گیری شده به سمت ساعتگرد از محور X تا نقطه شروع قوس |
| sweepAngle | **int32_t** | زاویه به درجه اندازه‌گیری شده به سمت ساعتگرد از **startAngle** تا نقطه پایان قوس |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) متد


قوس مشخص را با استفاده از قلم مشخص روی سطحی که توسط شیء جاری نمایان شده است، رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلمی برای استفاده هنگام رسم قوس |
| x | **float** | مختصات X گوشهٔ بالایی چپ مستطیلی که بیضی را تعریف می‌کند |
| y | **float** | مختصات Y گوشهٔ بالایی چپ مستطیلی که بیضی را تعریف می‌کند |
| width | **float** | عرض مستطیلی که بیضی را تعریف می‌کند |
| height | **float** | ارتفاع مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **float** | زاویه به درجه اندازه‌گیری شده به سمت ساعتگرد از محور X تا نقطه شروع قوس |
| sweepAngle | **float** | زاویه به درجه اندازه‌گیری شده به سمت ساعتگرد از **startAngle** تا نقطه پایان قوس |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) متد


قوس مشخص را با استفاده از قلم مشخص روی سطحی که توسط شیء جاری نمایان شده است، رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلمی برای استفاده هنگام رسم قوس |
| rect | [Rectangle](../../rectangle/) | مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **float** | زاویه به درجه اندازه‌گیری شده به سمت ساعتگرد از محور X تا نقطه شروع قوس |
| sweepAngle | **float** | زاویه به درجه اندازه‌گیری شده به سمت ساعتگرد از **startAngle** تا نقطه پایان قوس |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) متد


قوس مشخص را با استفاده از قلم مشخص روی سطحی که توسط شیء جاری نمایان شده است، رسم می‌کند.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلمی برای استفاده هنگام رسم قوس |
| rect | [RectangleF](../../rectanglef/) | مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **float** | زاویه به درجه اندازه‌گیری شده به سمت ساعتگرد از محور X تا نقطه شروع قوس |
| sweepAngle | **float** | زاویه به درجه اندازه‌گیری شده به سمت ساعتگرد از **startAngle** تا نقطه پایان قوس |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Pen](../../pen/)
* کلاس [Graphics](../)
* کلاس [Rectangle](../../rectangle/)
* کلاس [RectangleF](../../rectanglef/)
* فضای‌نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)