---
title: add_chart_from_workbook method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Ανακτά ένα διάγραμμα από το καθορισμένο αρχείο εργασίας Excel και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

### Επιστροφή

Το διάγραμμα που προστέθηκε στην συλλογή σχημάτων.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/el/aspose.slides.excel/iexceldataworkbook) | Το αρχείο εργασίας Excel. |
| worksheet_name | **str** | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chart_index | **int** | Ο μηδενικός δείκτης του σχήματος διαγράμματος που θα εισαχθεί. <br/><br/>            This index can be obtained using the **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** method. |
| embed_all_workbook | **bool** | Εάν `true`, ολόκληρο το αρχείο εργασίας θα ενσωματωθεί στο διάγραμμα· <br/><br/>            εάν `false`, θα ενσωματωθούν μόνο τα δεδομένα του διαγράμματος. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Σφαράχθηκε όταν κάποια απαιτούμενη παράμετρος είναι None, κενή ή όταν δεν βρεθεί το διάγραμμα στο αρχείο εργασίας. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Ανακτά ένα διάγραμμα από το καθορισμένο αρχείο εργασίας Excel και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

### Επιστροφή

Το διάγραμμα που προστέθηκε στην συλλογή σχημάτων.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/el/aspose.slides.excel/iexceldataworkbook) | Το αρχείο εργασίας Excel. |
| worksheet_name | **str** | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chart_name | **str** | Το όνομα του διαγράμματος που θα προστεθεί. |
| embed_all_workbook | **bool** | Εάν `true`, ολόκληρο το αρχείο εργασίας θα ενσωματωθεί στο διάγραμμα· <br/><br/>            εάν `false`, θα ενσωματωθούν μόνο τα δεδομένα του διαγράμματος. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Σφαράχθηκε όταν κάποια απαιτούμενη παράμετρος είναι None, κενή ή όταν δεν βρεθεί το διάγραμμα στο αρχείο εργασίας. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Ανακτά ένα διάγραμμα από το καθορισμένο αρχείο εργασίας Excel και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

### Επιστροφή

Το διάγραμμα που προστέθηκε στην συλλογή σχημάτων.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbook_stream | **io.RawIOBase** | Ροή που περιέχει τα δεδομένα του αρχείου εργασίας. |
| worksheet_name | **str** | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chart_name | **str** | Το όνομα του διαγράμματος που θα προστεθεί. |
| embed_all_workbook | **bool** | Εάν `true`, ολόκληρο το αρχείο εργασίας θα ενσωματωθεί στο διάγραμμα· <br/><br/>            εάν `false`, θα ενσωματωθούν μόνο τα δεδομένα του διαγράμματος. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Σφαράχθηκε όταν κάποια απαιτούμενη παράμετρος είναι None, κενή ή όταν δεν βρεθεί το διάγραμμα στο αρχείο εργασίας. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Σφαράχθηκε όταν τα εισερχόμενα δεδομένα είναι σε μορφή που δεν υποστηρίζεται. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Ανακτά ένα διάγραμμα από το καθορισμένο αρχείο εργασίας Excel και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

### Επιστροφή

Το διάγραμμα που προστέθηκε στην συλλογή σχημάτων.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection) | Η συλλογή σχημάτων στην οποία θα προστεθεί το διάγραμμα. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbook_path | **str** | Η διαδρομή αρχείου προς το αρχείο εργασίας που περιέχει το διάγραμμα. |
| worksheet_name | **str** | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chart_name | **str** | Το όνομα του διαγράμματος που θα προστεθεί. |
| embed_workbook | **bool** | Εάν `true`, το αρχείο εργασίας θα ενσωματωθεί στο διάγραμμα· <br/><br/>            εάν `false`, το διάγραμμα θα έχει σύνδεσμο προς το εξωτερικό αρχείο εργασίας. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Σφαράχθηκε όταν κάποια απαιτούμενη παράμετρος είναι None, κενή ή όταν δεν βρεθεί το διάγραμμα στο αρχείο εργασίας. |
| **RuntimeError(Proxy error(IOException))** | Σφαράχθηκε όταν προέκυψε σφάλμα I/O κατά την πρόσβαση στο αρχείο. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Σφαράχθηκε όταν τα εισερχόμενα δεδομένα είναι σε μορφή που δεν υποστηρίζεται. |



### Δείτε επίσης
* class [`ExcelWorkbookImporter`](/slides/python-net/el/aspose.slides.importing/excelworkbookimporter)
* class [`IExcelDataWorkbook`](/slides/python-net/el/aspose.slides.excel/iexceldataworkbook)
* class [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* module [`aspose.slides.importing`](/slides/python-net/el/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)