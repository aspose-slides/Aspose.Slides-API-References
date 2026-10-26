---
title: IImageTransformOperationCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα.
type: docs
url: /el/com.aspose.slides/iimagetransformoperationcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Αντιπροσωπεύει μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) από τη συλλογή με βάση τον δείκτη του. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα εφέ εικόνας από μια συλλογή στον καθορισμένο δείκτη. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Προσθέτει το νέο εφέ Alpha Bi-Level στο τέλος μιας συλλογής. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Προσθέτει το νέο εφέ Alpha Ceiling στο τέλος μιας συλλογής. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Προσθέτει το νέο εφέ Alpha Floor στο τέλος μιας συλλογής. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Προσθέτει το νέο εφέ Alpha Inverse στο τέλος μιας συλλογής. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Προσθέτει το νέο εφέ Alpha Modulate στο τέλος μιας συλλογής. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Προσθέτει το νέο εφέ Alpha Modulate Fixed στο τέλος μιας συλλογής. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Προσθέτει το νέο εφέ Alpha Replace στο τέλος μιας συλλογής. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Προσθέτει το νέο εφέ Bi-Level (black/white) στο τέλος μιας συλλογής. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Προσθέτει το νέο εφέ Blur στο τέλος μιας συλλογής. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Προσθέτει το νέο εφέ Color Change στο τέλος μιας συλλογής. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Προσθέτει το νέο εφέ Color Replacement στο τέλος μιας συλλογής. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Προσθέτει το νέο εφέ Duotone στο τέλος μιας συλλογής. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Προσθέτει το νέο εφέ Fill Overlay στο τέλος μιας συλλογής. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Προσθέτει το νέο εφέ Gray Scale στο τέλος μιας συλλογής. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Προσθέτει το νέο εφέ Hue/Saturation/Luminance στο τέλος μιας συλλογής. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Προσθέτει το νέο εφέ Luminance στο τέλος μιας συλλογής. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Προσθέτει το νέο εφέ Tint στο τέλος μιας συλλογής. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Προσθέτει το νέο εφέ BrightnessContrast στο τέλος μιας συλλογής. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Επιστρέφει ένα [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) από τη συλλογή με βάση τον δείκτη του.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Επιστρέφει:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Το αντικείμενο [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί ένα εφέ εικόνας από μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός εφέ εικόνας που πρέπει να διαγραφεί. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Προσθέτει το νέο εφέ Alpha Bi-Level στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Η τιμή κατωφλίου για το εφέ alpha bi-level. |

**Επιστρέφει:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Προσθέτει το νέο εφέ Alpha Ceiling στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Προσθέτει το νέο εφέ Alpha Floor στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Προσθέτει το νέο εφέ Alpha Inverse στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Προσθέτει το νέο εφέ Alpha Modulate στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Προσθέτει το νέο εφέ Alpha Modulate Fixed στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| amount | float | Το ποσοστό για την κλιμάκωση του alpha. |

**Επιστρέφει:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Προσθέτει το νέο εφέ Alpha Replace στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | float | Η νέα τιμή αδιαφάνειας. |

**Επιστρέφει:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Προσθέτει το νέο εφέ Bi-Level (black/white) στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Το κατώφλι φωτεινότητας για το εφέ Bi-Level. Οι τιμές μεγαλύτερες ή ίσες του κατωφλιού ορίζονται σε λευκό. Οι τιμές μικρότερες του κατωφλιού ορίζονται σε μαύρο. |

**Επιστρέφει:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Προσθέτει το νέο εφέ Blur στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| radius | double | Η ακτίνα του θόλωσης. |
| grow | boolean | Καθορίζει αν τα όρια του αντικειμένου θα μεγαλώσουν ως αποτέλεσμα της θόλωσης. Η τιμή true υποδεικνύει ότι τα όρια μεγαλώνουν, ενώ false ότι δεν μεγαλώνουν. |

**Επιστρέφει:**
[IBlur](../../com.aspose.slides/iblur) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Προσθέτει το νέο εφέ Color Change στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IColorChange](../../com.aspose.slides/icolorchange) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Προσθέτει το νέο εφέ Color Replacement στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Προσθέτει το νέο εφέ Duotone στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IDuotone](../../com.aspose.slides/iduotone) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Προσθέτει το νέο εφέ Fill Overlay στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Προσθέτει το νέο εφέ Gray Scale στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Προσθέτει το νέο εφέ Hue/Saturation/Luminance στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Ο αριθμός των μοιρών κατά τον οποίο ρυθμίζεται η απόχρωση. |
| saturation | float | Το ποσοστό κατά το οποίο ρυθμίζεται ο κορεσμός. |
| luminance | float | Το ποσοστό κατά το οποίο ρυθμίζεται η φωτεινότητα. |

**Επιστρέφει:**
[IHSL](../../com.aspose.slides/ihsl) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Προσθέτει το νέο εφέ Luminance στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Το ποσοστό αλλαγής της φωτεινότητας. |
| contrast | float | Το ποσοστό αλλαγής της αντίθεσης. |

**Επιστρέφει:**
[ILuminance](../../com.aspose.slides/iluminance) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Προσθέτει το νέο εφέ Tint στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Η απόχρωση προς την οποία θα χρωματιστεί. |
| amount | float | Καθορίζει κατά πόσο θα μετατοπιστεί η τιμή του χρώματος. |

**Επιστρέφει:**
[ITint](../../com.aspose.slides/itint) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Προσθέτει το νέο εφέ BrightnessContrast στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Το ποσοστό αλλαγής της φωτεινότητας. |
| contrast | float | Το ποσοστό αλλαγής της αντίθεσης. |

**Επιστρέφει:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Δείκτης του νέου εφέ εικόνας σε μια συλλογή.