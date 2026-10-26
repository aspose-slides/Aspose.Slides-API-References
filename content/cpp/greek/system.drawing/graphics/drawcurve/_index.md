---
title: DrawCurve()
second_title: Aspose.Slides για C++ API Αναφορά
description: Σχεδίαζει μια spline χρησιμοποιώντας το καθορισμένο pen.
type: docs
weight: 794
url: /el/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) method

Σχεδίαζει μια spline χρησιμοποιώντας το καθορισμένο pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) σημείων που καθορίζουν τη spline |
| tension | **float** | Τιμή που καθορίζει την ένταση της spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) method

Σχεδίαζει μια spline χρησιμοποιώντας το καθορισμένο pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) σημείων που καθορίζουν τη spline |
| tension | **float** | Τιμή που καθορίζει την ένταση της spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) method

Σχεδίαζει μια spline χρησιμοποιώντας το καθορισμένο pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) σημείων που καθορίζουν τη spline |
| offset | **int32_t** | Μετατόπιση από το πρώτο στοιχείο στον πίνακα **points** |
| numberOfSegments | **int32_t** | Αριθμός τμημάτων που θα προστεθούν στην καμπύλη |
| tension | **float** | Τιμή που καθορίζει την ένταση της spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) method

Σχεδίαζει μια spline χρησιμοποιώντας το καθορισμένο pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) σημείων που καθορίζουν τη spline |
| offset | **int32_t** | Μετατόπιση από το πρώτο στοιχείο στον πίνακα **points** |
| numberOfSegments | **int32_t** | Αριθμός τμημάτων που θα προστεθούν στην καμπύλη |
| tension | **float** | Τιμή που καθορίζει την ένταση της spline |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)