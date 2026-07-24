---
title: MeasureString()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Größe der angegebenen Zeichenfolge zurück, wenn sie in der angegebenen Schriftart im angegebenen Format gezeichnet wird.
type: docs
weight: 521
url: /de/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Gibt die Größe der angegebenen Zeichenfolge zurück, wenn sie in der angegebenen Schriftart im angegebenen Format gezeichnet wird.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Die Zeichenfolge, deren Größe berechnet werden soll |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Die Schriftart, die zum Zeichnen der Zeichenfolge verwendet wird |
| origin | [PointF](../../pointf/) const\& | Gibt die Position der oberen linken Ecke der Zeichenfolge an |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Gibt das Zeichenfolgenformat an |

### Rückgabewert

Ein [SizeF](../../sizef/) Objekt, das die Größe der Zeichenfolge in den Messeinheiten darstellt, die durch die PageUnit-Eigenschaft des aktuellen Graphics-Objekts festgelegt sind.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

Gibt die Größe der angegebenen Zeichenfolge zurück, wenn sie in der angegebenen Schriftart im angegebenen Format gezeichnet wird.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Die Zeichenfolge, deren Größe berechnet werden soll |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Die Schriftart, die zum Zeichnen der Zeichenfolge verwendet wird |
| width | int | Die maximale Breite der Zeichenfolge |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Gibt das Zeichenfolgenformat an |

### Rückgabewert

Ein [SizeF](../../sizef/) Objekt, das die Größe der Zeichenfolge in den Messeinheiten darstellt, die durch die PageUnit-Eigenschaft des aktuellen Graphics-Objekts festgelegt sind.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

NICHT IMPLEMENTIERT.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Gibt die Größe der angegebenen Zeichenfolge zurück, wenn sie in der angegebenen Schriftart im angegebenen Format gezeichnet wird.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Die Zeichenfolge, deren Größe berechnet werden soll |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Die Schriftart, die zum Zeichnen der Zeichenfolge verwendet wird |
| layoutArea | [SizeF](../../sizef/) const\& | Der maximale Layout-Bereich der Zeichenfolge |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Gibt das Zeichenfolgenformat an |

### Rückgabewert

Ein [SizeF](../../sizef/) Objekt, das die Größe der Zeichenfolge in den Messeinheiten darstellt, die durch die PageUnit-Eigenschaft des aktuellen Graphics-Objekts festgelegt sind.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SizeF](../../sizef/)
* Klasse [String](../../../system/string/)
* Klasse [Font](../../font/)
* Klasse [PointF](../../pointf/)
* Klasse [StringFormat](../../stringformat/)
* Klasse [Graphics](../)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)