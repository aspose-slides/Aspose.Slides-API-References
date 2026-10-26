---
title: ChartDataWorkbook
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/chartdataworkbook/
---
## ChartDataWorkbook κλάση

 Παρέχει πρόσβαση σε ενσωματωμένο βιβλίο εργασίας Excel

### calculateFormulas {#calculateFormulas}

| Όνομα | Περιγραφή |
| --- | --- |
| calculateFormulas () | Υπολογίζει όλους τους τύπους στο βιβλίο εργασίας και ενημερώνει τις αντίστοιχες τιμές των κελιών. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | CellUnsupportedDataException | Τα δεδομένα του κελιού δεν υποστηρίζονται. |


---


### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear (int) | Καθαρίζει όλες τις τιμές των κελιών στο φύλλο |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sheetIndex | int | Δείκτης του φύλλου |

 **Επιστρέφει:**
void


---


### getCell {#getCell}

| Όνομα | Περιγραφή |
| --- | --- |
| getCell (String, int, int) | Αποκτά το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες γραφήματος |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetName | String | Το όνομα του φύλλου εργασίας. |
| row | int | Η γραμμή. |
| column | int | Η στήλη. |

 **Επιστρέφει:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Όνομα | Περιγραφή |
| --- | --- |
| getCell (int, int, int) | Αποκτά το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες γραφήματος |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| row | int | Η γραμμή. |
| column | int | Η στήλη. |

 **Επιστρέφει:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Όνομα | Περιγραφή |
| --- | --- |
| getCell (int, String) | Αποκτά το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες γραφήματος |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| cellName | String | Το όνομα του κελιού. |

 **Επιστρέφει:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Όνομα | Περιγραφή |
| --- | --- |
| getCell (int, String, Object) | Αποκτά το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες γραφήματος |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| cellName | String | Το όνομα του κελιού. |
| value | Object | Η τιμή. |

 **Επιστρέφει:**
[ChartDataCell](../chartdatacell)


---


### getCell {#getCell}

| Όνομα | Περιγραφή |
| --- | --- |
| getCell (int, int, int, Object) | Αποκτά το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες γραφήματος |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| row | int | Η γραμμή. |
| column | int | Η στήλη. |
| value | Object | Η τιμή. |

 **Επιστρέφει:**
[ChartDataCell](../chartdatacell)


---


### getCellCollection {#getCellCollection}

| Όνομα | Περιγραφή |
| --- | --- |
| getCellCollection (String, boolean) | Αποκτά το σύνολο των κελιών. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | String | Τύπος Excel όπως "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Εάν είναι true, η μέθοδος επιστρέφει τη συλλογή χωρίς κρυμμένα κελιά. |

 **Επιστρέφει:**
[ChartCellCollection](../chartcellcollection)


---


### getWorksheets {#getWorksheets}

| Όνομα | Περιγραφή |
| --- | --- |
| getWorksheets () | Αποκτά μια συλλογή από φύλλα εργασίας. |

 **Επιστρέφει:**
[ChartDataWorksheetCollection](../chartdataworksheetcollection)


---