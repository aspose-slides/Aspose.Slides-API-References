---
title: IAlphaBiLevel
second_title: Aspose.Slides για την αναφορά API της Java
description: Αναπαριστά ένα εφέ Alpha Bi-Level.
type: docs
url: /el/com.aspose.slides/ialphabilevel/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
``` 
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Αναπαριστά ένα εφέ Alpha Bi-Level. Οι τιμές Alpha (Διαφάνεια) μικρότερες από το κατώφλι μετατρέπονται σε 0 (πλήρως διαφανείς) και οι τιμές alpha ίσες ή μεγαλύτερες από το κατώφλι μετατρέπονται σε 100% (πλήρως αδιαφανείς).

--------------------

Χρησιμοποιήστε το ImageTransformOperationFactory για να δημιουργήσετε στιγμές στο COM.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getThreshold()](#getThreshold--) | Επιστρέφει το κατώφλι του εφέ. |
| [setThreshold(float value)](#setThreshold-float-) | Επιστρέφει το κατώφλι του εφέ. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Επιστρέφει το κατώφλι του εφέ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Επιστρέφει το κατώφλι του εφέ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |