---
title: AddString()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen Textstring zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.
type: docs
weight: 170
url: /de/system.drawing.drawing2d/graphicspath/addstring/
---
## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Point, const SharedPtr\<StringFormat\>\&) Methode

Fügt einen Textstring zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Point origin, const SharedPtr<StringFormat> &stringFormat)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | Der hinzuzufügende Text |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | Die zum Zeichnen des Textes verwendete Schriftfamilie |
| style | int | Ein FontStyle-Enumerationswert, der den zu verwendenden Schriftstil angibt |
| emSize | **float** | Die Höhe des Em-Quadratkastens, der jedes Zeichen der Zeichenkette begrenzt |
| origin | [Point](../../../system.drawing/point/) | Gibt den Ort an, an dem der Text beginnt |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | Das Format der Zeichenkette |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, PointF, const SharedPtr\<StringFormat\>\&) Methode

Fügt einen Textstring zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, PointF origin, const SharedPtr<StringFormat> &stringFormat)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | Der hinzuzufügende Text |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | Die zum Zeichnen des Textes verwendete Schriftfamilie |
| style | int | Ein FontStyle-Enumerationswert, der den zu verwendenden Schriftstil angibt |
| emSize | **float** | Die Höhe des Em-Quadratkastens, der jedes Zeichen der Zeichenkette begrenzt |
| origin | [PointF](../../../system.drawing/pointf/) | Gibt den Ort an, an dem der Text beginnt |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | Das Format der Zeichenkette |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Rectangle, const SharedPtr\<StringFormat\>\&) Methode

Fügt einen Textstring zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Rectangle layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | Der hinzuzufügende Text |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | Die zum Zeichnen des Textes verwendete Schriftfamilie |
| style | int | Ein FontStyle-Enumerationswert, der den zu verwendenden Schriftstil angibt |
| emSize | **float** | Die Höhe des Em-Quadratkastens, der jedes Zeichen der Zeichenkette begrenzt |
| layoutRect | [Rectangle](../../../system.drawing/rectangle/) | Ein Rechteck, das den Text begrenzt |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | Das Format der Zeichenkette |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, RectangleF, const SharedPtr\<StringFormat\>\&) Methode

Fügt einen Textstring zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | Der hinzuzufügende Text |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | Die zum Zeichnen des Textes verwendete Schriftfamilie |
| style | int | Ein FontStyle-Enumerationswert, der den zu verwendenden Schriftstil angibt |
| emSize | **float** | Die Höhe des Em-Quadratkastens, der jedes Zeichen der Zeichenkette begrenzt |
| layoutRect | [RectangleF](../../../system.drawing/rectanglef/) | Ein Rechteck, das den Text begrenzt |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | Das Format der Zeichenkette |

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [FontFamily](../../../system.drawing/fontfamily/)
* Class [Point](../../../system.drawing/point/)
* Class [StringFormat](../../../system.drawing/stringformat/)
* Class [GraphicsPath](../)
* Class [PointF](../../../system.drawing/pointf/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)