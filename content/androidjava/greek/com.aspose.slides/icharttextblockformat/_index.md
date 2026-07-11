---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /el/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Αναπαριστά ιδιότητες μορφοποίησης για τα κείμενα των διαγραμμάτων.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Επιστρέφει ή ορίζει το κατακόρυφο αγκίστρωμα κειμένου σε ένα TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Επιστρέφει ή ορίζει το κατακόρυφο αγκίστρωμα κειμένου σε ένα TextFrame. |
| [getCenterText()](#getCenterText--) | Εάν NullableBool.True, το κείμενο πρέπει να κεντράρεται οριζόντια στο πλαίσιο. |
| [setCenterText(byte value)](#setCenterText-byte-) | Εάν NullableBool.True, το κείμενο πρέπει να κεντράρεται οριζόντια στο πλαίσιο. |
| [getTextVerticalType()](#getTextVerticalType--) | Καθορίζει την προσανατολισμό του κειμένου. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Καθορίζει την προσανατολισμό του κειμένου. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει ή ορίζει το δεξιό περιθώριο (points) σε ένα TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Επιστρέφει ή ορίζει το δεξιό περιθώριο (points) σε ένα TextFrame. |
| [getMarginTop()](#getMarginTop--) | Επιστρέφει ή ορίζει το άνω περιθώριο (points) σε ένα TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Επιστρέφει ή ορίζει το άνω περιθώριο (points) σε ένα TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. |
| [getWrapText()](#getWrapText--) | Αληθές εάν το κείμενο τυλίγεται στα περιθώρια του TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Αληθές εάν το κείμενο τυλίγεται στα περιθώρια του TextFrame. |
| [getAutofitType()](#getAutofitType--) | Επιστρέφει ή ορίζει τη λειτουργία αυτόματης προσαρμογής του κειμένου. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Επιστρέφει ή ορίζει τη λειτουργία αυτόματης προσαρμογής του κειμένου. |
| [getRotationAngle()](#getRotationAngle--) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του πλαισίου. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του πλαισίου. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Επιστρέφει ή ορίζει το κατακόρυφο αγκίστρωμα κειμένου σε ένα TextFrame. Ανάγνωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Επιστρέφει:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Επιστρέφει ή ορίζει το κατακόρυφο αγκίστρωμα κειμένου σε ένα TextFrame. Ανάγνωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Εάν NullableBool.True, το κείμενο πρέπει να κεντράρεται οριζόντια στο πλαίσιο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Εάν NullableBool.True, το κείμενο πρέπει να κεντράρεται οριζόντια στο πλαίσιο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Καθορίζει την προσανατολισμό του κειμένου. Η τελική τιμή της οπτικής περιστροφής του κειμένου προκύπτει από αυτήν την ιδιότητα και τη δική της γωνία στην ιδιότητα RotationAngle. Ανάγνωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Επιστρέφει:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Καθορίζει την προσανατολισμό του κειμένου. Η τελική τιμή της οπτικής περιστροφής του κειμένου προκύπτει από αυτήν την ιδιότητα και τη δική της γωνία στην ιδιότητα RotationAngle. Ανάγνωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Επιστρέφει ή ορίζει το δεξιό περιθώριο (points) σε ένα TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Επιστρέφει ή ορίζει το δεξιό περιθώριο (points) σε ένα TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Επιστρέφει ή ορίζει το άνω περιθώριο (points) σε ένα TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Επιστρέφει ή ορίζει το άνω περιθώριο (points) σε ένα TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Αληθές εάν το κείμενο τυλίγεται στα περιθώρια του TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2007/2013). Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Αληθές εάν το κείμενο τυλίγεται στα περιθώρια του TextFrame. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2007/2013). Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Επιστρέφει ή ορίζει τη λειτουργία αυτόματης προσαρμογής του κειμένου. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή [TextAutofitType](../../com.aspose.slides/textautofittype).

**Επιστρέφει:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Επιστρέφει ή ορίζει τη λειτουργία αυτόματης προσαρμογής του κειμένου. Η αλλαγή αυτής της ιδιότητας μπορεί να έχει κάποια επίδραση μόνο για τα παρακάτω μέρη του διαγράμματος: DataLabel και DataLabelFormat (πλήρης υποστήριξη στο PowerPoint 2013· στο PowerPoint 2007 δεν υπάρχει αποτέλεσμα στην απόδοση). Ανάγνωση/εγγραφή [TextAutofitType](../../com.aspose.slides/textautofittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του πλαισίου. Εάν δεν καθοριστεί, χρησιμοποιείται η περιστροφή του σχεδόν αντικειμένου. Εάν καθοριστεί, εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής του κειμένου. Η τελική τιμή της οπτικής περιστροφής του κειμένου προκύπτει από αυτήν την ιδιότητα και τον προκαθορισμένο κατακόρυφο τύπο στην ιδιότητα TextVerticalType. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Σκεφτείτε την περίπτωση όπου ένα σχήμα έχει εφαρμοσμένη περιστροφή 90 μοιρών δεξιόστροφα. 
>  Επιπλέον, το ίδιο το σώμα κειμένου έχει περιστροφή -90 μοιρών 
>  αριστερόστροφα. Στη συνέχεια, το προκύπτον από αυτό σχήμα θα φαίνεται να
>  είναι περιστραμμένο, αλλά το κείμενο μέσα σε αυτό θα φαίνεται σαν να μην έχει περιστραφεί καθόλου.
> ```

**Επιστρέφει:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του πλαισίου. Εάν δεν καθοριστεί, χρησιμοποιείται η περιστροφή του σχεδόν αντικειμένου. Εάν καθοριστεί, εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής του κειμένου. Η τελική τιμή της οπτικής περιστροφής του κειμένου προκύπτει από αυτήν την ιδιότητα και τον προκαθορισμένο κατακόρυφο τύπο στην ιδιότητα TextVerticalType. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Σκεφτείτε την περίπτωση όπου ένα σχήμα έχει εφαρμοσμένη περιστροφή 90 μοιρών δεξιόστροφα. 
>  Επιπλέον, το ίδιο το σώμα κειμένου έχει περιστροφή -90 μοιρών 
>  αριστερόστροφα εφαρμόζεται σε αυτό. Στη συνέχεια, το προκύπτον από αυτό σχήμα θα φαίνεται να
>  είναι περιστραμμένο, αλλά το κείμενο μέσα του θα φαίνεται σαν να μην έχει περιστραφεί καθόλου.
>  ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |