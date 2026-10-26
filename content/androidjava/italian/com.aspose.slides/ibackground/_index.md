---
title: IBackground
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta lo sfondo di una diapositiva.
type: docs
url: /it/com.aspose.slides/ibackground/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Rappresenta lo sfondo di una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Restituisce un tipo di riempimento di sfondo. |
| [setType(byte value)](#setType-byte-) | Restituisce un tipo di riempimento di sfondo. |
| [getFillFormat()](#getFillFormat--) | Restituisce un FillFormat per il riempimento BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Restituisce un EffectFormat per il riempimento BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Restituisce un ColorFormat per un riempimento BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Restituisce un indice del riempimento BackgroundType.Themed nella raccolta dei temi di sfondo. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Restituisce un indice del riempimento BackgroundType.Themed nella raccolta dei temi di sfondo. |
| [getEffective()](#getEffective--) | Ottiene i dati di sfondo effettivi con l'ereditarietà applicata. |
### getType() {#getType--}
```
public abstract byte getType()
```

Restituisce un tipo di riempimento di sfondo. Lettura/Scrittura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Restituisce:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Restituisce un tipo di riempimento di sfondo. Lettura/Scrittura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Restituisce un FillFormat per il riempimento BackgroundType.OwnBackground. Sola lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Restituisce un EffectFormat per il riempimento BackgroundType.OwnBackground. Sola lettura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Restituisce:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Restituisce un ColorFormat per un riempimento BackgroundType.Themed. Sola lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Restituisce un indice del riempimento BackgroundType.Themed nella raccolta dei temi di sfondo. 0 significa nessun riempimento. 1..999 - indice. Lettura/Scrittura int.

**Restituisce:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

Restituisce un indice del riempimento BackgroundType.Themed nella raccolta dei temi di sfondo. 0 significa nessun riempimento. 1..999 - indice. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

Ottiene i dati di sfondo effettivi con l'ereditarietà applicata.

**Restituisce:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).