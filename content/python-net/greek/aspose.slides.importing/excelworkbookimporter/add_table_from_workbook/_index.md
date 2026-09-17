---
title: add_table_from_workbook method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Ανακτά έναν πίνακα από το καθορισμένο βιβλίο εργασίας Excel και τον προσθέτει στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες.

### Επιστροφή

Ο πίνακας που προστέθηκε στη συλλογή σχήματος.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```



| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί ο πίνακας. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/el/aspose.slides.excel/iexceldataworkbook) | Το βιβλίο εργασίας Excel. |
| worksheet_name | **str** | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cell_range | **str** | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκβάλλεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι None ή κενή, ή όταν το καθορισμένο φύλλο εργασίας ή η περιοχή κελιών είναι άκυρα. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Εκβάλλεται όταν τα δεδομένα εισόδου είναι σε μη υποστηριζόμενη μορφή. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Ανακτά έναν πίνακα από το καθορισμένο αρχείο βιβλίου εργασίας Excel και τον προσθέτει στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες.

### Επιστροφή

Ο πίνακας που προστέθηκε στη συλλογή σχήματος.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί ο πίνακας. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbook_path | **str** | Η διαδρομή προς το αρχείο βιβλίου εργασίας Excel. |
| worksheet_name | **str** | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cell_range | **str** | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκβάλλεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι None ή κενή, ή όταν το καθορισμένο φύλλο εργασίας ή η περιοχή κελιών είναι άκυρα. |
| **RuntimeError(Proxy error(IOException))** | Εκβάλλεται όταν συμβαίνει σφάλμα I/O κατά την πρόσβαση στο αρχείο βιβλίου εργασίας. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Εκβάλλεται όταν τα δεδομένα εισόδου είναι σε μη υποστηριζόμενη μορφή. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Ανακτά έναν πίνακα από το καθορισμένο αρχείο βιβλίου εργασίας Excel και τον προσθέτει στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες.

### Επιστροφή

Ο πίνακας που προστέθηκε στη συλλογή σχήματος.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί ο πίνακας. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbook_stream | **io.RawIOBase** | Μία ροή που περιέχει τα δεδομένα του βιβλίου εργασίας. |
| worksheet_name | **str** | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cell_range | **str** | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκβάλλεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι None ή κενή, ή όταν το καθορισμένο φύλλο εργασίας ή η περιοχή κελιών είναι άκυρα. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Εκβάλλεται όταν τα δεδομένα εισόδου είναι σε μη υποστηριζόμενη μορφή. |



### Δείτε επίσης
* κλάση [`ExcelWorkbookImporter`](/slides/python-net/el/aspose.slides.importing/excelworkbookimporter)
* κλάση [`IExcelDataWorkbook`](/slides/python-net/el/aspose.slides.excel/iexceldataworkbook)
* κλάση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* κλάση [`ITable`](/slides/python-net/el/aspose.slides/itable)
* μονάδα [`aspose.slides.importing`](/slides/python-net/el/aspose.slides.importing)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)