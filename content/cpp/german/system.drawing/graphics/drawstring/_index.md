---
title: DrawString()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeichnet die angegebene Zeichenfolge an der angegebenen Position unter Verwendung der angegebenen Schriftart und des angegebenen Pinsels.
type: docs
weight: 365
url: /de/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method

Zeichnet die angegebene Zeichenfolge an der angegebenen Position unter Verwendung der angegebenen Schriftart und des angegebenen Pinsels.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Die zu zeichnende Zeichenfolge |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Eine zu verwendende Schriftart |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ein [Brush](../../brush/) Objekt zum Zeichnen |
| topLeft | [PointF](../../pointf/) | Gibt die Position der oberen linken Ecke der gezeichneten Zeichenfolge an |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Gibt das Format der Zeichenfolge an |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method

Zeichnet die angegebene Zeichenfolge im angegebenen Rechteck unter Verwendung der angegebenen Schriftart und des angegebenen Pinsels.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Die zu zeichnende Zeichenfolge |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Eine zu verwendende Schriftart |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ein [Brush](../../brush/) Objekt zum Zeichnen |
| layoutRectangle | [RectangleF](../../rectanglef/) | Gibt ein Rechteck an, in dem die Zeichenfolge gezeichnet wird |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Gibt das Format der Zeichenfolge an |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method

Zeichnet die angegebene Zeichenfolge an der angegebenen Position unter Verwendung der angegebenen Schriftart und des angegebenen Pinsels.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Die zu zeichnende Zeichenfolge |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Eine zu verwendende Schriftart |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ein [Brush](../../brush/) Objekt zum Zeichnen |
| x | **float** | Die X-Koordinate der Position der oberen linken Ecke der gezeichneten Zeichenfolge |
| y | **float** | Die Y-Koordinate der Position der oberen linken Ecke der gezeichneten Zeichenfolge |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Gibt das Format der Zeichenfolge an |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Font](../../font/)
* Klasse [Brush](../../brush/)
* Klasse [PointF](../../pointf/)
* Klasse [StringFormat](../../stringformat/)
* Klasse [Graphics](../)
* Klasse [RectangleF](../../rectanglef/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)