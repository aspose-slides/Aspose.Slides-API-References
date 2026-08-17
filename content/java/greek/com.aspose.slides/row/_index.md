---
title: Row
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει μια γραμμή σε έναν πίνακα.
type: docs
url: /el/com.aspose.slides/row/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Αντιπροσωπεύει μια γραμμή σε έναν πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος μιας γραμμής. |
| [getMinimalHeight()](#getMinimalHeight--) | Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Επιστρέφει ή ορίζει το ελάχιστο δυνατό ύψος μιας γραμμής. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης τμημάτων σε όλα τα τμήματα των κελιών της γραμμής. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης παραγράφων σε όλα τα παραγράφους των κελιών της γραμμής. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης πλαισίων κειμένου σε όλα τα πλαίσια κειμένου των κελιών της γραμμής. |
| [getRowFormat()](#getRowFormat--) | Επιστρέφει το αντικείμενο RowFormat που περιέχει ιδιότητες μορφοποίησης για αυτήν τη γραμμή. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Επιστρέφει το ύψος μιας γραμμής. Μόνο για ανάγνωση double.

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


Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης τμημάτων σε όλα τα τμήματα των κελιών της γραμμής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης παραγράφων σε όλα τα παραγράφους των κελιών της γραμμής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης πλαισίων κειμένου σε όλα τα πλαίσια κειμένου των κελιών της γραμμής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


Επιστρέφει το αντικείμενο RowFormat που περιέχει ιδιότητες μορφοποίησης για αυτήν τη γραμμής. Μόνο για ανάγνωση [IRowFormat](../../com.aspose.slides/irowformat).

**Επιστρέφει:**
[IRowFormat](../../com.aspose.slides/irowformat)