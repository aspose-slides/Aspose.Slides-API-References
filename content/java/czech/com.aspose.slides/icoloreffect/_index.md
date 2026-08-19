---
title: IColorEffect
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje barevný efekt pro animační chování.
type: docs
url: /cs/com.aspose.slides/icoloreffect/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Představuje barevný efekt pro animační chování.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFrom()](#getFrom--) | Tato hodnota se používá k určení počáteční barvy chování. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Tato hodnota se používá k určení počáteční barvy chování. |
| [getTo()](#getTo--) | Popisuje výslednou barvu pro změnu barvy animace. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Popisuje výslednou barvu pro změnu barvy animace. |
| [getBy()](#getBy--) | Popisuje relativní offsetovou hodnotu pro barevnou animaci. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Popisuje relativní offsetovou hodnotu pro barevnou animaci. |
| [getColorSpace()](#getColorSpace--) | Reprezentuje barevný prostor chování. |
| [setColorSpace(int value)](#setColorSpace-int-) | Reprezentuje barevný prostor chování. |
| [getDirection()](#getDirection--) | Určuje, kterým směrem postupovat v odstínu po barevném kruhu. |
| [setDirection(int value)](#setDirection-int-) | Určuje, kterým směrem postupovat v odstínu po barevném kruhu. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Tato hodnota se používá k určení počáteční barvy chování. Číst/Zapisovat [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Tato hodnota se používá k určení počáteční barvy chování. Číst/Zapisovat [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Popisuje výslednou barvu pro změnu barvy animace. Číst/Zapisovat [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Popisuje výslednou barvu pro změnu barvy animace. Číst/Zapisovat [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Popisuje relativní offsetovou hodnotu pro barevnou animaci. Číst/Zapisovat [IColorOffset](../../com.aspose.slides/icoloroffset).

**Vrací:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Popisuje relativní offsetovou hodnotu pro barevnou animaci. Číst/Zapisovat [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |
### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Reprezentuje barevný prostor chování. Číst/Zapisovat [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Vrací:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Reprezentuje barevný prostor chování. Číst/Zapisovat [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Určuje, kterým směrem postupovat v odstínu po barevném kruhu. Číst/Zapisovat [ColorDirection](../../com.aspose.slides/colordirection).

**Vrací:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Určuje, kterým směrem postupovat v odstínu po barevném kruhu. Číst/Zapisovat [ColorDirection](../../com.aspose.slides/colordirection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |