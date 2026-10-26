---
title: MeasureString()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een grootte van de opgegeven tekenreeks wanneer deze wordt getekend met het opgegeven lettertype en het opgegeven formaat.
type: docs
weight: 521
url: /nl/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Retourneert een grootte van de opgegeven tekenreeks wanneer deze wordt getekend met het opgegeven lettertype en het opgegeven formaat.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | De tekenreeks waarvan de grootte moet worden berekend |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Het lettertype dat wordt gebruikt om de tekenreeks te tekenen |
| origin | [PointF](../../pointf/) const\& | Specificeert de locatie van de linkerbovenhoek van de tekenreeks |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Specificeert het tekenreeksformaat |

### Retourwaarde

Een [SizeF](../../sizef/) object dat de grootte van de tekenreeks weergeeft in de meeteenheden gespecificeerd door de PageUnit-eigenschap van het huidige Grapphics-object.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

Retourneert een grootte van de opgegeven tekenreeks wanneer deze wordt getekend met het opgegeven lettertype en het opgegeven formaat.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | De tekenreeks waarvan de grootte moet worden berekend |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Het lettertype dat wordt gebruikt om de tekenreeks te tekenen |
| width | int | De maximale breedte van de tekenreeks |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Specificeert het tekenreeksformaat |

### Retourwaarde

Een [SizeF](../../sizef/) object dat de grootte van de tekenreeks weergeeft in de meeteenheden gespecificeerd door de PageUnit-eigenschap van het huidige Grapphics-object.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

NIET GEREALISEERD.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Retourneert een grootte van de opgegeven tekenreeks wanneer deze wordt getekend met het opgegeven lettertype en het opgegeven formaat.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | De tekenreeks waarvan de grootte moet worden berekend |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Het lettertype dat wordt gebruikt om de tekenreeks te tekenen |
| layoutArea | [SizeF](../../sizef/) const\& | Het maximale opmaaksgebied van de tekenreeks |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Specificeert het tekenreeksformaat |

### Retourwaarde

Een [SizeF](../../sizef/) object dat de grootte van de tekenreeks weergeeft in de meeteenheden gespecificeerd door de PageUnit-eigenschap van het huidige Grapphics-object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [SizeF](../../sizef/)
* Klasse [String](../../../system/string/)
* Klasse [Font](../../font/)
* Klasse [PointF](../../pointf/)
* Klasse [StringFormat](../../stringformat/)
* Klasse [Graphics](../)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)