---
title: IDoubleChartValue
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά τιμή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κυψέλη/κυψέλες του φύλλου εργασίας που σχετίζεται με το διάγραμμα· 2) ως κυριολεκτική τιμή.
type: docs
url: /el/com.aspose.slides/idoublechartvalue/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Αντιπροσωπεύει τιμή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κυψέλη/κυψέλες του φύλλου εργασίας που σχετίζεται με το διάγραμμα· 2) ως κυριολεκτική τιμή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Επιστρέφει ή ορίζει την κυριολεκτική τιμή double εάν DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Επιστρέφει ή ορίζει την κυριολεκτική τιμή double εάν DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Μετατρέπει σε double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Επιστρέφει ή ορίζει την κυριολεκτική τιμή double εάν DataSourceType = Charts.DataSourceType.DoubleLiterals. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Επιστρέφει ή ορίζει την κυριολεκτική τιμή double εάν DataSourceType = Charts.DataSourceType.DoubleLiterals. Ανάγνωση/εγγραφή double.

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
double - Τιμή Double.