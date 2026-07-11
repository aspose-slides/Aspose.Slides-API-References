---
title: ImageTransformOperationCollection
second_title: Aspose.Slides για Android μέσω Java API
description: Αντιπροσωπεύει μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα.
type: docs
url: /el/com.aspose.slides/imagetransformoperationcollection/
---
**Κληρονομικότητα:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**  
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)  
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Αντιπροσωπεύει μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) από τη συλλογή με το δείκτη του. |
| [removeAt(int index)](#removeAt-int-) | Καταργεί ένα εφέ εικόνας από μια συλλογή στον καθορισμένο δείκτη. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Προσθέτει το νέο εφέ Alpha Bi-Level στο τέλος μιας συλλογής. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Προσθέτει το νέο εφέ Alpha Ceiling στο τέλος μιας συλλογής. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Προσθέτει το νέο εφέ Alpha Floor στο τέλος μιας συλλογής. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Προσθέτει το νέο εφέ Alpha Inverse στο τέλος μιας συλλογής. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Προσθέτει το νέο εφέ Alpha Modulate στο τέλος μιας συλλογής. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Προσθέτει το νέο εφέ Alpha Modulate Fixed στο τέλος μιας συλλογής. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Προσθέτει το νέο εφέ Alpha Replace στο τέλος μιας συλλογής. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Προσθέτει το νέο εφέ Bi-Level (μαύρο/λευκό) στο τέλος μιας συλλογής. |
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
| [size()](#size--) | Επιστρέφει τον αριθμό των εφέ εικόνας σε μια συλλογή. |
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Προσθέτει το νέο εφέ εικόνας στο τέλος μιας συλλογής. |
| [clear()](#clear--) | Καταργεί όλα τα εφέ εικόνας από μια συλλογή. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Πίνακα, ξεκινώντας από έναν συγκεκριμένο δείκτη Πίνακα. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Καταργεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Επιστρέφει έναν ενομεωτή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**  
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Επιστρέφει ένα [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) από τη συλλογή με το δείκτη του.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Επιστρέφει:**  
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Το αντικείμενο [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Καταργεί ένα εφέ εικόνας από μια συλλογή στον καθορισμένο δείκτη.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός εφέ εικόνας που πρέπει να διαγραφεί. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Προσθέτει το νέο εφέ Alpha Bi-Level στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Η τιμή κατωφλίου για το εφέ alpha bi-level. |

**Επιστρέφει:**  
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Προσθέτει το νέο εφέ Alpha Ceiling στο τέλος μιας συλλογής.

**Επιστρέφει:**  
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Προσθέτει το νέο εφέ Alpha Floor στο τέλος μιας συλλογής.

**Επιστρέφει:**  
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Προσθέτει το νέο εφέ Alpha Inverse στο τέλος μιας συλλογής.

**Επιστρέφει:**  
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Προσθέτει το νέο εφέ Alpha Modulate στο τέλος μιας συλλογής.

**Επιστρέφει:**  
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Προσθέτει το νέο εφέ Alpha Modulate Fixed στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| amount | float | Το ποσοστό για την κλιμάκωση του alpha. |

**Επιστρέφει:**  
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Προσθέτει το νέο εφέ Alpha Replace στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | float | Η νέα τιμή αδιαφάνειας. |

**Επιστρέφει:**  
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Προσθέτει το νέο εφέ Bi-Level (μαύρο/λευκό) στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Το όριο φωτεινότητας για το εφέ Bi-Level. Τιμές ίσες ή μεγαλύτερες από το όριο τίθενται λευκές. Τιμές μικρότερες από το όριο τίθενται μαύρες. |

**Επιστρέφει:**  
[IBiLevel](../../com.aspose.slides/ibilevel) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Προσθέτει το νέο εφέ Blur στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| radius | double | Η ακτίνα του θολώματος. |
| grow | boolean | Καθορίζει εάν τα όρια του αντικειμένου πρέπει να μεγαλώσουν ως αποτέλεσμα του θολώματος. true υποδηλώνει ότι τα όρια μεγαλώνουν, false ότι δεν μεγαλώνουν. |

**Επιστρέφει:**  
[IBlur](../../com.aspose.slides/iblur) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Προσθέτει το νέο εφέ Color Change στο τέλος μιας συλλογής.

**Επιστρέφει:**  
[IColorChange](../../com.aspose.slides/icolorchange) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Προσθέτει το νέο εφέ Color Replacement στο τέλος μιας συλλογής.

**Επιστρέφει:**  
[IColorReplace](../../com.aspose.slides/icolorreplace) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Προσθέτει το νέο εφέ Duotone στο τέλος μιας συλλογής.

**Επιστρέφει:**  
[IDuotone](../../com.aspose.slides/iduotone) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Προσθέτει το νέο εφέ Fill Overlay στο τέλος μιας συλλογής.

**Επιστρέφει:**  
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Προσθέτει το νέο εφέ Gray Scale στο τέλος μιας συλλογής.

**Επιστρέφει:**  
[IGrayScale](../../com.aspose.slides/igrayscale) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Προσθέτει το νέο εφέ Hue/Saturation/Luminance στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Ο αριθμός των μοιρών κατά τις οποίες ρυθμίζεται η απόχρωση. |
| saturation | float | Το ποσοστό κατά το οποίο ρυθμίζεται ο κορεσμός. |
| luminance | float | Το ποσοστό κατά το οποίο ρυθμίζεται η φωτεινότητα. |

**Επιστρέφει:**  
[IHSL](../../com.aspose.slides/ihsl) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Προσθέτει το νέο εφέ Luminance στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Το ποσοστό αλλαγής της φωτεινότητας. |
| contrast | float | Το ποσοστό αλλαγής της αντίθεσης. |

**Επιστρέφει:**  
[ILuminance](../../com.aspose.slides/iluminance) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Προσθέτει το νέο εφέ Tint στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Η απόχρωση προς την οποία θα γίνεται η απόχρωση. |
| amount | float | Καθορίζει πόσο μετατοπίζεται η τιμή του χρώματος. |

**Επιστρέφει:**  
[ITint](../../com.aspose.slides/itint) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Προσθέτει το νέο εφέ BrightnessContrast στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Το ποσοστό αλλαγής της φωτεινότητας. |
| contrast | float | Το ποσοστό αλλαγής της αντίθεσης. |

**Επιστρέφει:**  
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Δείκτης του νέου εφέ εικόνας στη συλλογή.

### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των εφέ εικόνας σε μια συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Λαμβάνει μια τιμή που υποδεικνύει αν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**  
boolean - true εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση· διαφορετικά false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Προσθέτει το νέο εφέ εικόνας στο τέλος μιας συλλογής.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Το εφέ εικόνας που θα προστεθεί στο τέλος της συλλογής. |

### clear() {#clear--}
```
public final void clear()
```

Καταργεί όλα τα εφέ εικόνας από μια συλλογή.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Το αντικείμενο που θα βρεθεί στη [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**  
boolean - true εάν το αντικείμενο βρέθηκε στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Πίνακα, ξεκινώντας από έναν συγκεκριμένο δείκτη Πίνακα.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Ο μονοδιάστατος Πίνακας που είναι ο προορισμός των στοιχείων που αντιγράφηκαν από το [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο Πίνακας πρέπει να έχει μηδενική βασική δεικτοδότηση. |
| arrayIndex | int | Ο μηδενικός δείκτης στο array από τον οποίο αρχίζει η αντιγραφή. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Καταργεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Παράμετρος:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Το αντικείμενο που θα αφαιρεθεί από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**  
boolean - true εάν το item αφαιρέθηκε επιτυχώς από το [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά false. Αυτή η μέθοδος επιστρέφει επίσης false εάν το item δεν βρεθεί στην αρχική [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Επιστρέφει έναν ενομεωτή που διατρέχει τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη της συλλογής.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.