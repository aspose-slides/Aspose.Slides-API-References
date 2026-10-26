---
title: IDoubleChartValue
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά τιμή double η οποία μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του βιβλίου εργασίας που σχετίζονται με το γράφημα, 2) ως κυριολεξική τιμή.
type: docs
url: /el/com.aspose.slides/idoublechartvalue/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Αναπαριστά τιμή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με το γράφημα· 2) ως κυριολεξική τιμή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Επιστρέφει ή ορίζει κυριολεξική τιμή double εάν DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Επιστρέφει ή ορίζει κυριολεξική τιμή double εάν DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Μετατρέπει σε double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Επιστρέφει ή ορίζει κυριολεξική τιμή double εάν DataSourceType = Charts.DataSourceType.DoubleLiterals. double με δυνατότητα ανάγνωσης/εγγραφής.

**Επιστρέφει:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Επιστρέφει ή ορίζει κυριολεξική τιμή double εάν DataSourceType = Charts.DataSourceType.DoubleLiterals. double με δυνατότητα ανάγνωσης/εγγραφής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Μετατρέπει σε double.

**Επιστρέφει:**
double - Τιμή double.