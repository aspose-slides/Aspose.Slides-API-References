---
title: BaseChartValue
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά μια τιμή ενός διαγράμματος.
type: docs
url: /el/com.aspose.slides/basechartvalue/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Αναπαριστά μια τιμή ενός διαγράμματος.
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

Καθορίζει εάν η ιδιότητα AsCell, AsCells, AsLiteralString ή AsLiteralDouble είναι ενεργή σε απογόνους. Σε άλλες λέξεις καθορίζει τον τύπο της τιμής της ιδιότητας Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Για σημεία στη συλλογή ChartDataPointCollection, αυτή η ιδιότητα είναι μόνο-ανάγνωση. Σε αυτήν την περίπτωση, για αλλαγή της τιμής αυτής της ιδιότητας, μπορείτε να χρησιμοποιήσετε μία από τις ιδιότητες ChartDataPointCollection.DataSourceTypeFor<...>.

**Επιστρέφει:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Καθορίζει εάν η ιδιότητα AsCell, AsCells, AsLiteralString ή AsLiteralDouble είναι ενεργή σε απογόνους. Σε άλλες λέξεις καθορίζει τον τύπο της τιμής της ιδιότητας Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Για σημεία στη συλλογή ChartDataPointCollection, αυτή η ιδιότητα είναι μόνο-ανάγνωση. Σε αυτήν την περίπτωση, για αλλαγή της τιμής αυτής της ιδιότητας, μπορείτε να χρησιμοποιήσετε μία από τις ιδιότητες ChartDataPointCollection.DataSourceTypeFor<...>.

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

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject