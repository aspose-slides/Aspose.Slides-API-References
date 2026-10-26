---
title: ILineFormatEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som innehåller effektiva linjeformateringsegenskaper.
type: docs
url: /sv/com.aspose.slides/ilineformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Immutabel objekt som innehåller effektiva linjeformateringsegenskaper.

--------------------

Detta gränssnitt används tillsammans med gränssnittet [ILineFormat](../../com.aspose.slides/ilineformat) för att returnera effektiva formateringsvärden med arv tillämpat.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returnerar fyllningsformatet för en linje. |
| [getSketchFormat()](#getSketchFormat--) | Returnerar skissformatet för en linje. |
| [getWidth()](#getWidth--) | Returnerar bredden på en linje. |
| [getDashStyle()](#getDashStyle--) | Returnerar linjens streckstil. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returnerar det anpassade streckmönstret. |
| [getCapStyle()](#getCapStyle--) | Returnerar linjens ändpunktstil. |
| [getStyle()](#getStyle--) | Returnerar linjens stil. |
| [getAlignment()](#getAlignment--) | Returnerar linjens justering. |
| [getJoinStyle()](#getJoinStyle--) | Returnerar linjernas sammanfogningsstil. |
| [getMiterLimit()](#getMiterLimit--) | Returnerar mitergränsen för en linje. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returnerar pilspetsens stil i början av en linje. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returnerar pilspetsens stil i slutet av en linje. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returnerar pilspetsens bredd i början av en linje. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returnerar pilspetsens bredd i slutet av en linje. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returnerar pilspetsens längd i början av en linje. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returnerar pilspetsens längd i slutet av en linje. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Bestämmer om de två ILineFormatEffectiveData-instanserna är lika. |
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

Returnerar linjens streckstil. Skrivskyddad [LineDashStyle](../../com.aspose.slides/linedashstyle).

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

Returnerar linjens ändpunktstil. Skrivskyddad [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Returnerar:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Returnerar linjens stil. Skrivskyddad [LineStyle](../../com.aspose.slides/linestyle).

**Returnerar:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Returnerar linjens justering. Skrivskyddad [LineAlignment](../../com.aspose.slides/linealignment).

**Returnerar:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Returnerar linjernas sammanfogningsstil. Skrivskyddad [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Returnerar:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Returnerar mitergränsen för en linje. Skrivskyddad float.

**Returnerar:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Returnerar pilspetsens stil i början av en linje. Skrivskyddad [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returnerar:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Returnerar pilspetsens stil i slutet av en linje. Skrivskyddad [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returnerar:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Returnerar pilspetsens bredd i början av en linje. Skrivskyddad [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returnerar:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Returnerar pilspetsens bredd i slutet av en linje. Skrivskyddad [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returnerar:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Returnerar pilspetsens längd i början av en linje. Skrivskyddad [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returnerar:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Returnerar pilspetsens längd i slutet av en linje. Skrivskyddad [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returnerar:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

Bestämmer om de två ILineFormatEffectiveData-instanserna är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData som ska jämföras med den aktuella ILineFormatEffectiveData. |

**Returnerar:**
boolean - **true** om den angivna ILineFormatEffectiveData är lika med den aktuella ILineFormatEffectiveData; annars **false**.