---
title: ChartCategory
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει τις κατηγορίες του διαγράμματος.
type: docs
url: /el/com.aspose.slides/chartcategory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Αντιπροσωπεύει κατηγορίες διαγράμματος.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | Αν είναι true τότε η ιδιότητα AsCell είναι ενεργή. |
| [getAsCell()](#getAsCell--) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Επιστρέφει ή ορίζει το αντικείμενο AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Επιστρέφει ή ορίζει το αντικείμενο AsLiteral. |
| [getValue()](#getValue--) | Αν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Αν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Διαχειριζόμενος container των τιμών των επιπέδων ομαδοποίησης κατηγοριών διαγράμματος. |
| [getCachedValue()](#getCachedValue--) | Λαμβάνει την αποθηκευμένη τιμή μιας κατηγορίας διαγράμματος. |
| [remove()](#remove--) | Αφαιρεί την κατηγορία από το διάγραμμα. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Αν είναι true τότε η ιδιότητα AsCell είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας χρησιμοποιείται για την αποθήκευση της κατηγορίας (αυτή η περίπτωση υποστηρίζει κατηγορία πολλαπλών επιπέδων). Αν είναι false τότε η ιδιότητα AsLiteral είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για την αποθήκευση της κατηγορίας (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Μόνο για ανάγνωση boolean.

--------------------

Για να αλλάξετε την τιμή αυτής της ιδιότητας (για όλες τις κατηγορίες στη συλλογή) ορίστε τη νέα τιμή στην ιδιότητα ChartCategoryCollection.UseCells.

**Επιστρέφει:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Αν η κατηγορία είναι πολυεπίπεδη τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Αν η κατηγορία είναι πολυεπίπεδη τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Επιστρέφει ή ορίζει το αντικείμενο AsLiteral. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Επιστρέφει ή ορίζει το αντικείμενο AsLiteral. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Αν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Αν το UseCell είναι false τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Αν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Αν το UseCell είναι false τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Διαχειριζόμενος container των τιμών των επιπέδων ομαδοποίησης κατηγοριών διαγράμματος. Η κατηγορία πολλαπλών επιπέδων περιέχει περισσότερα από ένα επίπεδο ομαδοποίησης. Η αρίθμηση των επιπέδων ομαδοποίησης είναι μηδενική. Μόνο για ανάγνωση [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Επιστρέφει:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Λαμβάνει την αποθηκευμένη τιμή μιας κατηγορίας διαγράμματος. Μόνο για ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Εκτυπώνει όλες τις αποθηκευμένες τιμές των κατηγοριών του διαγράμματος.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### remove() {#remove--}
```
public final void remove()
```

Αφαιρεί την κατηγορία από το διάγραμμα.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject