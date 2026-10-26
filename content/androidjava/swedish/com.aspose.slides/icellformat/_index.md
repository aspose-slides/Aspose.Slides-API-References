---
title: ICellFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar formatet för en tabellcell.
type: docs
url: /sv/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Representerar formatet för en tabellcell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returnerar ett objekt med cellens fyllningsegenskaper. |
| [getBorderLeft()](#getBorderLeft--) | Returnerar ett objekt med vänsterkantens linjeegenskaper. |
| [getBorderTop()](#getBorderTop--) | Returnerar ett objekt med överkantens linjeegenskaper. |
| [getBorderRight()](#getBorderRight--) | Returnerar ett objekt med högerkantens linjeegenskaper. |
| [getBorderBottom()](#getBorderBottom--) | Returnerar ett objekt med nederkantens linjeegenskaper. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Returnerar ett objekt med diagonal linjeegenskaper från övre vänstra till nedre högra. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Returnerar ett objekt med diagonal linjeegenskaper från nedre vänstra till övre högra. |
| [getTransparency()](#getTransparency--) | Hämtar eller anger genomskinligheten för fyllningsfärgen. |
| [setTransparency(float value)](#setTransparency-float-) | Hämtar eller anger genomskinligheten för fyllningsfärgen. |
| [getEffective()](#getEffective--) | Hämtar effektiva formateringsinställningar för en tabellcell med arv och tabellstilar tillämpade. |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Returnerar ett objekt med cellens fyllningsegenskaper. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

Returnerar ett objekt med vänsterkantens linjeegenskaper. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Returnerar ett objekt med överkantens linjeegenskaper. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Returnerar ett objekt med högerkantens linjeegenskaper. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Returnerar ett objekt med nederkantens linjeegenskaper. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

Returnerar ett objekt med diagonal linjeegenskaper från övre vänstra till nedre högra. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

Returnerar ett objekt med diagonal linjeegenskaper från nedre vänstra till övre högra. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Hämtar eller anger genomskinligheten för fyllningsfärgen. Läs/skriv  float .

**Returnerar:**
float

### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Hämtar eller anger genomskinligheten för fyllningsfärgen. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

Hämtar effektiva formateringsinställningar för en tabellcell med arv och tabellstilar tillämpade.

**Returnerar:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).