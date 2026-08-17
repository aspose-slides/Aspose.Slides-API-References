---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /el/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Αναπαριστά την τιμή προσαρμογής γεωμετρικού σχήματος. Αυτές οι τιμές επηρεάζουν το σχήμα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRawValue()](#getRawValue--) | Επιστρέφει ή ορίζει την τιμή προσαρμογής "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Επιστρέφει ή ορίζει την τιμή προσαρμογής "as is". |
| [getAngleValue()](#getAngleValue--) | Επιστρέφει ή ορίζει την τιμή, ερμηνεύοντάς την ως γωνία σε μοίρες. |
| [setAngleValue(float value)](#setAngleValue-float-) | Επιστρέφει ή ορίζει την τιμή, ερμηνεύοντάς την ως γωνία σε μοίρες. |
| [getName()](#getName--) | Επιστρέφει ένα όνομα αυτής της τιμής προσαρμογής. |
| [getType()](#getType--) | Επιστρέφει τον τύπο της προσαρμογής σχήματος. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Επιστρέφει ή ορίζει την τιμή προσαρμογής "as is". Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Επιστρέφει ή ορίζει την τιμή προσαρμογής "as is". Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Επιστρέφει ή ορίζει την τιμή, ερμηνεύοντάς την ως γωνία σε μοίρες. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Επιστρέφει ή ορίζει την τιμή, ερμηνεύοντάς την ως γωνία σε μοίρες. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```

Επιστρέφει ένα όνομα αυτής της τιμής προσαρμογής. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Επιστρέφει τον τύπο της προσαρμογής σχήματος. Μόνο για ανάγνωση [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Επιστρέφει:**
int