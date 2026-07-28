---
title: DrawArc()
second_title: Aspose.Slides C++ API referenciája
description: A megadott tollal rajzolja meg a megadott ívet a jelenlegi objektum által képviselt felületen.
type: docs
weight: 248
url: /hu/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) method

Az aktuális objektum által képviselt felületen a megadott tollal rajzolja meg a megadott ívet.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen, amelyet az ív rajzolásához használ |
| x | **int32_t** | Az ellipszist meghatározó téglalap bal felső sarkának X koordinátája |
| y | **int32_t** | Az ellipszist meghatározó téglalap bal felső sarkának Y koordinátája |
| width | **int32_t** | Az ellipszist meghatározó téglalap szélessége |
| height | **int32_t** | Az ellipszist meghatározó téglalap magassága |
| startAngle | **int32_t** | Szög fokban, óramutató járásával megegyező irányban mérve az X tengelytől az ív kezdőpontjáig |
| sweepAngle | **int32_t** | Szög fokban, óramutató járásával megegyező irányban mérve az **startAngle**-tól az ív végpontjáig |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) method

Az aktuális objektum által képviselt felületen a megadott tollal rajzolja meg a megadott ívet.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen, amelyet az ív rajzolásához használ |
| x | **float** | Az ellipszist meghatározó téglalap bal felső sarkának X koordinátája |
| y | **float** | Az ellipszist meghatározó téglalap bal felső sarkának Y koordinátája |
| width | **float** | Az ellipszist meghatározó téglalap szélessége |
| height | **float** | Az ellipszist meghatározó téglalap magassága |
| startAngle | **float** | Szög fokban, óramutató járásával megegyező irányban mérve az X tengelytől az ív kezdőpontjáig |
| sweepAngle | **float** | Szög fokban, óramutató járásával megegyező irányban mérve az **startAngle**-tól az ív végpontjáig |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) method

Az aktuális objektum által képviselt felületen a megadott tollal rajzolja meg a megadott ívet.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen, amelyet az ív rajzolásához használ |
| rect | [Rectangle](../../rectangle/) | A téglalap, amely az ellipszist meghatározza |
| startAngle | **float** | Szög fokban, óramutató járásával megegyező irányban mérve az X tengelytől az ív kezdőpontjáig |
| sweepAngle | **float** | Szög fokban, óramutató járásával megegyező irányban mérve az **startAngle**-tól az ív végpontjáig |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) method

Az aktuális objektum által képviselt felületen a megadott tollal rajzolja meg a megadott ívet.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen, amelyet az ív rajzolásához használ |
| rect | [RectangleF](../../rectanglef/) | A téglalap, amely az ellipszist meghatározza |
| startAngle | **float** | Szög fokban, óramutató járásával megegyező irányban mérve az X tengelytől az ív kezdőpontjáig |
| sweepAngle | **float** | Szög fokban, óramutató járásával megegyező irányban mérve az **startAngle**-tól az ív végpontjáig |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)