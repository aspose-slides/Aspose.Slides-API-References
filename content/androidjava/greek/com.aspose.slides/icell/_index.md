---
title: ICell
second_title: Αναφορά API Java για Aspose.Slides για Android
description: Αντιπροσωπεύει ένα κελί σε έναν πίνακα.
type: docs
url: /el/com.aspose.slides/icell/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Αναπαριστά ένα κελί σε έναν πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Επιστρέφει μια απόσταση από την αριστερή πλευρά ενός πίνακα έως την αριστερή πλευρά ενός κελιού. |
| [getOffsetY()](#getOffsetY--) | Επιστρέφει μια απόσταση από την επάνω πλευρά ενός πίνακα έως την επάνω πλευρά ενός κελιού. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Επιστρέφει τον δείκτη της πρώτης σειράς που καλύπτεται από το κελί. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Επιστρέφει τον δείκτη της πρώτης στήλης που καλύπτεται από το κελί. |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος του κελιού. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος του κελιού. |
| [getMinimalHeight()](#getMinimalHeight--) | Επιστρέφει το ελάχιστο ύψος ενός κελιού. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει ή ορίζει το δεξιό περιθώριο σε ένα TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Επιστρέφει ή ορίζει το δεξιό περιθώριο σε ένα TextFrame. |
| [getMarginTop()](#getMarginTop--) | Επιστρέφει ή ορίζει το άνω περιθώριο σε ένα TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Επιστρέφει ή ορίζει το άνω περιθώριο σε ένα TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Επιστρέφει ή ορίζει τον τύπο του κάθετου κειμένου. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Επιστρέφει ή ορίζει τον τύπο του κάθετου κειμένου. |
| [getTextAnchorType()](#getTextAnchorType--) | Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου. |
| [getAnchorCenter()](#getAnchorCenter--) | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. |
| [getFirstColumn()](#getFirstColumn--) | Αποκτά την πρώτη στήλη του κελιού. |
| [getFirstRow()](#getFirstRow--) | Αποκτά την πρώτη σειρά του κελιού. |
| [getColSpan()](#getColSpan--) | Επιστρέφει τον αριθμό των στηλών του πλέγματος στον γονικό πίνακα που θα καλυφθούν από το τρέχον κελί. |
| [getRowSpan()](#getRowSpan--) | Επιστρέφει τον αριθμό των σειρών που καλύπτει ένα συγχωνευμένο κελί. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει το πλαίσιο κειμένου ενός κελιού. |
| [getTable()](#getTable--) | Επιστρέφει το γονικό αντικείμενο Table για ένα κελί. |
| [isMergedCell()](#isMergedCell--) | Επιστρέφει true αν το κελί είναι συγχωνευμένο με κάποιο προσαρμοσμένο κελί, αλλιώς false. |
| [getCellFormat()](#getCellFormat--) | Επιστρέφει το αντικείμενο CellFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτό το κελί. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη στήλης. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη σειράς. |
| [splitByHeight(double height)](#splitByHeight-double-) | Διαιρεί το κελί κατά ύψος. |
| [splitByWidth(double width)](#splitByWidth-double-) | Διαιρεί το κελί κατά πλάτος. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```


Επιστρέφει μια απόσταση από την αριστερή πλευρά ενός πίνακα έως την αριστερή πλευρά ενός κελιού. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```


Επιστρέφει μια απόσταση από την επάνω πλευρά ενός πίνακα έως την επάνω πλευρά ενός κελιού. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```


Επιστρέφει τον δείκτη της πρώτης σειράς που καλύπτεται από το κελί. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```


Επιστρέφει τον δείκτη της πρώτης στήλης που καλύπτεται από το κελί. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Επιστρέφει το πλάτος του κελιού. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Επιστρέφει το ύψος του κελιού. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Επιστρέφει το ελάχιστο ύψος ενός κελιού. Αυτή είναι το άθροισμα των ελάχιστων υψών όλων των σειρών που καλύπτονται από το κελί. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Επιστρέφει ή ορίζει το δεξιό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Επιστρέφει ή ορίζει το δεξιό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Επιστρέφει ή ορίζει το άνω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Επιστρέφει ή ορίζει το άνω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Επιστρέφει ή ορίζει τον τύπο του κάθετου κειμένου. Ανάγνωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Επιστρέφει:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Επιστρέφει ή ορίζει τον τύπο του κάθετου κειμένου. Ανάγνωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```


Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου. Ανάγνωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Επιστρέφει:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```


Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου. Ανάγνωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```


Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```


Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```


Αποκτά την πρώτη στήλη του κελιού. Μόνο για ανάγνωση [IColumn](../../com.aspose.slides/icolumn).

**Επιστρέφει:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```


Αποκτά την πρώτη σειρά του κελιού. Μόνο για ανάγνωση [IRow](../../com.aspose.slides/irow).

**Επιστρέφει:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```


Επιστρέφει τον αριθμό των στηλών του πλέγματος στον γονικό πίνακα που θα καλυφθούν από το τρέχον κελί. Αυτή η ιδιότητα επιτρέπει στα κελιά να εμφανίζονται ως συγχωνευμένα, καθώς καλύπτουν κάθετα τα όρια άλλων κελιών στον πίνακα. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```


Επιστρέφει τον αριθμό των σειρών που καλύπτει ένα συγχωνευμένο κελί. Χρησιμοποιείται σε συνδυασμό με το χαρακτηριστικό vMerge σε άλλα κελιά για τον καθορισμό του αρχικού κελιού μιας οριζόντιας συγχώνευσης. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Επιστρέφει το πλαίσιο κειμένου ενός κελιού. Μόνο για ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```


Επιστρέφει το γονικό αντικείμενο Table για ένα κελί. Μόνο για ανάγνωση [ITable](../../com.aspose.slides/itable).

**Επιστρέφει:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```


Επιστρέφει true αν το κελί είναι συγχωνευμένο με κάποιο προσαρμοσμένο κελί, αλλιώς false. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```


Επιστρέφει το αντικείμενο CellFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτό το κελί. Μόνο για ανάγνωση [ICellFormat](../../com.aspose.slides/icellformat).

**Επιστρέφει:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```


Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη στήλης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης στήλης. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```


Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης σειράς. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```


Διαιρεί το κελί κατά ύψος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| height | double | Ύψος μιας σειράς. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```


Διαιρεί το κελί κατά πλάτος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | double | Πλάτος μιας στήλης. |