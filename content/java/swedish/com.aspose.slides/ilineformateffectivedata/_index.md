---
title: ILineFormatEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som innehåller effektiva linjeformateringsegenskaper.
type: docs
url: /sv/com.aspose.slides/ilineformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Oföränderligt objekt som innehåller effektiva linjeformateringsegenskaper.

--------------------

Detta gränssnitt används tillsammans med [ILineFormat](../../com.aspose.slides/ilineformat)-gränssnittet för att returnera effektiva formateringsvärden med arv tillämpat.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returnerar fyllningsformatet för en linje. |
| [getSketchFormat()](#getSketchFormat--) | Returnerar skissformatet för en linje. |
| [getWidth()](#getWidth--) | Returnerar bredden på en linje. |
| [getDashStyle()](#getDashStyle--) | Returnerar streckstilen för en linje. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returnerar det anpassade streckmönstret. |
| [getCapStyle()](#getCapStyle--) | Returnerar toppstilen för en linje. |
| [getStyle()](#getStyle--) | Returnerar linjestilen. |
| [getAlignment()](#getAlignment--) | Returnerar linjejusteringen. |
| [getJoinStyle()](#getJoinStyle--) | Returnerar sammanslagningsstilen för linjer. |
| [getMiterLimit()](#getMiterLimit--) | Returnerar geringsgränsen för en linje. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returnerar pilhuvudstilen i början av en linje. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returnerar pilhuvudstilen i slutet av en linje. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returnerar pilhuvudets bredd i början av en linje. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returnerar pilhuvudets bredd i slutet av en linje. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returnerar pilhuvudets längd i början av en linje. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returnerar pilhuvudets längd i slutet av en linje. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Avgör om de två ILineFormatEffectiveData-instanserna är lika. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Returnerar fyllningsformatet för en linje. Skrivskyddad [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Returnerar:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Returnerar skissformatet för en linje. Skrivskyddad [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Returnerar:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Returnerar bredden på en linje. Skrivskyddad double.

**Returnerar:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Returnerar streckstilen för en linje. Skrivskyddad [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Returnerar:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Returnerar det anpassade streckmönstret. Skrivskyddad float[].

**Returnerar:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Returnerar toppstilen för en linje. Skrivskyddad [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Returnerar:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Returnerar linjestilen. Skrivskyddad [LineStyle](../../com.aspose.slides/linestyle).

**Returnerar:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Returnerar linjejusteringen. Skrivskyddad [LineAlignment](../../com.aspose.slides/linealignment).

**Returnerar:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Returnerar sammanslagningsstilen för linjer. Skrivskyddad [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Returnerar:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Returnerar geringsgränsen för en linje. Skrivskyddad float.

**Returnerar:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Returnerar pilhuvudstilen i början av en linje. Skrivskyddad [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returnerar:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Returnerar pilhuvudstilen i slutet av en linje. Skrivskyddad [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returnerar:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Returnerar pilhuvudets bredd i början av en linje. Skrivskyddad [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returnerar:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Returnerar pilhuvudets bredd i slutet av en linje. Skrivskyddad [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returnerar:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Returnerar pilhuvudets längd i början av en linje. Skrivskyddad [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returnerar:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Returnerar pilhuvudets längd i slutet av en linje. Skrivskyddad [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returnerar:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Avgör om de två ILineFormatEffectiveData-instanserna är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData som ska jämföras med den aktuella ILineFormatEffectiveData. |

**Returnerar:**
boolean - **true** if the specified ILineFormatEffectiveData is equal to the current ILineFormatEffectiveData; otherwise, **false**.