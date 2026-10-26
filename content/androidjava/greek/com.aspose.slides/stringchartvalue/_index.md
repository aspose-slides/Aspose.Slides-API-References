---
title: StringChartValue
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά τιμή συμβολοσειράς η οποία μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με το διάγραμμα· 2) ως κυριολεκτική τιμή.
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

Αναπαριστά μια τιμή συμβολοσειράς η οποία μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους: 1) σε κελί/κελιά του φύλλου εργασίας που σχετίζονται με το διάγραμμα· 2) ως κυριολεκτική τιμή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAsCells()](#getAsCells--) | Η εκχώρηση τιμής null δεν επιτρέπεται. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Η εκχώρηση τιμής null δεν επιτρέπεται. |
| [getAsLiteralString()](#getAsLiteralString--) | Επιστρέφει ή ορίζει την τιμή ως κυριολεκτική συμβολοσειρά. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Επιστρέφει ή ορίζει την τιμή ως κυριολεκτική συμβολοσειρά. |
| [getData()](#getData--) | Επιστρέφει ή ορίζει το αντικείμενο Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Επιστρέφει ή ορίζει το αντικείμενο Data. |
| [toString()](#toString--) | Επιστρέφει τα δεδομένα τιμής συμβολοσειράς. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Ορίζει την τιμή από το συγκεκριμένο κελί. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Εάν η ιδιότητα DataSourceType είναι DataSourceType.Worksheet, τότε αυτή η μέθοδος επιστρέφει τη διεύθυνση των κελιών στο βιβλίο εργασίας που αντιπροσωπεύουν τα δεδομένα της συμβολοσειράς. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Η εκχώρηση τιμής null δεν επιτρέπεται. Η επιστρεφόμενη τιμή είναι πάντα μη-null. Ανάγνωση/εγγραφή [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Επιστρέφει:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Η εκχώρηση τιμής null δεν επιτρέπεται. Η επιστρεφόμενη τιμή είναι πάντα μη-null. Ανάγνωση/εγγραφή [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

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

### toString() {#toString--}
```
public String toString()
```

Επιστρέφει τα δεδομένα τιμής συμβολοσειράς. Επιστρέφει null εάν το DataSourceType είναι false και δεν έχει οριστεί τιμή συμβολοσειράς.

**Επιστρέφει:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Ορίζει την τιμή από το συγκεκριμένο κελί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Εάν η ιδιότητα DataSourceType είναι DataSourceType.Worksheet, τότε αυτή η μέθοδος επιστρέφει τη διεύθυνση των κελιών στο βιβλίο εργασίας που αντιπροσωπεύουν τα δεδομένα της συμβολοσειράς. Διαφορετικά επιστρέφει κενή συμβολοσειρά.

**Επιστρέφει:**
java.lang.String