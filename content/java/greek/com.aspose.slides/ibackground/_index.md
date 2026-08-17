---
title: IBackground
second_title: Aspose.Slides για Java Αναφορά API
description: Αναπαριστά το φόντο μιας διαφάνειας.
type: docs
url: /el/com.aspose.slides/ibackground/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Αναπαριστά το φόντο μιας διαφάνειας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει έναν τύπο γέμισματος φόντου. |
| [setType(byte value)](#setType-byte-) | Επιστρέφει έναν τύπο γέμισματος φόντου. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει ένα FillFormat για γέμισμα BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει ένα EffectFormat για γέμισμα BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Επιστρέφει ένα ColorFormat για γέμισμα BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Επιστρέφει έναν δείκτη του γέμισματος BackgroundType.Themed στη συλλογή θεμάτων φόντου. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Επιστρέφει έναν δείκτη του γέμισματος BackgroundType.Themed στη συλλογή θεμάτων φόντου. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα φόντου με την κληρονομικότητα που εφαρμόζεται. |
### getType() {#getType--}
```
public abstract byte getType()
```

Επιστρέφει έναν τύπο γέμισματος φόντου. Ανάγνωση/εγγραφή [BackgroundType](../../com.aspose.slides/backgroundtype).

**Επιστρέφει:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Επιστρέφει έναν τύπο γέμισματος φόντου. Ανάγνωση/εγγραφή [BackgroundType](../../com.aspose.slides/backgroundtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Επιστρέφει ένα FillFormat για γέμισμα BackgroundType.OwnBackground. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Επιστρέφει ένα EffectFormat για γέμισμα BackgroundType.OwnBackground. Μόνο για ανάγνωση [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Επιστρέφει:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Επιστρέφει ένα ColorFormat για γέμισμα BackgroundType.Themed. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Επιστρέφει έναν δείκτη του γέμισματος BackgroundType.Themed στη συλλογή θεμάτων φόντου. 0 σημαίνει χωρίς γέμισμα. 1..999 - δείκτης. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

Επιστρέφει έναν δείκτη του γέμισματος BackgroundType.Themed στη συλλογή θεμάτων φόντου. 0 σημαίνει χωρίς γέμισμα. 1..999 - δείκτης. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα φόντου με την κληρονομικότητα που εφαρμόζεται.

**Επιστρέφει:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - Ένα [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).