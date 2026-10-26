---
title: IImageTransformOperationCollection
second_title: Aspose.Slides για Java API Αναφορά
description: Αναπαριστά μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα.
type: docs
url: /el/com.aspose.slides/iimagetransformoperationcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Αναπαριστά μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) από τη συλλογή με το δείκτη του. |
| [removeAt(int index)](#removeAt-int-) | Καταργεί ένα εφέ εικόνας από μια συλλογή στον καθορισμένο δείκτη. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Προσθέτει το νέο Alpha Bi-Level effect στο τέλος μιας συλλογής. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Προσθέτει το νέο Alpha Ceiling effect στο τέλος μιας συλλογής. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Προσθέτει το νέο Alpha Floor effect στο τέλος μιας συλλογής. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Προσθέτει το νέο Alpha Inverse effect στο τέλος μιας συλλογής. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Προσθέτει το νέο Alpha Modulate effect στο τέλος μιας συλλογής. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Προσθέτει το νέο Alpha Modulate Fixed effect στο τέλος μιας συλλογής. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Προσθέτει το νέο Alpha Replace effect στο τέλος μιας συλλογής. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Προσθέτει το νέο Bi-Level (black/white) effect στο τέλος μιας συλλογής. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Προσθέτει το νέο Blur effect στο τέλος μιας συλλογής. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Προσθέτει το νέο Color Change effect στο τέλος μιας συλλογής. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Προσθέτει το νέο Color Replacement effect στο τέλος μιας συλλογής. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Προσθέτει το νέο Duotone effect στο τέλος μιας συλλογής. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Προσθέτει το νέο Fill Overlay effect στο τέλος μιας συλλογής. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Προσθέτει το νέο Gray Scale effect στο τέλος μιας συλλογής. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Προσθέτει το νέο Hue/Saturation/Luminance effect στο τέλος μιας συλλογής. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Προσθέτει το νέο Luminance effect στο τέλος μιας συλλογής. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Προσθέτει το νέο Tint effect στο τέλος μιας συλλογής. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Προσθέτει το νέο BrightnessContrast effect στο τέλος μιας συλλογής. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Επιστρέφει ένα [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) από τη συλλογή με το δείκτη του.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Επιστρέφει:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Το [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) αντικείμενο.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Καταργεί ένα εφέ εικόνας από μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός εφέ εικόνας που πρέπει να διαγραφεί. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Προσθέτει το νέο Alpha Bi-Level effect στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Η τιμή κατωφλίου για το Alpha Bi-Level effect. |

**Επιστρέφει:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Προσθέτει το νέο Alpha Ceiling effect στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Προσθέτει το νέο Alpha Floor effect στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Προσθέτει το νέο Alpha Inverse effect στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Προσθέτει το νέο Alpha Modulate effect στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Προσθέτει το νέο Alpha Modulate Fixed effect στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| amount | float | Το ποσοστό για την προσαρμογή του alpha. |

**Επιστρέφει:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Προσθέτει το νέο Alpha Replace effect στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | float | Η νέα τιμή αδιαφάνειας. |

**Επιστρέφει:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Προσθέτει το νέο Bi-Level (black/white) effect στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Το κατώφλι φωτεινότητας για το Bi-Level effect. Οι τιμές ίσες ή μεγαλύτερες από το κατώφλι ορίζονται ως λευκό, οι μικρότερες ως μαύρο. |

**Επιστρέφει:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Προσθέτει το νέο Blur effect στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| radius | double | Η ακτίνα του θολώματος. |
| grow | boolean | Καθορίζει αν τα όρια του αντικειμένου θα μεγαλώσουν εξαιτίας του θολώματος. Η τιμή true υποδηλώνει ότι τα όρια μεγαλώνουν, η false ότι δεν αλλάζουν. |

**Επιστρέφει:**
[IBlur](../../com.aspose.slides/iblur) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Προσθέτει το νέο Color Change effect στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IColorChange](../../com.aspose.slides/icolorchange) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Προσθέτει το νέο Color Replacement effect στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Προσθέτει το νέο Duotone effect στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IDuotone](../../com.aspose.slides/iduotone) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Προσθέτει το νέο Fill Overlay effect στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Προσθέτει το νέο Gray Scale effect στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Προσθέτει το νέο Hue/Saturation/Luminance effect στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Ο αριθμός των μοιρών με τις οποίες ρυθμίζεται το hue. |
| saturation | float | Το ποσοστό με το οποίο ρυθμίζεται η κορεσμός. |
| luminance | float | Το ποσοστό με το οποίο ρυθμίζεται η φωτεινότητα. |

**Επιστρέφει:**
[IHSL](../../com.aspose.slides/ihsl) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Προσθέτει το νέο Luminance effect στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Το ποσοστό αλλαγής της φωτεινότητας. |
| contrast | float | Το ποσοστό αλλαγής της αντίθεσης. |

**Επιστρέφει:**
[ILuminance](../../com.aspose.slides/iluminance) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Προσθέτει το νέο Tint effect στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Το hue προς το οποίο γίνεται η απόχρωση. |
| amount | float | Καθορίζει το πόσο μετατοπίζεται η τιμή χρώματος. |

**Επιστρέφει:**
[ITint](../../com.aspose.slides/itint) - Δείκτης του νέου εφέ εικόνας στη συλλογή.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Προσθέτει το νέο BrightnessContrast effect στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Το ποσοστό αλλαγής της φωτεινότητας. |
| contrast | float | Το ποσοστό αλλαγής της αντίθεσης. |

**Επιστρέφει:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Δείκτης του νέου εφέ εικόνας στη συλλογή.