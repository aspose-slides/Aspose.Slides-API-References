---
title: StringOrDoubleChartValue
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά τιμή συμβολοσειράς ή δεκαδικού αριθμού που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά φύλλου εργασίας που σχετίζονται με το διάγραμμα· 2) ως κυριολεκτική τιμή.
type: docs
url: /el/com.aspose.slides/stringordoublechartvalue/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Αναπαριστά τιμή συμβολοσειράς ή δεκαδικού αριθμού που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του βιβλίου εργασίας που σχετίζονται με το διάγραμμα· 2) ως κυριολεκτική τιμή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returns or sets chart data cell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets chart data cell. |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets value as literal string. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets value as literal string. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets value as literal double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets value as literal double. |
| [getData()](#getData--) | Returns or sets Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returns or sets Data object. |
| [toDouble()](#toDouble--) | Converts to double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

**Επιστρέφει ή ορίζει το κελί δεδομένων του διαγράμματος.** Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

**Επιστρέφει ή ορίζει το κελί δεδομένων του διαγράμματος.** Ανάγνωση/εγγραφή [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

**Επιστρέφει ή ορίζει τιμή ως κυριολεκτική συμβολοσειρά.** Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

**Επιστρέφει ή ορίζει τιμή ως κυριολεκτική συμβολοσειρά.** Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

**Επιστρέφει ή ορίζει τιμή ως κυριολεκτικό δεκαδικό.** Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

**Επιστρέφει ή ορίζει τιμή ως κυριολεκτικό δεκαδικό.** Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

**Επιστρέφει ή ορίζει αντικείμενο Data.** Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

**Επιστρέφει ή ορίζει αντικείμενο Data.** Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

**Μετατρέπει σε δεκαδικό.**

**Επιστρέφει:**
double - Double value.