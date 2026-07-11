---
title: IUpDownBarsManager
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Παρέχει πρόσβαση στις μπάρες ανόδου/καθόδου γραφήματος Γραμμής ή Στοκ.
type: docs
url: /el/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Παρέχει πρόσβαση στις μπάρες ανόδου/καθόδου γραφήματος Γραμμής ή Στοκ.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Επιστρέφει τη μορφή των μπάρων ανόδου. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Επιστρέφει τη μορφή των μπάρων καθόδου. |
| [hasUpDownBars()](#hasUpDownBars--) | Καθορίζει αν το γράφημα έχει μπάρες ανόδου/καθόδου. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Καθορίζει αν το γράφημα έχει μπάρες ανόδου/καθόδου. |
| [getGapWidth()](#getGapWidth--) | Επιστρέφει ή ορίζει το πλάτος του κενού. |
| [setGapWidth(int value)](#setGapWidth-int-) | Επιστρέφει ή ορίζει το πλάτος του κενού. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Επιστρέφει τη μορφή των μπάρων ανόδου. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Επιστρέφει τη μορφή των μπάρων καθόδου. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Καθορίζει αν το γράφημα έχει μπάρες ανόδου/καθόδου. Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Καθορίζει αν το γράφημα έχει μπάρες ανόδου/καθόδου. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Επιστρέφει ή ορίζει το πλάτος του κενού. Αναγνώσιμη/εγγράψιμη int.

**Επιστρέφει:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Επιστρέφει ή ορίζει το πλάτος του κενού. Αναγνώσιμη/εγγράψιμη int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |