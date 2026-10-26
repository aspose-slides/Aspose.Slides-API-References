---
title: DrawPie()
second_title: مرجع API Aspose.Slides برای C++
description: پای مشخص شده را با استفاده از قلم تعیین‌شده بر روی سطحی که توسط شیء جاری نمایان شده است، ترسیم می‌کند.
type: docs
weight: 261
url: /fa/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) method

پای موردنظر را با استفاده از قلم مشخص شده بر روی سطحی که توسط شیء جاری نمایان شده است، ترسیم می‌کند.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | یک pen برای استفاده هنگام ترسیم پای |
| x | **int32_t** | مختصات X گوشهٔ بالا-چپ مستطیلی که بیضی را تعریف می‌کند |
| y | **int32_t** | مختصات Y گوشهٔ بالا-چپ مستطیلی که بیضی را تعریف می‌کند |
| width | **int32_t** | عرض مستطیلی که بیضی را تعریف می‌کند |
| height | **int32_t** | ارتفاع مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **int32_t** | زاویه به درجه که به‌صورت ساعتگرد از محور X تا نقطهٔ شروع پای اندازه‌گیری می‌شود |
| sweepAngle | **int32_t** | زاویه به درجه که به‌صورت ساعتگرد از **startAngle** تا نقطهٔ پایان پای اندازه‌گیری می‌شود |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) method

پای موردنظر را با استفاده از قلم مشخص شده بر روی سطحی که توسط شیء جاری نمایان شده است، ترسیم می‌کند.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | یک pen برای استفاده هنگام ترسیم پای |
| x | **float** | مختصات X گوشهٔ بالا-چپ مستطیلی که بیضی را تعریف می‌کند |
| y | **float** | مختصات Y گوشهٔ بالا-چپ مستطیلی که بیضی را تعریف می‌کند |
| width | **float** | عرض مستطیلی که بیضی را تعریف می‌کند |
| height | **float** | ارتفاع مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **float** | زاویه به درجه که به‌صورت ساعتگرد از محور X تا نقطهٔ شروع پای اندازه‌گیری می‌شود |
| sweepAngle | **float** | زاویه به درجه که به‌صورت ساعتگرد از **startAngle** تا نقطهٔ پایان پای اندازه‌گیری می‌شود |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) method

پای موردنظر را با استفاده از قلم مشخص شده بر روی سطحی که توسط شیء جاری نمایان شده است، ترسیم می‌کند.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | یک pen برای استفاده هنگام ترسیم پای |
| rect | [Rectangle](../../rectangle/) | مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **float** | زاویه به درجه که به‌صورت ساعتگرد از محور X تا نقطهٔ شروع پای اندازه‌گیری می‌شود |
| sweepAngle | **float** | زاویه به درجه که به‌صورت ساعتگرد از **startAngle** تا نقطهٔ پایان پای اندازه‌گیری می‌شود |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) method

پای موردنظر را با استفاده از قلم مشخص شده بر روی سطحی که توسط شیء جاری نمایان شده است، ترسیم می‌کند.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | یک pen برای استفاده هنگام ترسیم پای |
| rect | [RectangleF](../../rectanglef/) | مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **float** | زاویه به درجه که به‌صورت ساعتگرد از محور X تا نقطهٔ شروع پای اندازه‌گیری می‌شود |
| sweepAngle | **float** | زاویه به درجه که به‌صورت ساعتگرد از **startAngle** تا نقطهٔ پایان پای اندازه‌گیری می‌شود |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)