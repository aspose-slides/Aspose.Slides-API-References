---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /el/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Παρέχει πρόσβαση στις μπάρες άνω/κάτω γραμμής ή διαγράμματος τύπου Stock.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Επιστρέφει τη μορφή των άνω μπαρών. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Επιστρέφει τη μορφή των κάτω μπαρών. |
| [hasUpDownBars()](#hasUpDownBars--) | Καθορίζει εάν το γράφημα έχει μπάρες άνω/κάτω. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Καθορίζει εάν το γράφημα έχει μπάρες άνω/κάτω. |
| [getGapWidth()](#getGapWidth--) | Επιστρέφει ή ορίζει το πλάτος του διαστήματος. |
| [setGapWidth(int value)](#setGapWidth-int-) | Επιστρέφει ή ορίζει το πλάτος του διαστήματος. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Επιστρέφει τη μορφή των άνω μπαρών. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Επιστρέφει τη μορφή των κάτω μπαρών. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Καθορίζει εάν το γράφημα έχει μπάρες άνω/κάτω. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Καθορίζει εάν το γράφημα έχει μπάρες άνω/κάτω. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Επιστρέφει ή ορίζει το πλάτος του διαστήματος. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Επιστρέφει ή ορίζει το πλάτος του διαστήματος. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |