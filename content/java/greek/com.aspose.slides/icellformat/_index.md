---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά τη μορφή ενός κελιού πίνακα.
type: docs
url: /el/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Αναπαριστά τη μορφή ενός κελιού πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος κελιού. |
| [getBorderLeft()](#getBorderLeft--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής αριστερού περιγράμματος. |
| [getBorderTop()](#getBorderTop--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής επάνω περιγράμματος. |
| [getBorderRight()](#getBorderRight--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής δεξιού περιγράμματος. |
| [getBorderBottom()](#getBorderBottom--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής κάτω περιγράμματος. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγώνιας γραμμής από πάνω-αριστερά προς κάτω-δεξιά. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγώνιας γραμμής από κάτω-αριστερά προς πάνω-δεξιά. |
| [getTransparency()](#getTransparency--) | Αποκτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [setTransparency(float value)](#setTransparency-float-) | Αποκτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [getEffective()](#getEffective--) | Αποκτά τις αποτελεσματικές ιδιότητες μορφοποίησης κελιού πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος κελιού. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής αριστερού περιγράμματος. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής επάνω περιγράμματος. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής δεξιού περιγράμματος. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής κάτω περιγράμματος. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγώνιας γραμμής από πάνω-αριστερά προς κάτω-δεξιά. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγώνιας γραμμής από κάτω-αριστερά προς πάνω-δεξιά. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Αποκτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Αποκτά ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

Αποκτά τις αποτελεσματικές ιδιότητες μορφοποίησης κελιού πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.

**Επιστρέφει:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Ένα [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).