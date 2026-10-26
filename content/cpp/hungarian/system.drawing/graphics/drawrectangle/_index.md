---
title: DrawRectangle()
second_title: Aspose.Slides for C++ API-referencia
description: A megadott téglalapot a megadott Pen használatával a jelenlegi objektum által képviselt felületen rajzolja.
type: docs
weight: 287
url: /hu/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) metódus

A megadott téglalapot a megadott pen használatával a jelenlegi objektum által képviselt felületen rajzolja.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A téglalap rajzolásához használandó pen |
| x | int | A rajzolandó téglalap bal felső sarkának X koordinátája |
| y | int | A rajzolandó téglalap bal felső sarkának Y koordinátája |
| width | int | A rajzolandó téglalap szélessége |
| height | int | A rajzolandó téglalap magassága |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) metódus

A megadott téglalapot a megadott pen használatával a jelenlegi objektum által képviselt felületen rajzolja.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A téglalap rajzolásához használandó pen |
| x | **float** | A rajzolandó téglalap bal felső sarkának X koordinátája |
| y | **float** | A rajzolandó téglalap bal felső sarkának Y koordinátája |
| width | **float** | A rajzolandó téglalap szélessége |
| height | **float** | A rajzolandó téglalap magassága |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) metódus

A megadott téglalapot a megadott pen használatával a jelenlegi objektum által képviselt felületen rajzolja.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A téglalap rajzolásához használandó pen |
| rect | [Rectangle](../../rectangle/) | Egy [Rectangle](../../rectangle/) objektum, amely meghatározza a rajzolandó téglalap helyét és méretét |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Pen](../../pen/)
* Osztály [Graphics](../)
* Osztály [Rectangle](../../rectangle/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)