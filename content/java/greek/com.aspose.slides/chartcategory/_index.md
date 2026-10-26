---
title: ChartCategory
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεί τις κατηγορίες γραφήματος.
type: docs
url: /el/com.aspose.slides/chartcategory/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Αντιπροσωπεί τις κατηγορίες γραφήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getUseCell()](#getUseCell--) | Αν είναι true τότε η ιδιότητα AsCell είναι ενεργή. |
| [getAsCell()](#getAsCell--) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Επιστρέφει ή ορίζει το αντικείμενο AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Επιστρέφει ή ορίζει το αντικείμενο AsLiteral. |
| [getValue()](#getValue--) | Αν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Αν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Διαχειριζόμενο κοντέινερ των τιμών των επιπέδων ομαδοποίησης κατηγοριών γραφήματος. |
| [remove()](#remove--) | Αφαιρεί την κατηγορία από το γράφημα. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Αν είναι true τότε η ιδιότητα AsCell είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας χρησιμοποιείται για την αποθήκευση της κατηγορίας (αυτή η περίπτωση υποστηρίζει κατηγορία πολλαπλών επιπέδων). Αν είναι false τότε η ιδιότητα AsLiteral είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για την αποθήκευση της κατηγορίας (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Μόνο για ανάγνωση boolean.

--------------------

Για να αλλάξετε την τιμή αυτής της ιδιότητας (για όλες τις κατηγορίες στη συλλογή) ορίστε τη νέα τιμή στην ιδιότητα ChartCategoryCollection.UseCells property.

**Returns:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Αν η κατηγορία είναι πολλαπλού επιπέδου τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Αν/γρ [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Αν η κατηγορία είναι πολλαπλού επιπέδου τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Αν/γρ [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Επιστρέφει ή ορίζει το αντικείμενο AsLiteral. Αν/γρ Object.

**Returns:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Επιστρέφει ή ορίζει το αντικείμενο AsLiteral. Αν/γρ Object.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

Αν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Αν το UseCell είναι false τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Αν/γρ Object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Αν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Αν το UseCell είναι false τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Αν/γρ Object.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Διαχειριζόμενο κοντέινερ των τιμών των επιπέδων ομαδοποίησης κατηγοριών γραφήματος. Η κατηγορία πολλαπλών επιπέδων περιέχει περισσότερα από ένα επίπεδο ομαδοποίησης. Η αρίθμηση των επιπέδων ομαδοποίησης αρχίζει από το μηδέν. Μόνο για ανάγνωση [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Returns:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Αφαιρεί την κατηγορία από το γράφημα.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject