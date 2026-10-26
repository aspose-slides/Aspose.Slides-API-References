---
title: DoubleChartValue
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τιμή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με το γράφημα 2) ως κυριολεκτική τιμή.
type: docs
url: /el/com.aspose.slides/doublechartvalue/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Αναπαριστά τιμή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με το γράφημα· 2) ως κυριολεκτική τιμή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returns or sets chart data cell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets chart data cell. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets value as literal double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets value as literal double. |
| [getData()](#getData--) | Returns or sets Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returns or sets Data object. |
| [toDouble()](#toDouble--) | Converts to double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Επιστρέφει ή ορίζει το κελί δεδομένων του γραφήματος. Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Επιστρέφει ή ορίζει το κελί δεδομένων του γραφήματος. Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Επιστρέφει ή ορίζει την τιμή ως κυριολεκτικό double. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Επιστέψει ή ορίζει την τιμή ως κυριολεκτικό double. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


Επιστρέφει ή ορίζει το αντικείμενο Data. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Επιστρέφει ή ορίζει το αντικείμενο Data. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Μετατρέπει σε double.

**Επιστρέφει:**
double - Επιστρέφει LiteralDouble εάν το DataSourceType ισούται με DoubleLiterals. Εάν το DataSourceType ισούται με Worksheet, επιστρέφει την τιμή κελιού που μετατράπηκε επιτυχώς σε double, διαφορετικά επιστρέφει NaN.