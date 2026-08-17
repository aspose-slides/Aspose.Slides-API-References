---
title: Cell
second_title: Aspose.Slides για το Java API Αναφορά
description: Αντιπροσωπεύει ένα κελί ενός πίνακα.
type: docs
url: /el/com.aspose.slides/cell/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Ανταποκρίνεται σε ένα κελί πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Επιστρέφει μια απόσταση από την αριστερή πλευρά ενός πίνακα στην αριστερή πλευρά ενός κελιού. |
| [getOffsetY()](#getOffsetY--) | Επιστρέφει μια απόσταση από την άνω πλευρά ενός πίνακα στην άνω πλευρά ενός κελιού. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Επιστρέφει έναν δείκτη της πρώτης γραμμής που καλύπτεται από το κελί. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Επιστρέφει έναν δείκτη της πρώτης στήλης που καλύπτεται από το κελί. |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος του κελιού. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος του κελιού. |
| [getMinimalHeight()](#getMinimalHeight--) | Επιστρέφει το ελάχιστο ύψος ενός κελιού. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε ένα TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε ένα TextFrame. |
| [getMarginTop()](#getMarginTop--) | Επιστρέφει ή ορίζει το επάνω περιθώριο σε ένα TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Επιστρέφει ή ορίζει το επάνω περιθώριο σε ένα TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Επιστρέφει ή ορίζει τον τύπο του κάθετου κειμένου. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Επιστρέφει ή ορίζει τον τύπο του κάθετου κειμένου. |
| [getTextAnchorType()](#getTextAnchorType--) | Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου. |
| [getAnchorCenter()](#getAnchorCenter--) | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. |
| [getFirstRow()](#getFirstRow--) | Λαμβάνει την πρώτη γραμμή του κελιού. |
| [getFirstColumn()](#getFirstColumn--) | Λαμβάνει την πρώτη στήλη του κελιού. |
| [getColSpan()](#getColSpan--) | Επιστρέφει τον αριθμό των στηλών του πλέγματος στον γονικό πίνακα που θα καλυφθούν από το τρέχον κελί. |
| [getRowSpan()](#getRowSpan--) | Επιστρέφει τον αριθμό των γραμμών που καλύπτει ένα συγχωνευμένο κελί. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει το πλαίσιο κειμένου ενός κελιού. |
| [getTable()](#getTable--) | Επιστρέφει το αντικείμενο Table γονέα για ένα κελί. |
| [isMergedCell()](#isMergedCell--) | Επιστρέφει true εάν το κελί είναι συγχωνευμένο με οποιοδήποτε προσαρμοσμένο κελί, διαφορετικά false. |
| [getCellFormat()](#getCellFormat--) | Επιστρέφει το αντικείμενο CellFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτό το κελί. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη της στήλης. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη της γραμμής. |
| [splitByHeight(double height)](#splitByHeight-double-) | Διαιρεί το κελί κατά ύψος. |
| [splitByWidth(double width)](#splitByWidth-double-) | Διαιρεί το κελί κατά πλάτος. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός κελιού. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός κελιού. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Επιστρέφει μια απόσταση από την αριστερή πλευρά ενός πίνακα στην αριστερή πλευρά ενός κελιού. Μόνο-ανάγνωση double.

**Επιστρέφει:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Επιστρέφει μια απόσταση από την άνω πλευρά ενός πίνακα στην άνω πλευρά ενός κελιού. Μόνο-ανάγνωση double.

**Επιστρέφει:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Επιστρέφει έναν δείκτη της πρώτης γραμμής που καλύπτεται από το κελί. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Επιστρέφει έναν δείκτη της πρώτης στήλης που καλύπτεται από το κελί. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Επιστρέφει το πλάτος του κελιού. Μόνο-ανάγνωση double.

**Επιστρέφει:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Επιστρέφει το ύψος του κελιού. Μόνο-ανάγνωση double.

**Επιστρέφει:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Επιστρέφει το ελάχιστο ύψος ενός κελιού. Αυτό είναι το άθροισμα των ελάχιστων υψών όλων των γραμμών που καλύπτονται από το κελί. Μόνο-ανάγνωση double.

**Επιστρέφει:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Επιστρέφει ή ορίζει το δεξί περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Επιστρέφει ή ορίζει το δεξί περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Επιστρέφει ή ορίζει το επάνω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Επιστρέφει ή ορίζει το επάνω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Επιστρέφει ή ορίζει τον τύπο του κάθετου κειμένου. Ανάγνωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Επιστρέφει:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο του κάθετου κειμένου. Ανάγνωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου. Ανάγνωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Επιστρέφει:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου. Ανάγνωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Λαμβάνει την πρώτη γραμμή του κελιού. Μόνο-ανάγνωση [IRow](../../com.aspose.slides/irow).

**Επιστρέφει:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Λαμβάνει την πρώτη στήλη του κελιού. Μόνο-ανάγνωση [IColumn](../../com.aspose.slides/icolumn).

**Επιστρέφει:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Επιστρέφει τον αριθμό των στηλών του πλέγματος στον γονικό πίνακα που θα καλυφθούν από το τρέχον κελί. Αυτή η ιδιότητα επιτρέπει στα κελιά να έχουν την εμφάνιση συγχώνευσης, καθώς καλύπτουν κάθετα τα σύνορα άλλων κελιών στον πίνακα. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Επιστρέφει τον αριθμό των γραμμών που καλύπτει ένα συγχωνευμένο κελί. Αυτό χρησιμοποιείται σε συνδυασμό με το χαρακτηριστικό vMerge σε άλλα κελιά ώστε να προσδιοριστεί το αρχικό κελί μιας οριζόντιας συγχώνευσης. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Επιστρέφει το πλαίσιο κειμένου ενός κελιού. Μόνο-ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Επιστρέφει το αντικείμενο Table γονέα για ένα κελί. Μόνο-ανάγνωση [ITable](../../com.aspose.slides/itable).

**Επιστρέφει:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Επιστρέφει true εάν το κελί είναι συγχωνευμένο με οποιοδήποτε προσαρμοσμένο κελί, διαφορετικά false. Μόνο-ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Επιστρέφει το αντικείμενο CellFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτό το κελί. Μόνο-ανάγνωση [ICellFormat](../../com.aspose.slides/icellformat).

**Επιστρέφει:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη της στήλης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της στήλης. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη της γραμμής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της γραμμής. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Διαιρεί το κελί κατά ύψος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| height | double | Ύψος μιας γραμμής. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Διαιρεί το κελί κατά πλάτος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | double | Πλάτος μιας στήλης. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη γονική διαφάνεια ενός κελιού. Μόνο-ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση ενός κελιού. Μόνο-ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject