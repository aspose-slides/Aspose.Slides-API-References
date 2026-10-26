---
title: SetClip()
second_title: Aspose.Slides C++ API-referencia
description: Beállítja a jelenlegi Graphics objektum által képviselt rajzoló felület vágó régióját a megadott művelet eredményére, amely egyesíti a jelenlegi vágó régiót és a megadott régiót.
type: docs
weight: 690
url: /hu/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) metódus

Beállítja a jelenlegi [Graphics](../) objektum által képviselt rajzoló felület vágó régióját a megadott művelet eredményére, amely összevonja a jelenlegi vágó régiót és a megadott régiót.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Megadja az egyesítendő régiót |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Megadja az egyesítési műveletet |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) metódus

Beállítja a jelenlegi [Graphics](../) objektum által képviselt rajzoló felület vágó régióját a megadott művelet eredményére, amely összevonja a jelenlegi vágó régiót és a megadott régiót.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Megadja az egyesítendő régiót |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Megadja az egyesítési műveletet |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) metódus

Beállítja a jelenlegi [Graphics](../) objektum által képviselt rajzoló felület vágó régióját a megadott művelet eredményére, amely összevonja a jelenlegi vágó régiót és a megadott régiót.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Megadja az egyesítendő régiót |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Megadja az egyesítési műveletet |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) metódus

NEM IMPLEMENTÁLT.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) metódus

Beállítja a jelenlegi [Graphics](../) objektum által képviselt rajzoló felület vágó régióját a megadott művelet eredményére, amely összevonja a jelenlegi vágó régiót és a grafikus útvonallal megadott régiót.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Megadja az egyesítendő régiót |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Megadja az egyesítési műveletet |

## Lásd még

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Region](../../region/)
* Osztály [Graphics](../)
* Osztály [Rectangle](../../rectangle/)
* Osztály [RectangleF](../../rectanglef/)
* Osztály [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Névtere [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)