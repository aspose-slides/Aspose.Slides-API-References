---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά τιμή τύπου string ή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζεται με το γράφημα· 2) ως κυριολεκτική τιμή.
type: docs
url: /el/com.aspose.slides/istringordoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Αναπαριστά τιμή τύπου string ή double που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζεται με το γράφημα· 2) ως κυριολεκτική τιμή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Επιστρέφει ή ορίζει τη κυριολεκτική συμβολοσειρά εάν η ιδιότητα DataSourceType είναι DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Επιστρέφει ή ορίζει τη κυριολεκτική συμβολοσειρά εάν η ιδιότητα DataSourceType είναι DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Επιστρέφει ή ορίζει το κυριολεκτικό double εάν η ιδιότητα DataSourceType είναι DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Επιστρέφει ή ορίζει το κυριολεκτικό double εάν η ιδιότητα DataSourceType είναι DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Μετατρέπει την τιμή σε double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Επιστρέφει ή ορίζει τη κυριολεκτική συμβολοσειρά εάν η ιδιότητα DataSourceType είναι DataSourceType.StringLiterals. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Επιστρέφει ή ορίζει τη κυριολεκτική συμβολοσειρά εάν η ιδιότητα DataSourceType είναι DataSourceType.StringLiterals. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Επιστρέφει ή ορίζει το κυριολεκτικό double εάν η ιδιότητα DataSourceType είναι DataSourceType.DoubleLiterals. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Επιστρέφει ή ορίζει το κυριολεκτικό double εάν η ιδιότητα DataSourceType είναι DataSourceType.DoubleLiterals. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Μετατρέπει την τιμή σε double.

**Επιστρέφει:**
double - Double value double