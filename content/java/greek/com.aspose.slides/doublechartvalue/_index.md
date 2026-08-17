---
title: DoubleChartValue
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά τιμή double η οποία μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με το γράφημα 2) ως κυριολεκτική τιμή.
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

Αντιπροσωπεύει τιμή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με το γράφημα· 2) ως κυριολεκτική τιμή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsCell()](#getAsCell--) | Επιστρέφει ή ορίζει το κελί δεδομένων γραφήματος. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Επιστρέφει ή ορίζει το κελί δεδομένων γραφήματος. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Επιστρέφει ή ορίζει την τιμή ως κυριολεκτικό double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Επιστρέφει ή ορίζει την τιμή ως κυριολεκτικό double. |
| [getData()](#getData--) | Επιστρέφει ή ορίζει το αντικείμενο Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Επιστρέφει ή ορίζει το αντικείμενο Data. |
| [toDouble()](#toDouble--) | Μετατρέπει σε double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Επιστρέφει ή ορίζει το κελί δεδομένων γραφήματος. Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Επιστρέφει ή ορίζει το κελί δεδομένων γραφήματος. Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

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

Επιστρέφει ή ορίζει την τιμή ως κυριολεκτικό double. Ανάγνωση/εγγραφή double.

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
double - Επιστρέφει LiteralDouble εάν DataSourceType ισούται με DoubleLiterals. Εάν DataSourceType ισούται με Worksheet επιστρέφει επιτυχώς τη μετατρεπόμενη σε double τιμή κελιού, διαφορετικά επιστρέφει NaN.