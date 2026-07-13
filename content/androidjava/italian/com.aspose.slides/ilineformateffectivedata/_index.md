---
title: ILineFormatEffectiveData
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Oggetto immutabile che contiene le proprietà di formattazione della linea efficaci.
type: docs
url: /it/com.aspose.slides/ilineformateffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Oggetto immutabile che contiene le proprietà di formattazione della linea efficaci.

--------------------

Questa interfaccia è usata insieme all'interfaccia [ILineFormat](../../com.aspose.slides/ilineformat) per restituire i valori di formattazione efficaci con l'ereditarietà applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Restituisce il formato di riempimento di una linea. |
| [getSketchFormat()](#getSketchFormat--) | Restituisce il formato di schizzo di una linea. |
| [getWidth()](#getWidth--) | Restituisce la larghezza di una linea. |
| [getDashStyle()](#getDashStyle--) | Restituisce lo stile di tratteggio della linea. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Restituisce il modello di tratteggio personalizzato. |
| [getCapStyle()](#getCapStyle--) | Restituisce lo stile di estremità della linea. |
| [getStyle()](#getStyle--) | Restituisce lo stile della linea. |
| [getAlignment()](#getAlignment--) | Restituisce l'allineamento della linea. |
| [getJoinStyle()](#getJoinStyle--) | Restituisce lo stile di giunzione delle linee. |
| [getMiterLimit()](#getMiterLimit--) | Restituisce il limite di mordente di una linea. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Restituisce lo stile della punta di freccia all'inizio di una linea. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Restituisce lo stile della punta di freccia alla fine di una linea. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Restituisce la larghezza della punta di freccia all'inizio di una linea. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Restituisce la larghezza della punta di freccia alla fine di una linea. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Restituisce la lunghezza della punta di freccia all'inizio di una linea. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Restituisce la lunghezza della punta di freccia alla fine di una linea. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Determina se le due istanze ILineFormatEffectiveData sono uguali. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Restituisce il formato di riempimento di una linea. Sola lettura [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Restituisce:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Restituisce il formato di schizzo di una linea. Sola lettura [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Restituisce:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Restituisce la larghezza di una linea. Sola lettura double.

**Restituisce:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Restituisce lo stile di tratteggio della linea. Sola lettura [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Restituisce:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Restituisce il modello di tratteggio personalizzato. Sola lettura float[].

**Restituisce:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Restituisce lo stile di estremità della linea. Sola lettura [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Restituisce:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Restituisce lo stile della linea. Sola lettura [LineStyle](../../com.aspose.slides/linestyle).

**Restituisce:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Restituisce l'allineamento della linea. Sola lettura [LineAlignment](../../com.aspose.slides/linealignment).

**Restituisce:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Restituisce lo stile di giunzione delle linee. Sola lettura [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Restituisce:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Restituisce il limite di mordente di una linea. Sola lettura float.

**Restituisce:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Restituisce lo stile della punta di freccia all'inizio di una linea. Sola lettura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Restituisce:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Restituisce lo stile della punta di freccia alla fine di una linea. Sola lettura [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Restituisce:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Restituisce la larghezza della punta di freccia all'inizio di una linea. Sola lettura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Restituisce:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Restituisce la larghezza della punta di freccia alla fine di una linea. Sola lettura [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Restituisce:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Restituisce la lunghezza della punta di freccia all'inizio di una linea. Sola lettura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Restituisce:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Restituisce la lunghezza della punta di freccia alla fine di una linea. Sola lettura [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Restituisce:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Determina se le due istanze ILineFormatEffectiveData sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | L'ILineFormatEffectiveData da confrontare con l'ILineFormatEffectiveData corrente. |

**Restituisce:**
boolean - **true** se l'ILineFormatEffectiveData specificato è uguale all'ILineFormatEffectiveData corrente; altrimenti, **false**.