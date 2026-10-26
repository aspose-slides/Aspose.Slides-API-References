---
title: ExcelWorkbookImporter
second_title: Aspose.Sildes για PHP μέσω Αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/excelworkbookimporter/
---
## ExcelWorkbookImporter κλάση

 Παρέχει λειτουργικότητα για την εισαγωγή περιεχομένου από ένα βιβλίο εργασίας Excel σε μια παρουσίαση.
 
### addChartFromWorkbook {#addChartFromWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  int, boolean) | Ανάκτηση ενός διαγράμματος από το καθορισμένο βιβλίο εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί το διάγραμμα. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | Το βιβλίο εργασίας Excel. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartIndex | int | Ο δείκτης μηδενικής βάσης του σχήματος διαγράμματος που θα εισαχθεί. Αυτός ο δείκτης μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο IExcelDataWorkbook#getChartsFromWorksheet(String). |
| embedAllWorkbook | boolean | Εάν είναι true, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· εάν είναι false, θα ενσωματωθούν μόνο τα δεδομένα του διαγράμματος. |

 **Επιστρέφει:**
[Chart](../chart)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Ενισφαλματίζεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι null, κενή, ή εάν δεν είναι δυνατό το διάγραμμα να βρεθεί στο βιβλίο εργασίας. |


---

### addChartFromWorkbook {#addChartFromWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  String, boolean) | Ανάκτηση ενός διαγράμματος από το καθορισμένο βιβλίο εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί το διάγραμμα. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | Το βιβλίο εργασίας Excel. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartName | String | Το όνομα του διαγράμματος που θα προστεθεί. |
| embedAllWorkbook | boolean | Εάν είναι true, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· εάν είναι false, θα ενσωματωθούν μόνο τα δεδομένα του διαγράμματος. |

 **Επιστρέφει:**
[Chart](../chart)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | Ενισφαλματίζεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι null, κενή, ή εάν δεν είναι δυνατό το διάγραμμα να βρεθεί στο βιβλίο εργασίας. |


---

### addChartFromWorkbook {#addChartFromWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, InputStream, String, String,  boolean) | Ανάκτηση ενός διαγράμματος από το καθορισμένο βιβλίο εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί το διάγραμμα. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbookStream | InputStream | Μια ροή που περιέχει τα δεδομένα του βιβλίου εργασίας. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartName | String | Το όνομα του διαγράμματος που θα προστεθεί. |
| embedAllWorkbook | boolean | Εάν είναι true, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· εάν είναι false, θα ενσωματωθούν μόνο τα δεδομένα του διαγράμματος. |

 **Επιστρέφει:**
[Chart](../chart)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | InvalidOperationException | Ενισφαλματίζεται όταν τα εισερχόμενα δεδομένα είναι σε μη υποστηριζόμενη μορφή. |


---

### addChartFromWorkbook {#addChartFromWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| addChartFromWorkbook ([ShapeCollection](../shapecollection), float, float, String, String, String,  boolean) | Ανάκτηση ενός διαγράμματος από το καθορισμένο βιβλίο εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί το διάγραμμα. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του διαγράμματος. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του διαγράμματος. |
| workbookPath | String | Η διαδρομή αρχείου προς το βιβλίο εργασίας που περιέχει το διάγραμμα. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει το διάγραμμα. |
| chartName | String | Το όνομα του διαγράμματος που θα προστεθεί. |
| embedWorkbook | boolean | Εάν είναι true, το βιβλίο εργασίας θα ενσωματωθεί στο διάγραμμα· εάν είναι false, το διάγραμμα θα συνδεθεί με το εξωτερικό βιβλίο εργασίας. |

 **Επιστρέφει:**
[Chart](../chart)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | InvalidOperationException | Ενισφαλματίζεται όταν τα εισερχόμενα δεδομένα είναι σε μη υποστηριζόμενη μορφή. |


---

### addTableFromWorkbook {#addTableFromWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, [ExcelDataWorkbook](../exceldataworkbook), String,  String) | Ανάκτηση ενός πίνακα από το καθορισμένο βιβλίο εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί ο πίνακας. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbook | [ExcelDataWorkbook](../exceldataworkbook) | Το βιβλίο εργασίας Excel. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | String | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

 **Επιστρέφει:**
[Table](../table)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | InvalidOperationException | Ενισφαλματίζεται όταν τα εισερχόμενα δεδομένα είναι σε μη υποστηριζόμενη μορφή. |


---

### addTableFromWorkbook {#addTableFromWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, String, String, String) | Ανάκτηση ενός πίνακα από το καθορισμένο βιβλίο εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί ο πίνακας. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbookPath | String | Η διαδρομή προς το αρχείο βιβλίου εργασίας Excel. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | String | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

 **Επιστρέφει:**
[Table](../table)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | InvalidOperationException | Ενισφαλματίζεται όταν τα εισερχόμενα δεδομένα είναι σε μη υποστηριζόμενη μορφή. |


---

### addTableFromWorkbook {#addTableFromWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| addTableFromWorkbook ([ShapeCollection](../shapecollection), float, float, InputStream, String, String) | Ανάκτηση ενός πίνακα από το καθορισμένο βιβλίο εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχήματος στις καθορισμένες συντεταγμένες. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [ShapeCollection](../shapecollection) | Η συλλογή σχήματος στην οποία θα προστεθεί ο πίνακας. |
| x | float | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | float | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbookStream | InputStream | Μια ροή που περιέχει τα δεδομένα του βιβλίου εργασίας. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | String | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

 **Επιστρέφει:**
[Table](../table)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | InvalidOperationException | Ενισφαλματίζεται όταν τα εισερχόμενα δεδομένα είναι σε μη υποστηριζόμενη μορφή. |


---