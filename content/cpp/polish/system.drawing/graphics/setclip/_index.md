---
title: SetClip()
second_title: Referencja API Aspose.Slides dla C++
description: Ustawia obszar przycinania powierzchni rysowania reprezentowanej przez bieżący obiekt Graphics na wynik określonej operacji, która łączy bieżący obszar przycinania i określony obszar.
type: docs
weight: 690
url: /pl/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) metoda

Ustawia obszar przycinania powierzchni rysowania reprezentowanej przez bieżący obiekt [Graphics](../) na wynik określonej operacji, która łączy bieżący obszar przycinania i określony obszar.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Określa obszar do połączenia |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Określa operację łączenia |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) metoda

Ustawia obszar przycinania powierzchni rysowania reprezentowanej przez bieżący obiekt [Graphics](../) na wynik określonej operacji, która łączy bieżący obszar przycinania i określony obszar.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Określa obszar do połączenia |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Określa operację łączenia |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) metoda

Ustawia obszar przycinania powierzchni rysowania reprezentowanej przez bieżący obiekt [Graphics](../) na wynik określonej operacji, która łączy bieżący obszar przycinania i określony obszar.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Określa obszar do połączenia |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Określa operację łączenia |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) metoda

NIE ZAIMPLEMENTOWANO.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) metoda

Ustawia obszar przycinania powierzchni rysowania reprezentowanej przez bieżący obiekt [Graphics](../) na wynik określonej operacji, która łączy bieżący obszar przycinania i obszar określony przez ścieżkę graficzną.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Określa obszar do połączenia |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Określa operację łączenia |

## Zobacz także

* Wyliczenie [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Region](../../region/)
* Klasa [Graphics](../)
* Klasa [Rectangle](../../rectangle/)
* Klasa [RectangleF](../../rectanglef/)
* Klasa [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)