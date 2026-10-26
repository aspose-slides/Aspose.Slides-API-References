---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a value of a chart.
type: docs
url: /el/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Αντιπροσωπεύει μια τιμή ενός διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή. |
| [getData()](#getData--) | Ανάγνωση/εγγραφή Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Ανάγνωση/εγγραφή Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας Data. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Για την αλλαγή της τιμής αυτής της ιδιότητας μπορείτε να χρησιμοποιήσετε μια από τις ιδιότητες ChartDataPointCollection.DataSourceTypeFor<...>. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Επιστρέφει:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας Data. Αυτή η ιδιότητα είναι μόνο για ανάγνωση. Για την αλλαγή της τιμής αυτής της ιδιότητας μπορείτε να χρησιμοποιήσετε μια από τις ιδιότητες ChartDataPointCollection.DataSourceTypeFor<...>. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |