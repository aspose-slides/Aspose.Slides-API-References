---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Represents chart categories.
type: docs
url: /el/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Αντιπροσωπεύει τις κατηγορίες διαγραμμάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getUseCell()](#getUseCell--) | Αν είναι true, τότε η ιδιότητα AsCell είναι η ενεργή. |
| [getAsCell()](#getAsCell--) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Επιστρέφει ή ορίζει το AsLiteral εάν το UseCell είναι false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Επιστρέφει ή ορίζει το AsLiteral εάν το UseCell είναι false. |
| [getValue()](#getValue--) | Αν το UseCell είναι true, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Αν το UseCell είναι true, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. |
| [getCachedValue()](#getCachedValue--) | Αποκτά την αποθηκευμένη τιμή μιας κατηγορίας διαγράμματος. |
| [getGroupingLevels()](#getGroupingLevels--) | Διαχειριζόμενο κοντέινερ των τιμών των επιπέδων ομαδοποίησης κατηγοριών διαγράμματος. |
| [remove()](#remove--) | Αφαιρεί την κατηγορία από το διάγραμμα. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Αν είναι true, τότε η ιδιότητα AsCell είναι η ενεργή. Με άλλα λόγια, το worksheet χρησιμοποιείται για την αποθήκευση της κατηγορίας (αυτή η περίπτωση υποστηρίζει κατηγορία πολλαπλών επιπέδων). Αν είναι false, τότε η ιδιότητα AsLiteral είναι η ενεργή. Με άλλα λόγια, το worksheet ΔΕΝ χρησιμοποιείται για την αποθήκευση της κατηγορίας (και αυτή η περίπτωση δεν υποστηρίζει κατηγορίες πολλαπλών επιπέδων). Μόνο για ανάγνωση boolean.

--------------------

Για αλλαγή της τιμής αυτής της ιδιότητας (για όλες τις κατηγορίες στη συλλογή) ορίστε τη νέα τιμή στην ιδιότητα [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Επιστρέφει:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Εάν η κατηγορία είναι πολυεπίπεδη, τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell. Εάν η κατηγορία είναι πολυεπίπεδη, τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Επιστρέφει ή ορίζει το AsLiteral εάν το UseCell είναι false. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Επιστρέφει ή ορίζει το AsLiteral εάν το UseCell είναι false. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Αν το UseCell είναι true, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Αν το UseCell είναι false, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Αν το UseCell είναι true, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Αν το UseCell είναι false, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Αποκτά την αποθηκευμένη τιμή μιας κατηγορίας διαγράμματος. Μόνο για ανάγνωση [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Εκτυπώστε όλες τις αποθηκευμένες τιμές κατηγορίας διαγράμματος.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Διαχειριζόμενο κοντέινερ των τιμών των επιπέδων ομαδοποίησης κατηγοριών διαγράμματος. Κατηγορία πολλαπλών επιπέδων περιέχει περισσότερα από ένα επίπεδο ομαδοποίησης. Η αρίθμηση των επιπέδων ομαδοποίησης είναι μηδενική. Μόνο για ανάγνωση [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Επιστρέφει:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Αφαιρεί την κατηγορία από το διάγραμμα.