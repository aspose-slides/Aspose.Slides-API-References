---
title: Column
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά μια στήλη σε έναν πίνακα.
type: docs
url: /el/com.aspose.slides/column/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Αναπαριστά μια στήλη σε έναν πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWidth()](#getWidth--) | Επιστρέφει ή ορίζει το πλάτος μιας στήλης. |
| [setWidth(double value)](#setWidth-double-) | Επιστρέφει ή ορίζει το πλάτος μιας στήλης. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Ορίζει καθορισμένες ιδιότητες μορφοποίησης τμημάτων σε όλα τα τμήματα των κελιών της στήλης. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Ορίζει καθορισμένες ιδιότητες μορφοποίησης παραγράφου σε όλες τις παραγράφους των κελιών της στήλης. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Ορίζει καθορισμένες ιδιότητες μορφοποίησης πλαισίου κειμένου σε όλα τα πλαίσια κειμένου των κελιών της στήλης. |
| [getColumnFormat()](#getColumnFormat--) | Επιστρέφει το αντικείμενο ColumnFormat που περιέχει ιδιότητες μορφοποίησης για αυτή τη στήλη. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Επιστρέφει ή ορίζει το πλάτος μιας στήλης. Αναγνώσιμη/εγγράψιμη double.

**Επιστρέφει:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Επιστρέφει ή ορίζει το πλάτος μιας στήλης. Αναγνώσιμη/εγγράψιμη double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Ορίζει καθορισμένες ιδιότητες μορφοποίησης τμημάτων σε όλα τα τμήματα των κελιών της στήλης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Ορίζει καθορισμένες ιδιότητες μορφοποίησης παραγράφου σε όλες τις παραγράφους των κελιών της στήλης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```


Ορίζει καθορισμένες ιδιότητες μορφοποίησης πλαισίου κειμένου σε όλα τα πλαίσια κειμένου των κελιών της στήλης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Επιστρέφει το αντικείμενο ColumnFormat που περιέχει ιδιότητες μορφοποίησης για αυτή τη στήλη. Μόνο ανάγνωση [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Επιστρέφει:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)