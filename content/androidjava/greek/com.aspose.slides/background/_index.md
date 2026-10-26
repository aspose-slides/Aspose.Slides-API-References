---
title: Background
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά το φόντο μιας διαφάνειας.
type: docs
url: /el/com.aspose.slides/background/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Αναπαριστά το φόντο μιας διαφάνειας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει έναν τύπο γεμίσματος φόντου. |
| [setType(byte value)](#setType-byte-) | Επιστρέφει έναν τύπο γεμίσματος φόντου. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει ένα FillFormat για BackgroundType.OwnBackground γέμισμα. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει ένα EffectFormat για BackgroundType.OwnBackground γέμισμα. |
| [getStyleColor()](#getStyleColor--) | Επιστρέφει ένα ColorFormat για ένα BackgroundType.Themed γέμισμα. |
| [getStyleIndex()](#getStyleIndex--) | Επιστρέφει ένα δείκτη του BackgroundType.Themed γεμίσματος στη συλλογή θεμάτων φόντου. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Επιστρέφει ένα δείκτη του BackgroundType.Themed γεμίσματος στη συλλογή θεμάτων φόντου. |
| [getEffective()](#getEffective--) | Αποκτά τα αποτελεσματικά δεδομένα φόντου με την εφαρμοσμένη κληρονομικότητα. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Επιστρέφει τη διαφάνεια γονέα ενός σχήματος. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την παρουσίαση γονέα μιας διαφάνειας. |
### getType() {#getType--}
```
public final byte getType()
```


Επιστρέφει έναν τύπο γεμίσματος φόντου. Ανάγνωση/εγγραφή [BackgroundType](../../com.aspose.slides/backgroundtype).

**Επιστρέφει:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Επιστρέφει έναν τύπο γεμίσματος φόντου. Ανάγνωση/εγγραφή [BackgroundType](../../com.aspose.slides/backgroundtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Επιστρέφει ένα FillFormat για BackgroundType.OwnBackground γέμισμα. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


Επιστρέφει ένα EffectFormat για BackgroundType.OwnBackground γέμισμα. Μόνο για ανάγνωση [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Επιστρέφει:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


Επιστρέφει ένα ColorFormat για ένα BackgroundType.Themed γέμισμα. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


Επιστρέφει ένα δείκτη του BackgroundType.Themed γεμίσματος στη συλλογή θεμάτων φόντου. 0 σημαίνει χωρίς γέμισμα. 1..999 - δείκτης. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


Επιστρέφει ένα δείκτη του BackgroundType.Themed γεμίσματος στη συλλογή θεμάτων φόντου. 0 σημαίνει χωρίς γέμισμα. 1..999 - δείκτης. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


Αποκτά τα αποτελεσματικά δεδομένα φόντου με την εφαρμοσμένη κληρονομικότητα.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```


Επιστρέφει τη διαφάνεια γονέα ενός σχήματος. Μόνο για ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```


Επιστρέφει την παρουσίαση γονέα μιας διαφάνειας. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[Presentation](../../com.aspose.slides/presentation)