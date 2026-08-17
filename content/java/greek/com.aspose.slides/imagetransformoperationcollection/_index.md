---
title: ImageTransformOperationCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα.
type: docs
url: /el/com.aspose.slides/imagetransformoperationcollection/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Αναπαριστά μια συλλογή εφέ που εφαρμόζονται σε μια εικόνα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) από τη συλλογή με το ευρετήριο του. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα εφέ εικόνας από μια συλλογή στο συγκεκριμένο ευρετήριο. |
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
| [isReadOnly()](#isReadOnly--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Προσθέτει το νέο εφέ εικόνας στο τέλος μιας συλλογής. |
| [clear()](#clear--) | Αφαιρεί όλα τα εφέ εικόνας από μια συλλογή. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Array, ξεκινώντας από ένα συγκεκριμένο ευρετήριο Array. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```


Επιστρέφει ένα [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) από τη συλλογή με το ευρετήριο του.

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


Αφαιρεί ένα εφέ εικόνας από μια συλλογή στο συγκεκριμένο ευρετήριο.

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
| threshold | float | Η τιμή όριου για το εφέ alpha bi-level. |

**Επιστρέφει:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```


Προσθέτει το νέο εφέ Alpha Ceiling στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```


Προσθέτει το νέο εφέ Alpha Floor στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```


Προσθέτει το νέο εφέ Alpha Inverse στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```


Προσθέτει το νέο εφέ Alpha Modulate στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```


Προσθέτει το νέο εφέ Alpha Modulate Fixed στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| amount | float | Το ποσοστό με το οποίο κλιμακώνεται το alpha. |

**Επιστρέφει:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
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
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```


Προσθέτει το νέο εφέ Bi-Level (μαύρο/λευκό) στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Το όριο φωτεινότητας για το εφέ Bi-Level. Τιμές μεγαλύτερες ή ίσες με το όριο ορίζονται ως λευκό. Τιμές μικρότερες από το όριο ορίζονται ως μαύρο. |

**Επιστρέφει:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```


Προσθέτει το νέο εφέ Blur στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| radius | double | Η ακτίνα του θολώματος. |
| grow | boolean | Καθορίζει εάν τα όρια του αντικειμένου θα αυξηθούν ως αποτέλεσμα του θολώματος. Η τιμή true υποδεικνύει ότι τα όρια μεγαλώνουν, ενώ false ότι δεν μεγαλώνουν. |

**Επιστρέφει:**
[IBlur](../../com.aspose.slides/iblur) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```


Προσθέτει το νέο εφέ Color Change στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IColorChange](../../com.aspose.slides/icolorchange) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```


Προσθέτει το νέο εφέ Color Replacement στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```


Προσθέτει το νέο εφέ Duotone στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IDuotone](../../com.aspose.slides/iduotone) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```


Προσθέτει το νέο εφέ Fill Overlay στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```


Προσθέτει το νέο εφέ Gray Scale στο τέλος μιας συλλογής.

**Επιστρέφει:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```


Προσθέτει το νέο εφέ Hue/Saturation/Luminance στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Ο αριθμός των μοιρών κατά τον οποίο ρυθμίζεται η απόχρωση. |
| saturation | float | Το ποσοστό κατά το οποίο ρυθμίζεται ο κορεσμός. |
| luminance | float | Το ποσοστό κατά το οποίο ρυθμίζεται η φωτεινότητα. |

**Επιστρέφει:**
[IHSL](../../com.aspose.slides/ihsl) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```


Προσθέτει το νέο εφέ Luminance στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Το ποσοστό για την αλλαγή της φωτεινότητας. |
| contrast | float | Το ποσοστό για την αλλαγή της αντίθεσης. |

**Επιστρέφει:**
[ILuminance](../../com.aspose.slides/iluminance) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```


Προσθέτει το νέο εφέ Tint στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Η απόχρωση προς την οποία θα χρωματιστεί. |
| amount | float | Καθορίζει το πόσο μετατοπίζεται η τιμή του χρώματος. |

**Επιστρέφει:**
[ITint](../../com.aspose.slides/itint) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```


Προσθέτει το νέο εφέ BrightnessContrast στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Το ποσοστό για την αλλαγή της φωτεινότητας. |
| contrast | float | Το ποσοστό για την αλλαγή της αντίθεσης. |

**Επιστρέφει:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Ο δείκτης του νέου εφέ εικόνας στη συλλογή.
### size() {#size--}
```
public final int size()
```


Επιστρέφει τον αριθμό των εφέ εικόνας σε μια συλλογή. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean - true εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) είναι μόνο για ανάγνωση· διαφορετικά, false.
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```


Προσθέτει το νέο εφέ εικόνας στο τέλος μιας συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Το εφέ εικόνας που προστίθεται στο τέλος μιας συλλογής. |
### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλα τα εφέ εικόνας από μια συλλογή.
### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```


Καθορίζει εάν το [IGenericCollection](../../com.aspose.slides/igenericcollection) περιέχει μια συγκεκριμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Το αντικείμενο που εντοπίζεται στο [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το αντικείμενο βρεθεί στο [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false.
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```


Αντιγράφει τα στοιχεία του [IGenericCollection](../../com.aspose.slides/igenericcollection) σε έναν Array, ξεκινώντας από ένα συγκεκριμένο ευρετήριο Array.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Ο μονοδιάστατος Array που είναι προορισμός των στοιχείων που αντιγράφηκαν από το [IGenericCollection](../../com.aspose.slides/igenericcollection). Ο Array πρέπει να έχει δεικτοδότηση που ξεκινά από μηδέν. |
| arrayIndex | int | Ο δείκτης μηδενικής βάσης στον array από τον οποίο ξεκινά η αντιγραφή. |
### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```


Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από το [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Το αντικείμενο που πρέπει να αφαιρεθεί από το [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Επιστρέφει:**
boolean - true εάν το  item  αφαιρεθεί επιτυχώς από το [IGenericCollection](../../com.aspose.slides/igenericcollection)· διαφορετικά, false. Αυτή η μέθοδος επίσης επιστρέφει false εάν το αντικείμενο δεν βρεθεί στην αρχική [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```


Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για τη διαδρομή της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.