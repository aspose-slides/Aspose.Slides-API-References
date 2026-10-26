---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Represents chart categories.
type: docs
url: /el/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Αντιπροσωπεύει τις κατηγορίες του διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getUseCell()](#getUseCell--) | Αν true τότε η ιδιότητα AsCell είναι ενεργή. |
| [getAsCell()](#getAsCell--) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Επιστρέφει ή ορίζει AsLiteral εάν το UseCell είναι false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Επιστρέφει ή ορίζει AsLiteral εάν το UseCell είναι false. |
| [getValue()](#getValue--) | Εάν το UseCell είναι true, αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Εάν το UseCell είναι true, αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Διαχειριζόμενος container των τιμών των επιπέδων ομαδοποίησης της κατηγορίας του διαγράμματος. |
| [remove()](#remove--) | Αφαιρεί την κατηγορία από το διάγραμμα. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Αν true τότε η ιδιότητα AsCell είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας χρησιμοποιείται για την αποθήκευση της κατηγορίας (αυτή η περίπτωση υποστηρίζει κατηγορία πολλαπλών επιπέδων). Αν false τότε η ιδιότητα AsLiteral είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για την αποθήκευση της κατηγορίας (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Μόνο-ανάγνωση boolean.

--------------------

Για αλλαγή τιμής αυτής της ιδιότητας (για όλες τις κατηγορίες στη συλλογή) ορίστε τη νέα τιμή στην ιδιότητα [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Επιστρέφει:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Εάν η κατηγορία είναι πολλαπλών επιπέδων, χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Εάν η κατηγορία είναι πολλαπλών επιπέδων, χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Επιστρέφει ή ορίζει AsLiteral εάν το UseCell είναι false. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Επιστρέφει ή ορίζει AsLiteral εάν το UseCell είναι false. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Εάν το UseCell είναι true, αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Εάν το UseCell είναι false, αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Εάν το UseCell είναι true, αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Εάν το UseCell είναι false, αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Διαχειριζόμενος container των τιμών των επιπέδων ομαδοποίησης της κατηγορίας του διαγράμματος. Η κατηγορία πολλαπλών επιπέδων περιέχει περισσότερα από ένα επίπεδο ομαδοποίησης. Η αρίθμηση των επιπέδων ομαδοποίησης είναι μηδενική. Μόνο-ανάγνωση [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Επιστρέφει:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Αφαιρεί την κατηγορία από το διάγραμμα.