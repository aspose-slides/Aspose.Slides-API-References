---
title: Matrix()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Matrix वर्ग का एक नया उदाहरण बनाता है जो एक पहचान मैट्रिक्स का प्रतिनिधित्व करता है।
type: docs
weight: 1
url: /hi/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() निर्माता

एक नई instance बनाता है [Matrix](../) वर्ग की जो एक identity matrix का प्रतिनिधित्व करता है।

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) निर्माता

एक नई instance बनाता है [Matrix](../) वर्ग की और इसे निर्दिष्ट मानों से initialise करता है।

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| m11 | **float** | 1-st पंक्ति 1-st स्तंभ का मान |
| m12 | **float** | 1-st पंक्ति 2-nd स्तंभ का मान |
| m21 | **float** | 2-nd पंक्ति 1-st स्तंभ का मान |
| m22 | **float** | 2-nd पंक्ति 2-nd स्तंभ का मान |
| dx | **float** | 3-rd पंक्ति 1-st स्तंभ का मान |
| dy | **float** | 3-rd पंक्ति 2-nd स्तंभ का मान |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) निर्माता

एक नई instance बनाता है [Matrix](../) वर्ग की जो निर्दिष्ट rectangle और points के array द्वारा परिभाषित geometric transform को दर्शाता है।

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) निर्माता

एक नई instance बनाता है [Matrix](../) वर्ग की जो निर्दिष्ट rectangle और points के array द्वारा परिभाषित geometric transform को दर्शाता है।

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## देखें

* टाइपडेफ़ [ArrayPtr](../../../system/arrayptr/)
* वर्ग [Matrix](../)
* वर्ग [Rectangle](../../../system.drawing/rectangle/)
* वर्ग [Point](../../../system.drawing/point/)
* वर्ग [RectangleF](../../../system.drawing/rectanglef/)
* वर्ग [PointF](../../../system.drawing/pointf/)
* नेमस्पेस [System::Drawing::Drawing2D](../../)
* लाइब्रेरी [Aspose.Slides](../../../)