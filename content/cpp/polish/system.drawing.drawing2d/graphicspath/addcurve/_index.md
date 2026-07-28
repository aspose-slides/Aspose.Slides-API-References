---
title: AddCurve()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dodaje określoną krzywą do ścieżki reprezentowanej przez bieżący obiekt.
type: docs
weight: 274
url: /pl/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) metoda

Dodaje określoną krzywą do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punkty określające krzywą |
| tension | **float** | Określa stopień, w jakim krzywa wygina się pomiędzy punktami kontrolnymi |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) metoda

Dodaje określoną krzywą do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punkty określające krzywą |
| tension | **float** | Określa stopień, w jakim krzywa wygina się pomiędzy punktami kontrolnymi |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) metoda

Dodaje określoną krzywą do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punkty określające krzywą |
| offset | int | Indeks punktu w **points**, który jest używany jako punkt początkowy krzywej |
| number_of_segments | int | Liczba segmentów używanych do rysowania krzywej |
| tension | **float** | Określa stopień, w jakim krzywa wygina się pomiędzy punktami kontrolnymi |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) metoda

Dodaje określoną krzywą do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punkty określające krzywą |
| offset | int | Indeks punktu w **points**, który jest używany jako punkt początkowy krzywej |
| number_of_segments | int | Liczba segmentów używanych do rysowania krzywej |
| tension | **float** | Określa stopień, w jakim krzywa wygina się pomiędzy punktami kontrolnymi |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [PointF](../../../system.drawing/pointf/)
* Klasa [GraphicsPath](../)
* Klasa [Point](../../../system.drawing/point/)
* Przestrzeń nazw [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)