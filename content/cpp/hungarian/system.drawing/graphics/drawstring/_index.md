---
title: DrawString()
second_title: Aspose.Slides C++ API Referencia
description: Megjeleníti a megadott karakterláncot a megadott helyen a megadott betűtípussal és ecsettel.
type: docs
weight: 365
url: /hu/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metódus

Megjeleníti a megadott karakterláncot a megadott helyen a megadott betűtípussal és ecsettel.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | A megjelenítendő karakterlánc |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | A használandó betűkészlet |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Egy [Brush](../../brush/) objektum a rajzoláshoz |
| topLeft | [PointF](../../pointf/) | Megadja a megrajzolt karakterlánc bal felső sarkának helyét |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Megadja a karakterlánc formátumát |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metódus

Megjeleníti a megadott karakterláncot a megadott téglalapon a megadott betűtípussal és ecsettel.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | A megjelenítendő karakterlánc |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | A használandó betűkészlet |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Egy [Brush](../../brush/) objektum a rajzoláshoz |
| layoutRectangle | [RectangleF](../../rectanglef/) | Megadja a téglalapot, amelyben a karakterláncot meg kell jeleníteni |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Megadja a karakterlánc formátumát |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metódus

Megjeleníti a megadott karakterláncot a megadott helyen a megadott betűtípussal és ecsettel.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | A megjelenítendő karakterlánc |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | A használandó betűkészlet |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Egy [Brush](../../brush/) objektum a rajzoláshoz |
| x | **float** | Az X koordináta a megrajzolt karakterlánc bal felső sarkának helyéhez |
| y | **float** | Az Y koordináta a megrajzolt karakterlánc bal felső sarkának helyéhez |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Megadja a karakterlánc formátumát |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Font](../../font/)
* Osztály [Brush](../../brush/)
* Osztály [PointF](../../pointf/)
* Osztály [StringFormat](../../stringformat/)
* Osztály [Graphics](../)
* Osztály [RectangleF](../../rectanglef/)
* Névtér [System::Drawing](../../)
* Library [Aspose.Slides](../../../)