---
title: MeasureString()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací velikost zadaného řetězce při vykreslení ve zvoleném fontu ve zvoleném formátu.
type: docs
weight: 521
url: /cs/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const metoda


Vrátí velikost zadaného řetězce při vykreslení ve zvoleném fontu ve zvoleném formátu.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Řetězec, jehož velikost se má vypočítat |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Font použitý k vykreslení řetězce |
| origin | [PointF](../../pointf/) const\& | Určuje polohu levého horního rohu řetězce |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Určuje formát řetězce |

### Návratová hodnota

Objekt [SizeF](../../sizef/), který představuje velikost řetězce v měrných jednotkách určených vlastností PageUnit aktuálního objektu Grapphics.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const metoda


Vrátí velikost zadaného řetězce při vykreslení ve zvoleném fontu ve zvoleném formátu.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Řetězec, jehož velikost se má vypočítat |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Font použitý k vykreslení řetězce |
| width | int | Maximální šířka řetězce |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Určuje formát řetězce |

### Návratová hodnota

Objekt [SizeF](../../sizef/), který představuje velikost řetězce v měrných jednotkách určených vlastností PageUnit aktuálního objektu Grapphics.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const metoda


NEIMPLEMENTOVÁNO.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```


## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const metoda


Vrátí velikost zadaného řetězce při vykreslení ve zvoleném fontu ve zvoleném formátu.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Řetězec, jehož velikost se má vypočítat |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Font použitý k vykreslení řetězce |
| layoutArea | [SizeF](../../sizef/) const\& | Maximální oblast pro rozvržení řetězce |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Určuje formát řetězce |

### Návratová hodnota

Objekt [SizeF](../../sizef/), který představuje velikost řetězce v měrných jednotkách určených vlastností PageUnit aktuálního objektu Grapphics.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [SizeF](../../sizef/)
* Třída [String](../../../system/string/)
* Třída [Font](../../font/)
* Třída [PointF](../../pointf/)
* Třída [StringFormat](../../stringformat/)
* Třída [Graphics](../)
* Jmenný prostor [System::Drawing](../../)
* Library [Aspose.Slides](../../../)