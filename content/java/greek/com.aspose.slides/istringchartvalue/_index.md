---
title: IStringChartValue
second_title: Aspose.Slides για Java API Αναφορά
description: Αναπαριστά τιμή συμβολοσειράς η οποία μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1 σε κελί/κελιά του βιβλίου εργασίας που σχετίζονται με το διάγραμμα, 2 ως λεκτική τιμή.
type: docs
url: /el/com.aspose.slides/istringchartvalue/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Αναπαριστά μια τιμή συμβολοσειράς που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με το διάγραμμα· 2) ως λεκτική τιμή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Επιστρέφει ή ορίζει τη λεκτική συμβολοσειρά εάν η ιδιότητα DataSourceType είναι DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Επιστρέφει ή ορίζει τη λεκτική συμβολοσειρά εάν η ιδιότητα DataSourceType είναι DataSourceType.StringLiterals. |
| [toString()](#toString--) | Επιστρέφει την αναπαράσταση της συμβολοσειράς. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Ορίζει την τιμή από το καθορισμένο κελί. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Εάν η ιδιότητα DataSourceType είναι DataSourceType.Worksheet, τότε αυτή η μέθοδος επιστρέφει τη διεύθυνση των κελιών στο βιβλίο εργασίας που αντιπροσωπεύουν τα δεδομένα συμβολοσειράς. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Επιστρέφει ή ορίζει τη λεκτική συμβολοσειρά εάν η ιδιότητα DataSourceType είναι DataSourceType.StringLiterals. Read/write String.

**Επιστρέφει:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Επιστρέφει ή ορίζει τη λεκτική συμβολοσειρά εάν η ιδιότητα DataSourceType είναι DataSourceType.StringLiterals. Read/write String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Επιστρέφει την αναπαράσταση της συμβολοσειράς.

**Επιστρέφει:**
java.lang.String - String representation of a value String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Ορίζει την τιμή από το καθορισμένο κελί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Κελί. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Εάν η ιδιότητα DataSourceType είναι DataSourceType.Worksheet, τότε αυτή η μέθοδος επιστρέφει τη διεύθυνση των κελιών στο βιβλίο εργασίας που αντιπροσωπεύουν τα δεδομένα συμβολοσειράς. Διαφορετικά επιστρέφει κενή συμβολοσειρά.

**Επιστρέφει:**
java.lang.String - String value String