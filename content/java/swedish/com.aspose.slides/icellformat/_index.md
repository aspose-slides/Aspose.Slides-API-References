---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
description: Represents format of a table cell.
type: docs
url: /sv/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Representerar formatet för en tabellcell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returnerar ett cellfyllningsegenskapsobjekt. |
| [getBorderLeft()](#getBorderLeft--) | Returnerar ett objekt med egenskaper för vänster kantlinje. |
| [getBorderTop()](#getBorderTop--) | Returnerar ett objekt med egenskaper för överkantlinje. |
| [getBorderRight()](#getBorderRight--) | Returnerar ett objekt med egenskaper för höger kantlinje. |
| [getBorderBottom()](#getBorderBottom--) | Returnerar ett objekt med egenskaper för nederkantlinje. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Returnerar ett objekt med egenskaper för diagonal linje från övre vänster till nedre höger. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Returnerar ett objekt med egenskaper för diagonal linje från nedre vänster till övre höger. |
| [getTransparency()](#getTransparency--) | Hämtar eller anger transparensen för fyllningsfärgen. |
| [setTransparency(float value)](#setTransparency-float-) | Hämtar eller anger transparensen för fyllningsfärgen. |
| [getEffective()](#getEffective--) | Hämtar effektiva tabellcellsformateringsattribut med arv och tabellstilar tillämpade. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Returnerar ett cellfyllningsegenskapsobjekt. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

Returnerar ett objekt med egenskaper för vänster kantlinje. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Returnerar ett objekt med egenskaper för överkantlinje. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Returnerar ett objekt med egenskaper för höger kantlinje. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Returnerar ett objekt med egenskaper för nederkantlinje. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

Returnerar ett objekt med egenskaper för diagonal linje från övre vänster till nedre höger. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

Returnerar ett objekt med egenskaper för diagonal linje från nedre vänster till övre högra. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Hämtar eller anger transparensen för fyllningsfärgen. Läs/skriv  float .

**Returnerar:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Hämtar eller anger transparensen för fyllningsfärgen. Läs/skriv  float .

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

Hämtar effektiva tabellcellsformateringsattribut med arv och tabellstilar tillämpade.

**Returnerar:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - En [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).