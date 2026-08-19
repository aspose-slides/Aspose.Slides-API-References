---
title: IChartTextBlockFormat
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt opmaak-eigenschappen voor chart-textelementen.
type: docs
url: /nl/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Vertegenwoordigt opmaak-eigenschappen voor chart-tekst elementen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Geeft de verticale ankertekst in een TextFrame terug of stelt deze in. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Geeft de verticale ankertekst in een TextFrame terug of stelt deze in. |
| [getCenterText()](#getCenterText--) | Indien NullableBool.True dan moet de tekst horizontaal gecentreerd worden in de doos. |
| [setCenterText(byte value)](#setCenterText-byte-) | Indien NullableBool.True dan moet de tekst horizontaal gecentreerd worden in de doos. |
| [getTextVerticalType()](#getTextVerticalType--) | Bepaalt de tekstoriëntatie. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bepaalt de tekstoriëntatie. |
| [getMarginLeft()](#getMarginLeft--) | Geeft de linkermarge (punten) in een TextFrame terug of stelt deze in. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Geeft de linkermarge (punten) in een TextFrame terug of stelt deze in. |
| [getMarginRight()](#getMarginRight--) | Geeft de rechtermarge (punten) in een TextFrame terug of stelt deze in. |
| [setMarginRight(double value)](#setMarginRight-double-) | Geeft de rechtermarge (punten) in een TextFrame terug of stelt deze in. |
| [getMarginTop()](#getMarginTop--) | Geeft de bovenmarge (punten) in een TextFrame terug of stelt deze in. |
| [setMarginTop(double value)](#setMarginTop-double-) | Geeft de bovenmarge (punten) in een TextFrame terug of stelt deze in. |
| [getMarginBottom()](#getMarginBottom--) | Geeft de ondermarge (punten) in een TextFrame terug of stelt deze in. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Geeft de ondermarge (punten) in een TextFrame terug of stelt deze in. |
| [getWrapText()](#getWrapText--) | Waar als tekst wordt afgebroken bij de marges van de TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Waar als tekst wordt afgebroken bij de marges van de TextFrame. |
| [getAutofitType()](#getAutofitType--) | Geeft de autofit-modus van de tekst terug of stelt deze in. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Geeft de autofit-modus van de tekst terug of stelt deze in. |
| [getRotationAngle()](#getRotationAngle--) | Specificeert de aangepaste rotatie die op de tekst binnen de begrenzingsbox wordt toegepast. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specificeert de aangepaste rotatie die op de tekst binnen de begrenzingsbox wordt toegepast. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Geeft de verticale ankertekst in een TextFrame terug of stelt deze in. Lezen/schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retour:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


Geeft de verticale ankertekst in een TextFrame terug of stelt deze in. Lezen/schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


Indien NullableBool.True dan moet de tekst horizontaal gecentreerd worden in de doos. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


Indien NullableBool.True dan moet de tekst horizontaal gecentreerd worden in de doos. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Bepaalt de tekstoriëntatie. De resulterende visuele tekstrrotatie wordt samengevat uit deze eigenschap en de aangepaste hoek in eigenschap RotationAngle. Lezen/schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retour:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Bepaalt de tekstoriëntatie. De resulterende visuele tekstrrotatie wordt samengevat uit deze eigenschap en de aangepaste hoek in eigenschap RotationAngle. Lezen/schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Geeft de linkermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven double.

**Retour:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Geeft de linkermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Geeft de rechtermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven double.

**Retour:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Geeft de rechtermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Geeft de bovenmarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven double.

**Retour:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Geeft de bovenmarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Geeft de ondermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven double.

**Retour:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Geeft de ondermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


Waar als tekst wordt afgebroken bij de marges van de TextFrame. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2007/2013). Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


Waar als tekst wordt afgebroken bij de marges van de TextFrame. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2007/2013). Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Geeft de autofit-modus van de tekst terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retour:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


Geeft de autofit-modus van de tekst terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op de volgende chart-onderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


Specificeert de aangepaste rotatie die op de tekst binnen de begrenzingsbox wordt toegepast. Indien niet gespecificeerd, wordt de rotatie van de bijbehorende vorm gebruikt. Indien gespecificeerd, wordt deze onafhankelijk van de vorm toegepast. Dat wil zeggen dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De geresulteerde visuele tekstrrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in eigenschap TextVerticalType. Lezen/schrijven float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Retour:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Specificeert de aangepaste rotatie die op de tekst binnen de begrenzingsbox wordt toegepast. Indien niet gespecificeerd, wordt de rotatie van de bijbehorende vorm gebruikt. Indien gespecificeerd, wordt deze onafhankelijk van de vorm toegepast. Dat wil zeggen dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De geresulteerde visuele tekstrrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in eigenschap TextVerticalType. Lezen/schrijven float.

--------------------

> ```
> Overweeg het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft gekregen. 
>  In aanvulling hierop heeft het tekstlichaam zelf een rotatie van -90 graden tegen de klok in gekregen. 
>  Dan zou de resulterende vorm lijken te
>  worden gedraaid, maar de tekst erin zou lijken alsof deze niet gedraaid is.
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |