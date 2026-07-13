---
title: ILineFillFormat
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta le proprietà per il riempimento delle linee.
type: docs
url: /it/com.aspose.slides/ilinefillformat/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Rappresenta le proprietà per il riempimento delle linee.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillType()](#getFillType--) | Restituisce o imposta il tipo di riempimento. |
| [setFillType(byte value)](#setFillType-byte-) | Restituisce o imposta il tipo di riempimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Restituisce il colore di un riempimento solido. |
| [getGradientFormat()](#getGradientFormat--) | Restituisce il formato del riempimento gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Restituisce il formato del riempimento a motivo. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se il riempimento deve essere ruotato con una forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina se il riempimento deve essere ruotato con una forma. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Restituisce o imposta il tipo di riempimento. Lettura/Scrittura [FillType](../../com.aspose.slides/filltype).

**Restituisce:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Restituisce o imposta il tipo di riempimento. Lettura/Scrittura [FillType](../../com.aspose.slides/filltype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Restituisce il colore di un riempimento solido. Sola lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Restituisce il formato del riempimento gradiente. Sola lettura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Restituisce:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Restituisce il formato del riempimento a motivo. Sola lettura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Restituisce:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Determina se il riempimento deve essere ruotato con una forma. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Determina se il riempimento deve essere ruotato con una forma. Lettura/Scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |