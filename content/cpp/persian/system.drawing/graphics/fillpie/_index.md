---
title: FillPie()
second_title: مرجع API Aspose.Slides برای C++
description: پای مشخص‌شده را با استفاده از brush مشخص‌شده روی سطحی که توسط شیء فعلی نمایان می‌شود پر می‌کند.
type: docs
weight: 274
url: /fa/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) متد

پای مشخص‌شده را با استفاده از brush مشخص‌شده روی سطحی که توسط شیء فعلی نمایان می‌شود پر می‌کند.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | brush برای استفاده هنگام پر کردن پای |
| x | int | مختصات X گوشهٔ بالایی چپ مستطیلی که بیضی را تعریف می‌کند |
| y | int | مختصات Y گوشهٔ بالایی چپ مستطیلی که بیضی را تعریف می‌کند |
| width | int | عرض مستطیلی که بیضی را تعریف می‌کند |
| height | int | ارتفاع مستطیلی که بیضی را تعریف می‌کند |
| startAngle | int | زاویه بر حسب درجه که ساعت‌گرد از محور X تا نقطهٔ شروع پای اندازه‌گیری می‌شود |
| sweepAngle | int | زاویه بر حسب درجه که ساعت‌گرد از **startAngle** تا نقطهٔ پایان پای اندازه‌گیری می‌شود |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) متد

پای مشخص‌شده را با استفاده از brush مشخص‌شده روی سطحی که توسط شیء فعلی نمایان می‌شود پر می‌کند.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | brush برای استفاده هنگام پر کردن پای |
| x | **float** | مختصات X گوشهٔ بالایی چپ مستطیلی که بیضی را تعریف می‌کند |
| y | **float** | مختصات Y گوشهٔ بالایی چپ مستطیلی که بیضی را تعریف می‌کند |
| width | **float** | عرض مستطیلی که بیضی را تعریف می‌کند |
| height | **float** | ارتفاع مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **float** | زاویه بر حسب درجه که ساعت‌گرد از محور X تا نقطهٔ شروع پای اندازه‌گیری می‌شود |
| sweepAngle | **float** | زاویه بر حسب درجه که ساعت‌گرد از **startAngle** تا نقطهٔ پایان پای اندازه‌گیری می‌شود |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) متد

پای مشخص‌شده را با استفاده از brush مشخص‌شده روی سطحی که توسط شیء فعلی نمایان می‌شود پر می‌کند.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | brush برای استفاده هنگام پر کردن پای |
| rect | [Rectangle](../../rectangle/) | مستطیلی که بیضی را تعریف می‌کند |
| startAngle | **float** | زاویه بر حسب درجه که ساعت‌گرد از محور X تا نقطهٔ شروع پای اندازه‌گیری می‌شود |
| sweepAngle | **float** | زاویه بر حسب درجه که ساعت‌گرد از **startAngle** تا نقطهٔ پایان پای اندازه‌گیری می‌شود |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)