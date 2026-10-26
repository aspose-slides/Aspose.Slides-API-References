---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Αντιπροσωπεύει τις κατηγορίες διαγραμμάτων.
type: docs
url: /el/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Αντιπροσωπεύει τις κατηγορίες διαγραμμάτων.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getUseCell()](#getUseCell--) | Εάν είναι true, τότε η ιδιότητα AsCell είναι ενεργή. |
| [getAsCell()](#getAsCell--) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Επιστρέφει ή ορίζει το AsLiteral εάν το UseCell είναι false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Επιστρέφει ή ορίζει το AsLiteral εάν το UseCell είναι false. |
| [getValue()](#getValue--) | Εάν το UseCell είναι true, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Εάν το UseCell είναι true, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Διαχειριζόμενος κοντέινερ των τιμών των επιπέδων ομαδοποίησης της κατηγορίας διαγράμματος. |
| [remove()](#remove--) | Καταργεί την κατηγορία από το διάγραμμα. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Εάν είναι true, τότε η ιδιότητα AsCell είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας χρησιμοποιείται για την αποθήκευση της κατηγορίας (αυτή η περίπτωση υποστηρίζει πολυεπίπεδη κατηγορία). Εάν είναι false, τότε η ιδιότητα AsLiteral είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για την αποθήκευση της κατηγορίας (και αυτή η περίπτωση δεν υποστηρίζει πολυεπίπεδες κατηγορίες). Μόνο για ανάγνωση boolean.

--------------------

Για να αλλάξετε την τιμή αυτής της ιδιότητας (για όλες τις κατηγορίες στη συλλογή) ορίστε τη νέα τιμή στην ιδιότητα [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Επιστρέφει:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Εάν η κατηγορία είναι πολυεπίπεδη, τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Ανάγνωση/Εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Εάν η κατηγορία είναι πολυεπίπεδη, τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Ανάγνωση/Εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Επιστρέφει ή ορίζει το AsLiteral εάν το UseCell είναι false. Ανάγνωση/Εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Επιστρέφει ή ορίζει το AsLiteral εάν το UseCell είναι false. Ανάγνωση/Εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Εάν το UseCell είναι true, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Εάν το UseCell είναι false, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/Εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Εάν το UseCell είναι true, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Εάν το UseCell είναι false, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/Εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Διαχειριζόμενος κοντέινερ των τιμών των επιπέδων ομαδοποίησης της κατηγορίας διαγράμματος. Η πολυεπίπεδη κατηγορία περιέχει περισσότερα από ένα επίπεδο ομαδοποίησης. Η αρίθμηση των επιπέδων ομαδοποίησης ξεκινά από το μηδέν. Μόνο για ανάγνωση [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Επιστρέφει:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Καταργεί την κατηγορία από το διάγραμμα.