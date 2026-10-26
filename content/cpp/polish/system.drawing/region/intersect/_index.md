---
title: Intersect()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zastępuje region reprezentowany przez bieżący obiekt wynikiem przecięcia tego regionu z regionem określonym przez podany prostokąt.
type: docs
weight: 79
url: /pl/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) metoda

Zastępuje region reprezentowany przez bieżący obiekt wynikiem przecięcia tego regionu z regionem określonym przez podany prostokąt.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Prostokąt, który definiuje region, z którym należy przeciąć ten region |

## Region::Intersect(const Rectangle\&) metoda

Zastępuje region reprezentowany przez bieżący obiekt wynikiem przecięcia tego regionu z regionem określonym przez podany prostokąt.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Prostokąt, który definiuje region, z którym należy przeciąć ten region |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metoda

Zastępuje region reprezentowany przez bieżący obiekt wynikiem przecięcia tego regionu z regionem określonym przez podaną ścieżkę.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Ścieżka, która definiuje region, z którym należy przeciąć ten region |

## Region::Intersect(const SharedPtr\<Region\>\&) metoda

Zastępuje region reprezentowany przez bieżący obiekt wynikiem przecięcia tego regionu ze wskazanym regionem.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Region, z którym należy przeciąć ten region |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [RectangleF](../../rectanglef/)
* Klasa [Region](../)
* Klasa [Rectangle](../../rectangle/)
* Klasa [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)