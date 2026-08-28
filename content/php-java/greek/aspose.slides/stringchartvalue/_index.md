---
title: StringChartValue
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/stringchartvalue/
---
## StringChartValue κλάση

Αναπαριστά την τιμή συμβολοσειράς που μπορεί να αποθηκευτεί σε έγγραφο παρουσίασης pptx με δύο τρόπους:
 1) σε κελί/κελιά του βιβλίου εργασίας που σχετίζονται με διάγραμμα·
 2) ως κυριολεκτική τιμή.

### getAsCells {#getAsCells}

| Name | Description |
| --- | --- |
| getAsCells () | Η ανάθεση τιμής null δεν επιτρέπεται. Η επιστρεφόμενη τιμή είναι πάντα μη null. Ανάγνωση/Εγγραφή IChartCellCollection. |

**Επιστρέφει:**
[ChartCellCollection](../chartcellcollection)

---


### getAsLiteralString {#getAsLiteralString}

| Name | Description |
| --- | --- |
| getAsLiteralString () | Επιστρέφει ή ορίζει τιμή ως κυριολεκτική συμβολοσειρά. Ανάγνωση/Εγγραφή String. |

**Επιστρέφει:**
String

---


### getCellsAddressInWorkbook {#getCellsAddressInWorkbook}

| Name | Description |
| --- | --- |
| getCellsAddressInWorkbook () | Εάν η ιδιότητα DataSourceType είναι DataSourceType.Worksheet, τότε αυτή η μέθοδος επιστρέφει τη διεύθυνση των κυψελών στο βιβλίο εργασίας που αντιπροσωπεύει τα δεδομένα συμβολοσειράς. Διαφορετικά επιστρέφει κενό string. |

**Επιστρέφει:**
String

---


### getData {#getData}

| Name | Description |
| --- | --- |
| getData () | Επιστρέφει ή ορίζει αντικείμενο Data. Ανάγνωση/Εγγραφή Object. |

**Επιστρέφει:**
Object

---


### setAsCells {#setAsCells}

| Name | Description |
| --- | --- |
| setAsCells ([ChartCellCollection](../chartcellcollection)) | Η ανάθεση τιμής null δεν επιτρέπεται. Η επιστρεφόμενη τιμή είναι πάντα μη null. Ανάγνωση/Εγγραφή IChartCellCollection. |

**Επιστρέφει:**
void

---


### setAsLiteralString {#setAsLiteralString}

| Name | Description |
| --- | --- |
| setAsLiteralString (String) | Επιστρέφει ή ορίζει τιμή ως κυριολεκτική συμβολοσειρά. Ανάγνωση/Εγγραφή String. |

**Επιστρέφει:**
void

---


### setData {#setData}

| Name | Description |
| --- | --- |
| setData (Object) | Επιστρέφει ή ορίζει αντικείμενο Data. Ανάγνωση/Εγγραφή Object. |

**Επιστρέφει:**
void

---


### setFromOneCell {#setFromOneCell}

| Name | Description |
| --- | --- |
| setFromOneCell ([ChartDataCell](../chartdatacell)) | Ορίζει την τιμή από το καθορισμένο κελί. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| cell | [ChartDataCell](../chartdatacell) | Κυψέλη. |

**Επιστρέφει:**
void

---


### toString {#toString}

| Name | Description |
| --- | --- |
| toString () | Επιστρέφει τα δεδομένα τιμής συμβολοσειράς. Επιστρέφει null αν DataSourceType είναι false και δεν έχει ανατεθεί τιμή συμβολοσειράς. |

**Επιστρέφει:**
String

---