---
title: IFillFormatEffectiveData
second_title: Aspose.Slides per Android via Riferimento API Java
description: Oggetto immutabile che contiene le proprietà di formattazione del riempimento effettive.
type: docs
url: /it/com.aspose.slides/ifillformateffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Oggetto immutabile che contiene le proprietà di formattazione del riempimento effettive.

--------------------

Questa interfaccia è utilizzata insieme all'interfaccia [IFillFormat](../../com.aspose.slides/ifillformat) per restituire i valori di formattazione effettivi con l'ereditarietà applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillType()](#getFillType--) | Restituisce il tipo di riempimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Restituisce il colore di riempimento. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Ottiene il colore di riempimento definito da uno schema di colore. |
| [getGradientFormat()](#getGradientFormat--) | Restituisce il formato di riempimento a gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Restituisce il formato di riempimento a trama. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Restituisce il formato di riempimento immagine. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se il riempimento deve essere ruotato con la forma. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Restituisce il tipo di riempimento. Solo lettura [FillType](../../com.aspose.slides/filltype).

**Restituisce:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Restituisce il colore di riempimento. Solo lettura java.lang.Integer.

**Restituisce:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Ottiene il colore di riempimento definito da uno schema di colore. Il valore [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) indica che il SolidFillColor (\#getSolidFillColor.getSolidFillColor) non è un colore di schema. Solo lettura [SchemeColor](../../com.aspose.slides/schemecolor).

**Restituisce:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Restituisce il formato di riempimento a gradiente. Solo lettura [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Restituisce:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Restituisce il formato di riempimento a trama. Solo lettura [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Restituisce:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Restituisce il formato di riempimento immagine. Solo lettura [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Restituisce:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Determina se il riempimento deve essere ruotato con la forma. Solo lettura boolean.

**Restituisce:**
boolean