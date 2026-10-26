---
title: ILineFormat
second_title: Aspose.Slides pro Android přes Java API Reference
description: Representuje formát řádku.
type: docs
url: /cs/com.aspose.slides/ilineformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Representuje formát řádku.
## Metody

| Metoda | Popis |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Vrací true, pokud není formát řádku definován (právě po vytvoření, výchozí). |
| [getFillFormat()](#getFillFormat--) | Vrací výplňový formát řádku. |
| [getSketchFormat()](#getSketchFormat--) | Vrací skicovací formát řádku. |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku řádku. |
| [setWidth(double value)](#setWidth-double-) | Vrací nebo nastavuje šířku řádku. |
| [getDashStyle()](#getDashStyle--) | Vrací nebo nastavuje styl čáry s čárkováním. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Vrací nebo nastavuje styl čáry s čárkováním. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Vrací nebo nastavuje vlastní vzor čáry. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Vrací nebo nastavuje vlastní vzor čáry. |
| [getCapStyle()](#getCapStyle--) | Vrací nebo nastavuje styl zakončení řádku. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Vrací nebo nastavuje styl zakončení řádku. |
| [getStyle()](#getStyle--) | Vrací nebo nastavuje styl řádku. |
| [setStyle(byte value)](#setStyle-byte-) | Vrací nebo nastavuje styl řádku. |
| [getAlignment()](#getAlignment--) | Vrací nebo nastavuje zarovnání řádku. |
| [setAlignment(byte value)](#setAlignment-byte-) | Vrací nebo nastavuje zarovnání řádku. |
| [getJoinStyle()](#getJoinStyle--) | Vrací nebo nastavuje styl spojení řádek. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Vrací nebo nastavuje styl spojení řádek. |
| [getMiterLimit()](#getMiterLimit--) | Vrací nebo nastavuje limit ostří (miter) řádku. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Vrací nebo nastavuje limit ostří (miter) řádku. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Vrací nebo nastavuje styl šipky na začátku řádku. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Vrací nebo nastavuje styl šipky na začátku řádku. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Vrací nebo nastavuje styl šipky na konci řádku. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Vrací nebo nastavuje styl šipky na konci řádku. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Vrací nebo nastavuje šířku šipky na začátku řádku. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Vrací nebo nastavuje šířku šipky na začátku řádku. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Vrací nebo nastavuje šířku šipky na konci řádku. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Vrací nebo nastavuje šířku šipky na konci řádku. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Vrací nebo nastavuje délku šipky na začátku řádku. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Vrací nebo nastavuje délku šipky na začátku řádku. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Vrací nebo nastavuje délku šipky na konci řádku. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Vrací nebo nastavuje délku šipky na konci řádku. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Určuje, zda jsou dvě instance LineFormat rovny. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování řádku s aplikovaným děděním. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Vrací true, pokud není formát řádku definován (právě po vytvoření, výchozí). Pouze pro čtení boolean.

**Vrací:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Vrací výplňový formát řádku. Pouze pro čtení [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Vrací:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Vrací skicovací formát řádku. Pouze pro čtení [ISketchFormat](../../com.aspose.slides/isketchformat).

**Vrací:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Vrací nebo nastavuje šířku řádku. Čtení/Zápis double.

**Vrací:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Vrací nebo nastavuje šířku řádku. Čtení/Zápis double.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Vrací nebo nastavuje styl čáry s čárkováním. Čtení/Zápis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Vrací:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Vrací nebo nastavuje styl čáry s čárkováním. Čtení/Zápis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Vrací nebo nastavuje vlastní vzor čáry. Čtení/Zápis float[].

**Vrací:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Vrací nebo nastavuje vlastní vzor čáry. Čtení/Zápis float[].

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Vrací nebo nastavuje styl zakončení řádku. Čtení/Zápis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Vrací:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Vrací nebo nastavuje styl zakončení řádku. Čtení/Zápis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Vrací nebo nastavuje styl řádku. Čtení/Zápis [LineStyle](../../com.aspose.slides/linestyle).

**Vrací:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Vrací nebo nastavuje styl řádku. Čtení/Zápis [LineStyle](../../com.aspose.slides/linestyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Vrací nebo nastavuje zarovnání řádku. Čtení/Zápis [LineAlignment](../../com.aspose.slides/linealignment).

**Vrací:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Vrací nebo nastavuje zarovnání řádku. Čtení/Zápis [LineAlignment](../../com.aspose.slides/linealignment).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Vrací nebo nastavuje styl spojení řádek. Čtení/Zápis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Vrací:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Vrací nebo nastavuje styl spojení řádek. Čtení/Zápis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Vrací nebo nastavuje limit ostří (miter) řádku. Čtení/Zápis float.

**Vrací:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Vrací nebo nastavuje limit ostří (miter) řádku. Čtení/Zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Vrací nebo nastavuje styl šipky na začátku řádku. Čtení/Zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Vrací nebo nastavuje styl šipky na začátku řádku. Čtení/Zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Vrací nebo nastavuje styl šipky na konci řádku. Čtení/Zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Vrací:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Vrací nebo nastavuje styl šipky na konci řádku. Čtení/Zápis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Vrací nebo nastavuje šířku šipky na začátku řádku. Čtení/Zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Vrací nebo nastavuje šířku šipky na začátku řádku. Čtení/Zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Vrací nebo nastavuje šířku šipky na konci řádku. Čtení/Zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Vrací:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Vrací nebo nastavuje šířku šipky na konci řádku. Čtení/Zápis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Vrací nebo nastavuje délku šipky na začátku řádku. Čtení/Zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Vrací nebo nastavuje délku šipky na začátku řádku. Čtení/Zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Vrací nebo nastavuje délku šipky na konci řádku. Čtení/Zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Vrací:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Vrací nebo nastavuje délku šipky na konci řádku. Čtení/Zápis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Určuje, zda jsou dvě instance LineFormat rovny.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat, se kterým se porovnává aktuální LineFormat. |

**Vrací:**
boolean - **true** pokud je zadaný LineFormat roven aktuálnímu LineFormat; jinak **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Získá efektivní data formátování řádku s aplikovaným děděním.

**Vrací:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).