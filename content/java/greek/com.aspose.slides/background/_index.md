---
title: Background
second_title: Aspose.Slides για Java API Αναφορά
description: Αναπαριστά το φόντο μιας διαφάνειας.
type: docs
url: /el/com.aspose.slides/background/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Αντιπροσωπεύει το φόντο μιας διαφάνειας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει έναν τύπο γεμίσματος φόντου. |
| [setType(byte value)](#setType-byte-) | Επιστρέφει έναν τύπο γεμίσματος φόντου. |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει ένα FillFormat για γεμισμό BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Επιστρέφει ένα EffectFormat για γεμισμό BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Επιστρέφει ένα ColorFormat για γεμισμό BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Επιστρέφει έναν δείκτη του γεμίσματος BackgroundType.Themed στη συλλογή θέματος φόντου. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Επιστρέφει έναν δείκτη του γεμίσματος BackgroundType.Themed στη συλλογή θέματος φόντου. |
| [getEffective()](#getEffective--) | Λαμβάνει τα δεδομένα αποτελεσματικού φόντου με εφαρμοσμένη κληρονομικότητα. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. |
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

Επιστρέφει ένα FillFormat για γεμισμό BackgroundType.OwnBackground. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Επιστρέφει ένα EffectFormat για γεμισμό BackgroundType.OwnBackground. Μόνο για ανάγνωση [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Επιστρέφει:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Επιστρέφει ένα ColorFormat για γεμισμό BackgroundType.Themed. Μόνο για ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Επιστρέφει έναν δείκτη του γεμίσματος BackgroundType.Themed στη συλλογή θέματος φόντου. 0 σημαίνει χωρίς γέμισμα. 1..999 - δείκτης. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Επιστρέφει έναν δείκτη του γεμίσματος BackgroundType.Themed στη συλλογή θέματος φόντου. 0 σημαίνει χωρίς γέμισμα. 1..999 - δείκτης. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Λαμβάνει τα δεδομένα αποτελεσματικού φόντου με εφαρμοσμένη κληρονομικότητα.

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

Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο για ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[Presentation](../../com.aspose.slides/presentation)