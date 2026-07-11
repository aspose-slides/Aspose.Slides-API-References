---
title: Row
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια γραμμή σε έναν πίνακα.
type: docs
url: /el/com.aspose.slides/row/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Αναπαριστά μια γραμμή σε έναν πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος μιας γραμμής. |
| [getMinimalHeight()](#getMinimalHeight--) | Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ορίζει καθορισμένες ιδιότητες μορφοποίησης τμημάτων σε όλα τα τμήματα των κελιών της γραμμής. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ορίζει καθορισμένες ιδιότητες μορφοποίησης παραγράφων σε όλα τα κελιά της γραμμής. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ορίζει καθορισμένες ιδιότητες μορφοποίησης πλαισίων κειμένου σε όλα τα πλαίσια κειμένου των κελιών της γραμμής. |
| [getRowFormat()](#getRowFormat--) | Επιστρέφει το αντικείμενο RowFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτήν τη γραμμή. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Επιστρέφει το ύψος μιας γραμμής. Μόνο ανάγνωση double.

**Επιστρέφει:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Ορίζει καθορισμένες ιδιότητες μορφοποίησης τμημάτων σε όλα τα τμήματα των κελιών της γραμμής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | αντικείμενο IPortionFormat με τις απαραίτητες ιδιότητες ορισμένες. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Ορίζει καθορισμένες ιδιότητες μορφοποίησης παραγράφων σε όλα τα κελιά της γραμμής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | αντικείμενο IParagraphFormat με τις απαραίτητες ιδιότητες ορισμένες. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

Ορίζει καθορισμένες ιδιότητες μορφοποίησης πλαισίων κειμένου σε όλα τα πλαίσια κειμένου των κελιών της γραμμής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | αντικείμενο ITextFrameFormat με τις απαραίτητες ιδιότητες ορισμένες. |
### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Επιστρέφει το αντικείμενο RowFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτήν τη γραμμή. Μόνο ανάγνωση [IRowFormat](../../com.aspose.slides/irowformat).

**Επιστρέφει:**
[IRowFormat](../../com.aspose.slides/irowformat)