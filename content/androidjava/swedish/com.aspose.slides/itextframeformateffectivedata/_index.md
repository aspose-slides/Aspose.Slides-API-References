---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Oföränderligt objekt som innehåller effektiva formateringsegenskaper för textramen.
type: docs
url: /sv/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Oföränderligt objekt som innehåller effektiva formateringsegenskaper för textramen.

--------------------

Detta gränssnitt används tillsammans med [ITextFrameFormat](../../com.aspose.slides/itextframeformat)-gränssnittet för att returnera effektiva formateringsvärden med ärftlighet tillämpad.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Returnerar effektiv textstil. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar vänster marginal (punkter) i en TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returnerar höger marginal (punkter) i en TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returnerar övre marginal (punkter) i en TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returnerar nedre marginal (punkter) i en TextFrame. |
| [getWrapText()](#getWrapText--) | Returnerar om texten är omslagen vid TextFrames marginaler. |
| [getAnchoringType()](#getAnchoringType--) | Returnerar vertikal förankring av text i en TextFrame. |
| [getCenterText()](#getCenterText--) | Returnerar om texten ska centreras horisontellt i rutan. |
| [getTextVerticalType()](#getTextVerticalType--) | Returnerar textorientering. |
| [getAutofitType()](#getAutofitType--) | Returnerar textens autofit-läge. |
| [getColumnCount()](#getColumnCount--) | Anger antalet kolumner med text i den avgränsande rektangeln. |
| [getColumnSpacing()](#getColumnSpacing--) | Anger avståndet mellan textkolumner i textområdet (i punkter). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Returnerar effektiv textstil. Skrivskyddad [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Returnerar:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Returnerar vänster marginal (punkter) i en TextFrame. Skrivskyddad double.

**Returnerar:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Returnerar höger marginal (punkter) i en TextFrame. Skrivskyddad double.

**Returnerar:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Returnerar övre marginal (punkter) i en TextFrame. Skrivskyddad double.

**Returnerar:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Returnerar nedre marginal (punkter) i en TextFrame. Skrivskyddad double.

**Returnerar:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Returnerar om texten är omslagen vid TextFrames marginaler. Skrivskyddad boolean.

**Returnerar:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Returnerar vertikal förankring av text i en TextFrame. Skrivskyddad [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returnerar:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Returnerar om texten ska centreras horisontellt i rutan. Skrivskyddad boolean.

**Returnerar:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Returnerar textorientering. Skrivskyddad [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returnerar:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Returnerar textens autofit-läge. Skrivskyddad [TextAutofitType](../../com.aspose.slides/textautofittype).

**Returnerar:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Anger antalet kolumner med text i den avgränsande rektangeln. Skrivskyddad int.

**Returnerar:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Anger avståndet mellan textkolumner i textområdet (i punkter). Skrivskyddad float.

**Returnerar:**
float