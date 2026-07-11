---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Αναπαριστά τη μορφή ενός πίνακα.
type: docs
url: /el/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Αναπαριστά τη μορφή ενός πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος πίνακα. |
| [getTransparency()](#getTransparency--) | Ανακτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [setTransparency(float value)](#setTransparency-float-) | Ανακτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [getEffective()](#getEffective--) | Ανακτά τις αποτελεσματικές ιδιότητες μορφοποίησης πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος πίνακα. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Ανακτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Εγγραφή/Ανάγνωση  float .

**Επιστρέφει:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Ανακτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Εγγραφή/Ανάγνωση  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

Ανακτά τις αποτελεσματικές ιδιότητες μορφοποίησης πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.

**Επιστρέφει:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).