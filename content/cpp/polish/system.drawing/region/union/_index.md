---
title: Union()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zastępuje region reprezentowany przez bieżący obiekt wynikiem operacji łączenia tego regionu i regionu określonego przez podany prostokąt.
type: docs
weight: 53
url: /pl/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) metoda


Zastępuje region reprezentowany przez bieżący obiekt wynikiem operacji łączenia tego regionu i regionu określonego przez podany prostokąt.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Prostokąt definiujący region, z którym należy połączyć ten region |

## Region::Union(const Rectangle\&) metoda


Zastępuje region reprezentowany przez bieżący obiekt wynikiem łączenia tego regionu i regionu określonego przez podany prostokąt.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Prostokąt definiujący region, z którym należy połączyć ten region |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metoda


Zastępuje region reprezentowany przez bieżący obiekt wynikiem łączenia tego regionu i regionu określonego przez podaną ścieżkę.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Ścieżka definiująca region, z którym należy połączyć ten region |

## Region::Union(const SharedPtr\<Region\>\&) metoda


Zastępuje region reprezentowany przez bieżący obiekt wynikiem łączenia tego regionu i wskazanego regionu.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Region, z którym należy połączyć ten region |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [RectangleF](../../rectanglef/)
* Klasa [Region](../)
* Klasa [Rectangle](../../rectangle/)
* Klasa [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)