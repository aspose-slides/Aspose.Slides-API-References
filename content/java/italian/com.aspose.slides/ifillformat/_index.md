---
title: IFillFormat
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le opzioni di formattazione del riempimento.
type: docs
url: /it/com.aspose.slides/ifillformat/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Rappresenta un'opzione di formattazione del riempimento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillType()](#getFillType--) | Restituisce o imposta il tipo di riempimento. |
| [setFillType(byte value)](#setFillType-byte-) | Restituisce o imposta il tipo di riempimento. |
| [getSolidFillColor()](#getSolidFillColor--) | Restituisce il colore di riempimento. |
| [getGradientFormat()](#getGradientFormat--) | Restituisce il formato di riempimento gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Restituisce il formato di riempimento a motivo. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Restituisce il formato di riempimento immagine. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se il riempimento debba ruotare con la forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina se il riempimento debba ruotare con la forma. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione del riempimento effettivi con l'ereditarietà applicata. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Restituisce o imposta il tipo di riempimento. Lettura/scrittura [FillType](../../com.aspose.slides/filltype).

**Restituisce:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Restituisce o imposta il tipo di riempimento. Lettura/scrittura [FillType](../../com.aspose.slides/filltype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Restituisce il colore di riempimento. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Restituisce il formato di riempimento gradiente. Solo lettura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Restituisce:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Restituisce il formato di riempimento a motivo. Solo lettura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Restituisce:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Restituisce il formato di riempimento immagine. Solo lettura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Restituisce:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Determina se il riempimento debba ruotare con la forma. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Determina se il riempimento debba ruotare con la forma. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Ottiene i dati di formattazione del riempimento effettivi con l'ereditarietà applicata.

**Restituisce:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).