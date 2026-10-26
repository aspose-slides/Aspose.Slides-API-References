---
title: ILineFormatEffectiveData
second_title: Aspose.Slides pro Java - referenční API
description: Neměnný objekt, který obsahuje efektivní vlastnosti formátování čáry.
type: docs
url: /cs/com.aspose.slides/ilineformateffectivedata/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Neměnný objekt, který obsahuje efektivní vlastnosti formátování čáry.

--------------------

Toto rozhraní se používá společně s rozhraním [ILineFormat](../../com.aspose.slides/ilineformat) k vrácení efektivních hodnot formátování s aplikovaným děděním.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Vrací výplňový formát čáry. |
| [getSketchFormat()](#getSketchFormat--) | Vrací skicovací formát čáry. |
| [getWidth()](#getWidth--) | Vrací šířku čáry. |
| [getDashStyle()](#getDashStyle--) | Vrací styl čárkování čáry. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Vrací vlastní vzor čárkování. |
| [getCapStyle()](#getCapStyle--) | Vrací styl konce čáry. |
| [getStyle()](#getStyle--) | Vrací styl čáry. |
| [getAlignment()](#getAlignment--) | Vrací zarovnání čáry. |
| [getJoinStyle()](#getJoinStyle--) | Vrací styl spojení čar. |
| [getMiterLimit()](#getMiterLimit--) | Vrací limit zkosení čáry. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Vrací styl šípky na začátku čáry. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Vrací styl šípky na konci čáry. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Vrací šířku šípky na začátku čáry. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Vrací šířku šípky na konci čáry. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Vrací délku šípky na začátku čáry. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Vrací délku šípky na konci čáry. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Určuje, zda jsou dvě instance ILineFormatEffectiveData rovny. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Vrací výplňový formát čáry. Pouze ke čtení [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Vrací:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Vrací skicovací formát čáry. Pouze ke čtení [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Vrací:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Vrací šířku čáry. Pouze ke čtení double.

**Vrací:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Vrací styl čárkování čáry. Pouze ke čtení [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Vrací:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Vrací vlastní vzor čárkování. Pouze ke čtení float[].

**Vrací:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Vrací styl konce čáry. Pouze ke čtení [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Vrací:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Vrací styl čáry. Pouze ke čtení [LineStyle](../../com.aspose.slides/linestyle).

**Vrací:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Vrací zarovnání čáry. Pouze ke čtení [LineAlignment](../../com.aspose.slides/linealignment).

**Vrací:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Vrací styl spojení čar. Pouze ke čtení [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Vrací:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Vrací limit zkosení čáry. Pouze ke čtení float.

**Vrací:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Vrací styl šípky na začátku čáry. Pouze ke čtení [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Vrací styl šípky na konci čáry. Pouze ke čtení [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Vrací šířku šípky na začátku čáry. Pouze ke čtení [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Vrací šířku šípky na konci čáry. Pouze ke čtení [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Vrací délku šípky na začátku čáry. Pouze ke čtení [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Vrací délku šípky na konci čáry. Pouze ke čtení [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Určuje, zda jsou dvě instance ILineFormatEffectiveData rovny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | ILineFormatEffectiveData, který se porovnává s aktuálním ILineFormatEffectiveData. |

**Vrací:**
boolean - **true** pokud je zadaný ILineFormatEffectiveData roven aktuálnímu ILineFormatEffectiveData; jinak **false**.