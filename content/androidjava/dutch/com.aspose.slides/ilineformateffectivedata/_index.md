---
title: ILineFormatEffectiveData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Onveranderlijk object dat effectieve regelopmaak-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ilineformateffectivedata/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Onveranderlijk object dat effectieve regelopmaak-eigenschappen bevat.

--------------------

Deze interface wordt samen met de [ILineFormat](../../com.aspose.slides/ilineformat) interface gebruikt om effectieve opmaakwaarden met toegepaste overerving te retourneren.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Retourneert het vullingsformaat van een lijn. |
| [getSketchFormat()](#getSketchFormat--) | Retourneert het schetsformaat van een lijn. |
| [getWidth()](#getWidth--) | Retourneert de breedte van een lijn. |
| [getDashStyle()](#getDashStyle--) | Retourneert de streepjesstijl van een lijn. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Retourneert het aangepaste streepjespatroon. |
| [getCapStyle()](#getCapStyle--) | Retourneert de eindstijl van een lijn. |
| [getStyle()](#getStyle--) | Retourneert de lijnstijl. |
| [getAlignment()](#getAlignment--) | Retourneert de uitlijning van de lijn. |
| [getJoinStyle()](#getJoinStyle--) | Retourneert de verbindingsstijl van de lijnen. |
| [getMiterLimit()](#getMiterLimit--) | Retourneert de versteklimiet van een lijn. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Retourneert de pijlhoofdstijl aan het begin van een lijn. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Retourneert de pijlhoofdstijl aan het einde van een lijn. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Retourneert de pijlhoofdbreedte aan het begin van een lijn. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Retourneert de pijlhoofdbreedte aan het einde van een lijn. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Retourneert de pijlhoofd lengte aan het begin van een lijn. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Retourneert de pijlhoofd lengte aan het einde van een lijn. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Bepaalt of de twee ILineFormatEffectiveData-instanties gelijk zijn. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Retourneert het vullingsformaat van een lijn. Alleen-lezen [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Retour:**  
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Retourneert het schetsformaat van een lijn. Alleen-lezen [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Retour:**  
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Retourneert de breedte van een lijn. Alleen-lezen double.

**Retour:**  
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Retourneert de streepjesstijl van een lijn. Alleen-lezen [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Retour:**  
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Retourneert het aangepaste streepjespatroon. Alleen-lezen float[].

**Retour:**  
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Retourneert de eindstijl van een lijn. Alleen-lezen [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Retour:**  
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Retourneert de lijnstijl. Alleen-lezen [LineStyle](../../com.aspose.slides/linestyle).

**Retour:**  
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Retourneert de uitlijning van de lijn. Alleen-lezen [LineAlignment](../../com.aspose.slides/linealignment).

**Retour:**  
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Retourneert de verbindingsstijl van de lijnen. Alleen-lezen [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Retour:**  
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Retourneert de versteklimiet van een lijn. Alleen-lezen float.

**Retour:**  
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Retourneert de pijlhoofdstijl aan het begin van een lijn. Alleen-lezen [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retour:**  
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Retourneert de pijlhoofdstijl aan het einde van een lijn. Alleen-lezen [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retour:**  
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Retourneert de pijlhoofdbreedte aan het begin van een lijn. Alleen-lezen [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retour:**  
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Retourneert de pijlhoofdbreedte aan het einde van een lijn. Alleen-lezen [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retour:**  
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Retourneert de pijlhoofd lengte aan het begin van een lijn. Alleen-lezen [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retour:**  
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Retourneert de pijlhoofd lengte aan het einde van een lijn. Alleen-lezen [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retour:**  
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Bepaalt of de twee ILineFormatEffectiveData-instanties gelijk zijn.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | De ILineFormatEffectiveData om te vergelijken met de huidige ILineFormatEffectiveData. |

**Retour:**  
boolean - **true** als de opgegeven ILineFormatEffectiveData gelijk is aan de huidige ILineFormatEffectiveData; anders, **false**.