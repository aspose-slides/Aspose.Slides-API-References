---
title: Flatten()
second_title: مرجع API Aspose.Slides برای C++
description: هر منحنی در مسیر را با تبدیل آن به مجموعه‌ای از خطوط متصل صاف می‌کند. مقدار flatness برابر 0.25 استفاده می‌شود.
type: docs
weight: 391
url: /fa/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() متد

هر منحنی در مسیر را با تبدیل به مجموعه‌ای از خطوط متصل، صاف می‌کند. مقدار flatness برابر 0.25 استفاده می‌شود.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) متد

هر منحنی در مسیر را با تبدیل به مجموعه‌ای از خطوط متصل، صاف می‌کند. مقدار flatness برابر 0.25 استفاده می‌شود.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | ماتریس تبدیل برای اعمال بر مسیر قبل از صاف‌سازی |

## GraphicsPath::Flatten(const MatrixPtr\&, float) متد

هر منحنی در مسیر را با تبدیل به مجموعه‌ای از خطوط متصل، صاف می‌کند.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | ماتریس تبدیل برای اعمال بر مسیر قبل از صاف‌سازی |
| flatness | **float** | حداکثر خطای مجاز بین منحنی و تقریب صاف‌سازی شده آن را مشخص می‌کند |

## مراجع دیگر

* Typedef [MatrixPtr](../../matrixptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)