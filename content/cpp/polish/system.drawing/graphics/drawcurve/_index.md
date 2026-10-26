---
title: DrawCurve()
second_title: Aspose.Slides dla C++ referencja API
description: Rysuje krzywą sklejającą przy użyciu określonego pióra.
type: docs
weight: 794
url: /pl/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) metoda


Rysuje krzywą sklejającą przy użyciu określonego pióra.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane do rysowania krzywej sklejającej |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) punktów określających krzywą sklejającą |
| tension | **float** | Wartość określająca naprężenie krzywej sklejającej |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) metoda


Rysuje krzywą sklejającą przy użyciu określonego pióra.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane do rysowania krzywej sklejającej |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) punktów określających krzywą sklejającą |
| tension | **float** | Wartość określająca naprężenie krzywej sklejającej |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) metoda


Rysuje krzywą sklejającą przy użyciu określonego pióra.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane do rysowania krzywej sklejającej |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) punktów określających krzywą sklejającą |
| offset | **int32_t** | Przesunięcie od pierwszego elementu w tablicy **points** |
| numberOfSegments | **int32_t** | Liczba segmentów do uwzględnienia w krzywej |
| tension | **float** | Wartość określająca naprężenie krzywej sklejającej |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) metoda


Rysuje krzywą sklejającą przy użyciu określonego pióra.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane do rysowania krzywej sklejającej |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) punktów określających krzywą sklejającą |
| offset | **int32_t** | Przesunięcie od pierwszego elementu w tablicy **points** |
| numberOfSegments | **int32_t** | Liczba segmentów do uwzględnienia w krzywej |
| tension | **float** | Wartość określająca naprężenie krzywej sklejającej |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Pen](../../pen/)
* Klasa [Point](../../point/)
* Klasa [Graphics](../)
* Klasa [PointF](../../pointf/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)