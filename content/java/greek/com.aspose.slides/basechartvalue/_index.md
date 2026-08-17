---
title: BaseChartValue
second_title: Aspose.Slides για την Αναφορά API Java
description: Αναπαριστά μια τιμή διαγράμματος.
type: docs
url: /el/com.aspose.slides/basechartvalue/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Αναπαριστά μια τιμή διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Καθορίζει εάν η ιδιότητα AsCell, AsCells, AsLiteralString ή AsLiteralDouble είναι ενεργή σε απογόνους. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Καθορίζει εάν η ιδιότητα AsCell, AsCells, AsLiteralString ή AsLiteralDouble είναι ενεργή σε απογόνους. |
| [getData()](#getData--) | Δεδομένα. |
| [setData(Object value)](#setData-java.lang.Object-) | Δεδομένα. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Καθορίζει εάν η ιδιότητα AsCell, AsCells, AsLiteralString ή AsLiteralDouble είναι ενεργή σε απογόνους. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Για σημεία στο ChartDataPointCollection η ιδιότητα αυτή είναι μόνο για ανάγνωση. Σε αυτήν τη περίπτωση για την αλλαγή τιμής της ιδιότητας μπορείτε να χρησιμοποιήσετε μία από τις ιδιότητες ChartDataPointCollection.DataSourceTypeFor<...>.

**Επιστρέφει:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Καθορίζει εάν η ιδιότητα AsCell, AsCells, AsLiteralString ή AsLiteralDouble είναι ενεργή σε απογόνους. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Για σημεία στο ChartDataPointCollection η ιδιότητα αυτή είναι μόνο για ανάγνωση. Σε αυτήν τη περίπτωση για την αλλαγή τιμής της ιδιότητας μπορείτε να χρησιμοποιήσετε μία από τις ιδιότητες ChartDataPointCollection.DataSourceTypeFor<...>.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

Δεδομένα. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Δεδομένα. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject