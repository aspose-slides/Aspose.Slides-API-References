---
title: MeasureString()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en storlek på den angivna strängen när den ritas i det angivna teckensnittet i det angivna formatet.
type: docs
weight: 521
url: /sv/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const&, System::SharedPtr<Font> const&, PointF const&, System::SharedPtr<StringFormat> const&) const metod


Returnerar en storlek på den angivna strängen när den ritas i det angivna teckensnittet i det angivna formatet.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [String](../../../system/string/) const& | Strängen vars storlek ska beräknas |
| font | [System::SharedPtr](../../../system/sharedptr/)<[Font](../../font/)> const& | Teckensnittet som används för att rita strängen |
| origin | [PointF](../../pointf/) const& | Anger platsen för strängens övre vänstra hörn |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)<[StringFormat](../../stringformat/)> const& | Anger strängformatet |

### Returvärde

Ett [SizeF](../../sizef/)-objekt som representerar storleken på strängen i de mätenheter som anges av egenskapen PageUnit för det aktuella Grapphics-objektet.

## Graphics::MeasureString(String const&, System::SharedPtr<Font> const&, int, System::SharedPtr<StringFormat> const&) const metod


Returnerar en storlek på den angivna strängen när den ritas i det angivna teckensnittet i det angivna formatet.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [String](../../../system/string/) const& | Strängen vars storlek ska beräknas |
| font | [System::SharedPtr](../../../system/sharedptr/)<[Font](../../font/)> const& | Teckensnittet som används för att rita strängen |
| width | int | Strängens maximala bredd |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)<[StringFormat](../../stringformat/)> const& | Anger strängformatet |

### Returvärde

Ett [SizeF](../../sizef/)-objekt som representerar storleken på strängen i de mätenheter som anges av egenskapen PageUnit för det aktuella Grapphics-objektet.

## Graphics::MeasureString(String const&, System::SharedPtr<Font> const&, SizeF const&, System::SharedPtr<StringFormat> const&, int&, int&) const metod


INTE IMPLEMENTERAD.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```


## Graphics::MeasureString(String const&, System::SharedPtr<Font> const&, SizeF const&, System::SharedPtr<StringFormat> const&) const metod


Returnerar en storlek på den angivna strängen när den ritas i det angivna teckensnittet i det angivna formatet.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [String](../../../system/string/) const& | Strängen vars storlek ska beräknas |
| font | [System::SharedPtr](../../../system/sharedptr/)<[Font](../../font/)> const& | Teckensnittet som används för att rita strängen |
| layoutArea | [SizeF](../../sizef/) const& | Strängens maximala layoutområde |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)<[StringFormat](../../stringformat/)> const& | Anger strängformatet |

### Returvärde

Ett [SizeF](../../sizef/)-objekt som representerar storleken på strängen i de mätenheter som anges av egenskapen PageUnit för det aktuella Grapphics-objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [SizeF](../../sizef/)
* Klass [String](../../../system/string/)
* Klass [Font](../../font/)
* Klass [PointF](../../pointf/)
* Klass [StringFormat](../../stringformat/)
* Klass [Graphics](../)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)