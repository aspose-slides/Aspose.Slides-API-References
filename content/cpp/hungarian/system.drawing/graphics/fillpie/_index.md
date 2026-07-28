---
title: FillPie()
second_title: Aspose.Slides for C++ API Referencia
description: Kitölti a megadott szektort a megadott ecsettel a jelenlegi objektum által képviselt felületen.
type: docs
weight: 274
url: /hu/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) metódus

Kitölti a megadott sektort a megadott ecsettel a jelenlegi objektum által képviselt felületen.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A szektor kitöltéséhez használandó ecset |
| x | int | Az ellipszist meghatározó téglalap bal felső sarkának X koordinátája |
| y | int | Az ellipszist meghatározó téglalap bal felső sarkának Y koordinátája |
| width | int | Az ellipszist meghatározó téglalap szélessége |
| height | int | Az ellipszist meghatározó téglalap magassága |
| startAngle | int | Az X tengelytől óramutató járásával megegyező irányban a szektor kiindulási pontjáig mért fokban kifejezett szög |
| sweepAngle | int | Az **startAngle**-tól a szektor végpontjáig óramutató járásával megegyező irányban mért fokban kifejezett szög |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) metódus

Kitölti a megadott sektort a megadott ecsettel a jelenlegi objektum által képviselt felületen.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A szektor kitöltéséhez használandó ecset |
| x | **float** | Az ellipszist meghatározó téglalap bal felső sarkának X koordinátája |
| y | **float** | Az ellipszist meghatározó téglalap bal felső sarkának Y koordinátája |
| width | **float** | Az ellipszist meghatározó téglalap szélessége |
| height | **float** | Az ellipszist meghatározó téglalap magassága |
| startAngle | **float** | Az X tengelytől óramutató járásával megegyező irányban a szektor kiindulási pontjáig mért fokban kifejezett szög |
| sweepAngle | **float** | Az **startAngle**-tól a szektor végpontjáig óramutató járásával megegyező irányban mért fokban kifejezett szög |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) metódus

Kitölti a megadott sektort a megadott ecsettel a jelenlegi objektum által képviselt felületen.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A szektor kitöltéséhez használandó ecset |
| rect | [Rectangle](../../rectangle/) | Az ellipszist meghatározó téglalap |
| startAngle | **float** | Az X tengelytől óramutató járásával megegyező irányban a szektor kiindulási pontjáig mért fokban kifejezett szög |
| sweepAngle | **float** | Az **startAngle**-tól a szektor végpontjáig óramutató járásával megegyező irányban mért fokban kifejezett szög |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Brush](../../brush/)
* Osztály [Graphics](../)
* Osztály [Rectangle](../../rectangle/)
* Névtere [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)