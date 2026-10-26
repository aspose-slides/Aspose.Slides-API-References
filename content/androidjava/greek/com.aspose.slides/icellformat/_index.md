---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Αναπαριστά τη μορφοποίηση ενός κελιού πίνακα.
type: docs
url: /el/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Αναπαριστά τη μορφοποίηση ενός κελιού πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος κελιού. |
| [getBorderLeft()](#getBorderLeft--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων αριστερής γραμμής περιγράμματος. |
| [getBorderTop()](#getBorderTop--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων επάνω γραμμής περιγράμματος. |
| [getBorderRight()](#getBorderRight--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων δεξιάς γραμμής περιγράμματος. |
| [getBorderBottom()](#getBorderBottom--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων κάτω γραμμής περιγράμματος. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγωνίου γραμμής από επάνω αριστερά προς κάτω δεξιά. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγωνίου γραμμής από κάτω αριστερά προς επάνω δεξιά. |
| [getTransparency()](#getTransparency--) | Ανακτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [setTransparency(float value)](#setTransparency-float-) | Ανακτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [getEffective()](#getEffective--) | Ανακτά αποτελεσματικές ιδιότητες μορφοποίησης κελιού πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος κελιού. Μόνο ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων αριστερής γραμμής περιγράμματος. Μόνο ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων επάνω γραμμής περιγράμματος. Μόνο ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων δεξιάς γραμμής περιγράμματος. Μόνο ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων κάτω γραμμής περιγράμματος. Μόνο ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγωνίου γραμμής από επάνω αριστερά προς κάτω δεξιά. Μόνο ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγωνίου γραμμής από κάτω αριστερά προς επάνω δεξιά. Μόνο ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Ανακτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Ανακτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Ανακτά αποτελεσματικές ιδιότητες μορφοποίησης κελιού πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.

**Επιστρέφει:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).