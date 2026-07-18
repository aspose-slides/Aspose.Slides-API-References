---
title: DrawClosedCurve()
second_title: Aspose.Slides για C++ Αναφορά API
description: Σχεδιάζει μια κλειστή spline χρησιμοποιώντας το καθορισμένο στυλό.
type: docs
weight: 781
url: /el/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) μέθοδος

Σχεδιάζει μια κλειστή spline χρησιμοποιώντας το καθορισμένο στυλό.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα στυλό για χρήση κατά τη σχεδίαση της spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) σημείων που καθορίζουν τη spline |
| tension | **float** | Τιμή που καθορίζει την τάση της spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | ΑΓΝΟΟΥΜΕΝΟ |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) μέθοδος

Σχεδιάζει μια κλειστή spline χρησιμοποιώντας το καθορισμένο στυλό.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα στυλό για χρήση κατά τη σχεδίαση της spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) σημείων που καθορίζουν τη spline |
| tension | **float** | Τιμή που καθορίζει την τάση της spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | ΑΓΝΟΟΥΜΕΝΟ |

## Δείτε επίσης

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Pen](../../pen/)
* Κλάση [Point](../../point/)
* Κλάση [Graphics](../)
* Κλάση [PointF](../../pointf/)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)