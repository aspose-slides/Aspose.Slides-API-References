---
title: LineFillFormat
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta le proprietà per il riempimento delle linee.
type: docs
url: /it/com.aspose.slides/linefillformat/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

Rappresenta le proprietà per il riempimento delle linee.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Restituisce o imposta il tipo di riempimento. |
| [setFillType(byte value)](#setFillType-byte-) | Restituisce o imposta il tipo di riempimento. |
| [getRotateWithShape()](#getRotateWithShape--) | Determina se il riempimento deve essere ruotato con una forma. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determina se il riempimento deve essere ruotato con una forma. |
| [getSolidFillColor()](#getSolidFillColor--) | Restituisce il colore di un riempimento solido. |
| [getGradientFormat()](#getGradientFormat--) | Restituisce il formato del riempimento a gradiente. |
| [getPatternFormat()](#getPatternFormat--) | Restituisce il formato del riempimento a motivo. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Solo lettura long.

**Restituisce:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```


Restituisce o imposta il tipo di riempimento. Lettura/scrittura [FillType](../../com.aspose.slides/filltype).

**Restituisce:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```


Restituisce o imposta il tipo di riempimento. Lettura/scrittura [FillType](../../com.aspose.slides/filltype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```


Determina se il riempimento deve essere ruotato con una forma. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```


Determina se il riempimento deve essere ruotato con una forma. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```


Restituisce il colore di un riempimento solido. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```


Restituisce il formato del riempimento a gradiente. Solo lettura [IGradientFormat](../../com.aspose.slides/igradientformat).

**Restituisce:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```


Restituisce il formato del riempimento a motivo. Solo lettura [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Restituisce:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)