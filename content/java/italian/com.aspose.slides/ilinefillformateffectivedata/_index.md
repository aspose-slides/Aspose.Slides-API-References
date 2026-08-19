---
title: ILineFillFormatEffectiveData
second_title: Riferimento API di Aspose.Slides per Java
description: Oggetto immutabile che contiene le proprietà di riempimento di linea efficaci.
type: docs
url: /it/com.aspose.slides/ilinefillformateffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Oggetto immutabile che contiene le proprietà di riempimento di linea efficaci.

--------------------

Questa interfaccia è utilizzata come parte di [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillType()](#getFillType--) | Restituisce il tipo di riempimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Restituisce il colore di un riempimento solido. |
| [getGradientFormat()](#getGradientFormat--) | Restituisce il formato di riempimento a gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Restituisce il formato di riempimento a motivo. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se il riempimento deve essere ruotato con una forma. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

Restituisce il tipo di riempimento. Solo lettura [FillType](../../com.aspose.slides/filltype).

**Restituisce:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

Restituisce il colore di un riempimento solido. Solo lettura java.awt.Color.

**Restituisce:**
java.awt.Color
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

Restituisce il formato di riempimento a motivo. Solo lettura [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Restituisce:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

Determina se il riempimento deve essere ruotato con una forma. Solo lettura boolean.

**Restituisce:**
boolean