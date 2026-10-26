---
title: IAlphaBiLevel
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά ένα εφέ Alpha Bi-Level.
type: docs
url: /el/com.aspose.slides/ialphabilevel/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Αναπαριστά ένα εφέ Alpha Bi-Level. Τιμές Alpha (Διαφάνειας) μικρότερες από το όριο μετατρέπονται σε 0 (εντελώς διαφανείς) και τιμές alpha μεγαλύτερες ή ίσες με το όριο μετατρέπονται σε 100 % (εντελώς αδιαφανείς).

--------------------

Χρησιμοποιήστε το ImageTransformOperationFactory για να δημιουργήσετε στιγμιότυπα σε COM.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getThreshold()](#getThreshold--) | Επιστρέφει το όριο του εφέ. |
| [setThreshold(float value)](#setThreshold-float-) | Επιστρέφει το όριο του εφέ. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Επιστρέφει το όριο του εφέ. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Επιστρέφει το όριο του εφέ. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |