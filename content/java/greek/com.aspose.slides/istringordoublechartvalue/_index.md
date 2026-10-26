---
title: IStringOrDoubleChartValue
second_title: "Aspose.Slides για την Java API Αναφορά"
description: "Αντιπροσωπεύει τιμή τύπου string ή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με διάγραμμα· 2) ως κυριολεκτική τιμή."
type: docs
url: /el/com.aspose.slides/istringordoublechartvalue/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Αντιπροσωπεύει τιμή τύπου string ή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με διάγραμμα· 2) ως κυριολεκτική τιμή.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converts value to double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Μετατρέπει την τιμή σε double.

**Επιστρέφει:**
double - Τιμή double