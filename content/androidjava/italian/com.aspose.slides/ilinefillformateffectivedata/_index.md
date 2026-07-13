---
title: ILineFillFormatEffectiveData
second_title: Riferimento API Java per Aspose.Slides per Android
description: Oggetto immutabile che contiene le proprietà di riempimento delle linee efficaci.
type: docs
url: /it/com.aspose.slides/ilinefillformateffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Oggetto immutabile che contiene le proprietà di riempimento delle linee efficaci.

--------------------

Questa interfaccia è usata come parte di [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillType()](#getFillType--) | Restituisce il tipo di riempimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Restituisce il colore di un riempimento solido. |
| [getGradientFormat()](#getGradientFormat--) | Restituisce il formato del riempimento gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Restituisce il formato del riempimento a modello. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se il riempimento deve essere ruotato con una forma. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Restituisce il tipo di riempimento. Sola lettura [FillType](../../com.aspose.slides/filltype).

**Restituisce:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

Restituisce il colore di un riempimento solido. Sola lettura java.lang.Integer.

**Restituisce:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

Restituisce il formato del riempimento gradiente. Sola lettura [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Restituisce:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

Restituisce il formato del riempimento a modello. Sola lettura [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Restituisce:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Determina se il riempimento deve essere ruotato con una forma. Sola lettura boolean.

**Restituisce:**
boolean