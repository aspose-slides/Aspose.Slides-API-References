---
title: StringChartValue
second_title: Aspose.Slides για το Java - Αναφορά API
description: Αναπαριστά την τιμή κειμένου που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του βιβλίου εργασίας σχετικού με το γράφημα 2) ως κυριολεκτική τιμή.
type: docs
url: /el/com.aspose.slides/stringchartvalue/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Αναπαριστά τιμή κειμένου που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του βιβλίου εργασίας σχετικού με το γράφημα· 2) ως κυριολεκτική τιμή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsCells()](#getAsCells--) | Δεν επιτρέπεται η ανάθεση τιμής null. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Δεν επιτρέπεται η ανάθεση τιμής null. |
| [getAsLiteralString()](#getAsLiteralString--) | Επιστρέφει ή ορίζει την τιμή ως κυριολεκτική συμβολοσειρά. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Επιστρέφει ή ορίζει την τιμή ως κυριολεκτική συμβολοσειρά. |
| [getData()](#getData--) | Επιστρέφει ή ορίζει αντικείμενο Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Επιστρέφει ή ορίζει αντικείμενο Data. |
| [toString()](#toString--) | Επιστρέφει δεδομένα τιμής συμβολοσειράς. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Ορίζει την τιμή από το καθορισμένο κελί. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Εάν η ιδιότητα DataSourceType είναι DataSourceType.Worksheet, τότε αυτή η μέθοδος επιστρέφει τη διεύθυνση των κελιών στο βιβλίο εργασίας που αντιπροσωπεύουν τα δεδομένα συμβολοσειράς. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Δεν επιτρέπεται η ανάθεση τιμής null. Η επιστρεφόμενη τιμή είναι πάντα μη null. Ανάγνωση/εγγραφή [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Επιστρέφει:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Δεν επιτρέπεται η ανάθεση τιμής null. Η επιστρεφόμενη τιμή είναι πάντα μη null. Ανάγνωση/εγγραφή [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Επιστρέφει ή ορίζει την τιμή ως κυριολεκτική συμβολοσειρά. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Επιστρέφει ή ορίζει την τιμή ως κυριολεκτική συμβολοσειρά. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Επιστρέφει ή ορίζει αντικείμενο Data. Ανάγνωση/εγγραφή Object.

**Επιστρέφει:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Επιστρέφει ή ορίζει αντικείμενο Data. Ανάγνωση/εγγραφή Object.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Επιστρέφει δεδομένα τιμής συμβολοσειράς. Επιστρέφει null εάν η DataSourceType είναι false και δεν έχει ανατεθεί τιμή συμβολοσειράς.

**Επιστρέφει:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Ορίζει την τιμή από το καθορισμένο κελί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Εάν η ιδιότητα DataSourceType είναι DataSourceType.Worksheet, τότε αυτή η μέθοδος επιστρέφει τη διεύθυνση των κελιών στο βιβλίο εργασίας που αντιπροσωπεύουν τα δεδομένα συμβολοσειράς. Διαφορετικά επιστρέφει κενή συμβολοσειρά.

**Επιστρέφει:**
java.lang.String