---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Geeft de opmaak-eigenschappen voor tekstelementen van een diagram weer.
type: docs
url: /nl/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Geeft de opmaak-eigenschappen voor tekstelementen van een diagram weer.
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Geeft de verticale verankeringstekst in een TextFrame terug of stelt deze in. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Geeft de verticale verankeringstekst in een TextFrame terug of stelt deze in. |
| [getCenterText()](#getCenterText--) | Als NullableBool.True is, moet de tekst horizontaal gecentreerd worden in het vak. |
| [setCenterText(byte value)](#setCenterText-byte-) | Als NullableBool.True is, moet de tekst horizontaal gecentreerd worden in het vak. |
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
| [getWrapText()](#getWrapText--) | Waar als de tekst wordt afgebroken bij de marges van de TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Waar als de tekst wordt afgebroken bij de marges van de TextFrame. |
| [getAutofitType()](#getAutofitType--) | Geeft de autofit-modus van de tekst terug of stelt deze in. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Geeft de autofit-modus van de tekst terug of stelt deze in. |
| [getRotationAngle()](#getRotationAngle--) | Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende rechthoek. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende rechthoek. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Geeft de verticale verankeringstekst in een TextFrame terug of stelt deze in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retour:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Geeft de verticale verankeringstekst in een TextFrame terug of stelt deze in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Als NullableBool.True is, moet de tekst horizontaal gecentreerd worden in het vak. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Als NullableBool.True is, moet de tekst horizontaal gecentreerd worden in het vak. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Bepaalt de tekstoriëntatie. De resulterende waarde van visuele tekstraprotatie, samengevat uit deze eigenschap en de aangepaste hoek in de eigenschap RotationAngle. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retour:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Bepaalt de tekstoriëntatie. De resulterende waarde van visuele tekstraprotatie, samengevat uit deze eigenschap en de aangepaste hoek in de eigenschap RotationAngle. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Geeft de linkermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven double.

**Retour:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Geeft de linkermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Geeft de rechtermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven double.

**Retour:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Geeft de rechtermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Geeft de bovenmarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven double.

**Retour:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Geeft de bovenmarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Geeft de ondermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven double.

**Retour:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Geeft de ondermarge (punten) in een TextFrame terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Waar als de tekst wordt afgebroken bij de marges van de TextFrame. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2007/2013). Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Waar als de tekst wordt afgebroken bij de marges van de TextFrame. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2007/2013). Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Geeft de autofit-modus van de tekst terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retour:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Geeft de autofit-modus van de tekst terug of stelt deze in. Het wijzigen van deze eigenschap kan alleen invloed hebben op deze diagramonderdelen: DataLabel en DataLabelFormat (volledige ondersteuning in PowerPoint 2013; in PowerPoint 2007 heeft het geen effect op weergave). Lezen/Schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende rechthoek. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstraprotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lezen/Schrijven float.

--------------------

> ```
> Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft toegepast. 
>  Daarnaast heeft het tekstgedeelte zelf een rotatie van -90 graden 
>  tegen de klok in toegepast. Dan zou de resulterende vorm lijken te
>  gedraaid zijn, maar de tekst erin zou lijken alsof deze niet gedraaid is.
> ```


**Retour:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende rechthoek. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstraprotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lezen/Schrijven float.

--------------------

> ```
> Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft toegepast. 
>  Daarnaast heeft het tekstgedeelte zelf een rotatie van -90 graden 
>  tegen de klok in toegepast. Dan zou de resulterende vorm lijken te
>  gedraaid zijn, maar de tekst erin zou lijken alsof deze niet gedraaid is.
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |