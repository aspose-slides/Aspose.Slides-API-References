---
title: IColorEffect
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un effetto di colore per un comportamento di animazione.
type: docs
url: /it/com.aspose.slides/icoloreffect/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Rappresenta un effetto di colore per un comportamento di animazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFrom()](#getFrom--) | Questo valore è usato per specificare il colore iniziale del comportamento. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Questo valore è usato per specificare il colore iniziale del comportamento. |
| [getTo()](#getTo--) | Descrive il colore risultante per la modifica del colore dell'animazione. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Descrive il colore risultante per la modifica del colore dell'animazione. |
| [getBy()](#getBy--) | Descrive il valore di offset relativo per l'animazione del colore. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Descrive il valore di offset relativo per l'animazione del colore. |
| [getColorSpace()](#getColorSpace--) | Rappresenta lo spazio colore del comportamento. |
| [setColorSpace(int value)](#setColorSpace-int-) | Rappresenta lo spazio colore del comportamento. |
| [getDirection()](#getDirection--) | Specifica la direzione in cui ciclicare la tonalità intorno alla ruota dei colori. |
| [setDirection(int value)](#setDirection-int-) | Specifica la direzione in cui ciclicare la tonalità intorno alla ruota dei colori. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Questo valore è usato per specificare il colore iniziale del comportamento. Lettura/Scrittura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Questo valore è usato per specificare il colore iniziale del comportamento. Lettura/Scrittura [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Descrive il colore risultante per la modifica del colore dell'animazione. Lettura/Scrittura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Descrive il colore risultante per la modifica del colore dell'animazione. Lettura/Scrittura [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Descrive il valore di offset relativo per l'animazione del colore. Lettura/Scrittura [IColorOffset](../../com.aspose.slides/icoloroffset).

**Restituisce:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Descrive il valore di offset relativo per l'animazione del colore. Lettura/Scrittura [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |
### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Rappresenta lo spazio colore del comportamento. Lettura/Scrittura [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Restituisce:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Rappresenta lo spazio colore del comportamento. Lettura/Scrittura [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Specifică la direzione in cui ciclicare la tonalità intorno alla ruota dei colori. Lettura/Scrittura [ColorDirection](../../com.aspose.slides/colordirection).

**Restituisce:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Specifică la direzione in cui ciclicare la tonalità intorno alla ruota dei colori. Lettura/Scrittura [ColorDirection](../../com.aspose.slides/colordirection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |