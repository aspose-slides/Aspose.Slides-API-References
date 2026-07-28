---
title: DrawPie()
second_title: Aspose.Slides C++ API referencia
description: A megadott körszelet a megadott tollal rajzolja a jelenlegi objektum által képviselt felületen.
type: docs
weight: 261
url: /hu/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) metódus

A megadott körszelet a megadott tollal rajzolja a jelenlegi objektum által képviselt felületen.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A toll, amelyet a körszelet rajzolásához használ |
| x | **int32_t** | Az X koordináta a kört meghatározó téglalap bal felső sarkában |
| y | **int32_t** | Az Y koordináta a kört meghatározó téglalap bal felső sarkában |
| width | **int32_t** | A téglalap szélessége, amely meghatározza az ellipszist |
| height | **int32_t** | A téglalap magassága, amely meghatározza az ellipszist |
| startAngle | **int32_t** | A fokban kifejezett szög, amelyet az X tengelytől az óramutató járásával megegyező irányban mérnek a körszelet kiindulópontjáig |
| sweepAngle | **int32_t** | A fokban kifejezett szög, amelyet az **startAngle**-től az óramutató járásával megegyező irányban mérnek a körszelet végpontjáig |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) metódus

A megadott körszelet a megadott tollal rajzolja a jelenlegi objektum által képviselt felületen.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A toll, amelyet a körszelet rajzolásához használ |
| x | **float** | Az X koordináta a kört meghatározó téglalap bal felső sarkában |
| y | **float** | Az Y koordináta a kört meghatározó téglalap bal felső sarkában |
| width | **float** | A téglalap szélessége, amely meghatározza az ellipszist |
| height | **float** | A téglalap magassága, amely meghatározza az ellipszist |
| startAngle | **float** | A fokban kifejezett szög, amelyet az X tengelytől az óramutató járásával megegyező irányban mérnek a körszelet kiindulópontjáig |
| sweepAngle | **float** | A fokban kifejezett szög, amelyet az **startAngle**-től az óramutató járásával megegyező irányban mérnek a körszelet végpontjáig |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) metódus

A megadott körszelet a megadott tollal rajzolja a jelenlegi objektum által képviselt felületen.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A toll, amelyet a körszelet rajzolásához használ |
| rect | [Rectangle](../../rectangle/) | A téglalap, amely meghatározza az ellipszist |
| startAngle | **float** | A fokban kifejezett szög, amelyet az X tengelytől az óramutató járásával megegyező irányban mérnek a körszelet kiindulópontjáig |
| sweepAngle | **float** | A fokban kifejezett szög, amelyet az **startAngle**-től az óramutató járásával megegyező irányban mérnek a körszelet végpontjáig |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) metódus

A megadott körszelet a megadott tollal rajzolja a jelenlegi objektum által képviselt felületen.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A toll, amelyet a körszelet rajzolásához használ |
| rect | [RectangleF](../../rectanglef/) | A téglalap, amely meghatározza az ellipszist |
| startAngle | **float** | A fokban kifejezett szög, amelyet az X tengelytől az óramutató járásával megegyező irányban mérnek a körszelet kiindulópontjáig |
| sweepAngle | **float** | A fokban kifejezett szög, amelyet az **startAngle**-től az óramutató járásával megegyező irányban mérnek a körszelet végpontjáig |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)