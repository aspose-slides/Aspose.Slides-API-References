---
title: ILineFormatEffectiveData
second_title: Aspose.Slides Androidra vonatkozó Java API referenciája
description: Módosíthatatlan objektum, amely hatékony vonalformázási tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/ilineformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Módosíthatatlan objektum, amely hatékony vonalformázási tulajdonságokat tartalmaz.

--------------------

Ez az interfész a [ILineFormat](../../com.aspose.slides/ilineformat) interfésszel együtt használható, hogy visszaadja az öröklődés alkalmazásával a hatékony formázási értékeket.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Visszaadja a vonal kitöltési formátumát. |
| [getSketchFormat()](#getSketchFormat--) | Visszaadja a vonal vázlat formátumát. |
| [getWidth()](#getWidth--) | Visszaadja a vonal szélességét. |
| [getDashStyle()](#getDashStyle--) | Visszaadja a vonal vonalas stílusát. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Visszaadja az egyéni vonalas mintát. |
| [getCapStyle()](#getCapStyle--) | Visszaadja a vonal végpont stílusát. |
| [getStyle()](#getStyle--) | Visszaadja a vonal stílusát. |
| [getAlignment()](#getAlignment--) | Visszaadja a vonal igazítását. |
| [getJoinStyle()](#getJoinStyle--) | Visszaadja a vonalak csatlakozási stílusát. |
| [getMiterLimit()](#getMiterLimit--) | Visszaadja a vonal átfedéskorlátját. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Visszaadja a vonal elején lévő nyílhegy stílusát. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Visszaadja a vonal végén lévő nyílhegy stílusát. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Visszaadja a vonal elején lévő nyílhegy szélességét. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Visszaadja a vonal végén lévő nyílhegy szélességét. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Víszaadja a vonal elején lévő nyílhegy hosszát. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Visszaadja a vonal végén lévő nyílhegy hosszát. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Megállapítja, hogy a két ILineFormatEffectiveData példány egyenlő-e. |

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

Visszaadja a vonal kitöltési formátumát. Csak olvasható [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Visszatérési érték:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

Visszaadja a vonal vázlat formátumát. Csak olvasható [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Visszatérési érték:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Visszaadja a vonal szélességét. Csak olvasható double.

**Visszatérési érték:**
double

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Visszaadja a vonal vonalas stílusát. Csak olvasható [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Visszatérési érték:**
byte

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Visszaadja az egyéni vonalas mintát. Csak olvasható float[].

**Visszatérési érték:**
float[]

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Visszaadja a vonal végpont stílusát. Csak olvasható [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Visszatérési érték:**
byte

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Visszaadja a vonal stílusát. Csak olvasható [LineStyle](../../com.aspose.slides/linestyle).

**Visszatérési érték:**
byte

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Visszaadja a vonal igazítását. Csak olvasható [LineAlignment](../../com.aspose.slides/linealignment).

**Visszatérési érték:**
byte

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Visszaadja a vonalak csatlakozási stílusát. Csak olvasható [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Visszatérési érték:**
byte

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Visszaadja a vonal átfedéskorlátját. Csak olvasható float.

**Visszatérési érték:**
float

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Visszaadja a vonal elején lévő nyílhegy stílusát. Csak olvasható [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Visszatérési érték:**
byte

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Visszaadja a vonal végén lévő nyílhegy stílusát. Csak olvasható [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Visszatérési érték:**
byte

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Visszaadja a vonal elején lévő nyílhegy szélességét. Csak olvasható [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Visszatérési érték:**
byte

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Visszaadja a vonal végén lévő nyílhegy szélességét. Csak olvasható [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Visszatérési érték:**
byte

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Visszaadja a vonal elején lévő nyílhegy hosszát. Csak olvasható [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Visszatérési érték:**
byte

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Visszaadja a vonal végén lévő nyílhegy hosszát. Csak olvasható [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Visszatérési érték:**
byte

### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

Megállapítja, hogy a két ILineFormatEffectiveData példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | Az ILineFormatEffectiveData, amelyet az aktuális ILineFormatEffectiveData-vel hasonlítunk össze. |

**Visszatérési érték:**
boolean - **true** ha a megadott ILineFormatEffectiveData egyenlő az aktuális ILineFormatEffectiveData-val; egyébként, **false**.