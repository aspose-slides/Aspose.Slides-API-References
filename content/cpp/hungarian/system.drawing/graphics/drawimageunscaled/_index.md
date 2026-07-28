---
title: DrawImageUnscaled()
second_title: Aspose.Slides for C++ API Referenciája
description: A megadott képet az eredeti fizikai méretével a megadott helyen rajzolja.
type: docs
weight: 443
url: /hu/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) method

A megadott képet az eredeti fizikai méretével a megadott helyen rajzolja.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| x | int | A rajzolt kép bal felső sarkának X koordinátája |
| y | int | A rajzolt kép bal felső sarkának Y koordinátája |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) method

A megadott képet az eredeti fizikai méretben egy adott helyen rajzolja meg.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| x | int | A rajzolt kép bal felső sarkának X koordinátája |
| y | int | A rajzolt kép bal felső sarkának Y koordinátája |
| width | int | Nem használt |
| height | int | Nem használt |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) method

A megadott képet az eredeti fizikai méretben a megadott helyen rajzolja.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| rect | const [Rectangle](../../rectangle/)\& | A téglalap, amely meghatározza a rajzolt kép bal felső sarkát. A téglalap X és Y tulajdonságai határozzák meg a bal felső sarkot. A szélesség és magasság értékek figyelmen kívül maradnak. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) method

A megadott képet az eredeti fizikai méretben a megadott helyen rajzolja.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A rajzolandó kép |
| point | const [Point](../../point/)\& | A [Point](../../point/) struktúra, amely meghatározza a rajzolt kép bal felső sarkát. |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Image](../../image/)
* Osztály [Graphics](../)
* Osztály [Rectangle](../../rectangle/)
* Osztály [Point](../../point/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)