---
title: AddTableFromWorkbook
second_title: Αναφορά API Aspose.Sildes για .NET
description: Ανακτά έναν πίνακα από το καθορισμένο βιβλίο εργασיה Excel και τον προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.
type: docs
weight: 20
url: /el/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Ανάκτηση ενός πίνακα από το καθορισμένο βιβλίο εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | IShapeCollection | Η συλλογή σχημάτων στην οποία θα προστεθεί ο πίνακας. |
| x | Single | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | Single | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbook | IExcelDataWorkbook | Το βιβλίο εργασίας Excel. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | String | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

### Τιμή επιστροφής

Ο πίνακας που προστέθηκε στη συλλογή σχημάτων.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι null ή κενή, ή όταν το καθορισμένο φύλλο εργασίας ή η περιοχή κελιών είναι άκυρα. |
| InvalidOperationException | Εκτοπίζεται όταν τα δεδομένα εισόδου είναι σε μορφή που δεν υποστηρίζεται. |

### Παραδείγματα

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* διεπαφή [ITable](../../../aspose.slides/itable)
* διεπαφή [IShapeCollection](../../../aspose.slides/ishapecollection)
* διεπαφή [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* κλάση [ExcelWorkbookImporter](../../excelworkbookimporter)
* χώρος ονομάτων [Aspose.Slides.Import](../../excelworkbookimporter)
* συγκρότημα [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Ανάκτηση ενός πίνακα από το καθορισμένο αρχείο βιβλίου εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | IShapeCollection | Η συλλογή σχημάτων στην οποία θα προστεθεί ο πίνακας. |
| x | Single | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | Single | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbookPath | String | Η διαδρομή προς το αρχείο βιβλίου εργασίας Excel. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | String | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

### Τιμή επιστροφής

Ο πίνακας που προστέθηκε στη συλλογή σχημάτων.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι null ή κενή, ή όταν το καθορισμένο φύλλο εργασίας ή η περιοχή κελιών είναι άκυρα. |
| IOException | Εκτοπίζεται όταν συμβαίνει σφάλμα I/O κατά την πρόσβαση στο αρχείο του βιβλίου εργασίας. |
| InvalidOperationException | Εκτοπίζεται όταν τα δεδομένα εισόδου είναι σε μορφή που δεν υποστηρίζεται. |

### Παραδείγματα

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* διεπαφή [ITable](../../../aspose.slides/itable)
* διεπαφή [IShapeCollection](../../../aspose.slides/ishapecollection)
* κλάση [ExcelWorkbookImporter](../../excelworkbookimporter)
* χώρος ονομάτων [Aspose.Slides.Import](../../excelworkbookimporter)
* συγκρότημα [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Ανάκτηση ενός πίνακα από το καθορισμένο αρχείο βιβλίου εργασίας Excel και προσθήκη του στο τέλος της δοσμένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | IShapeCollection | Η συλλογή σχημάτων στην οποία θα προστεθεί ο πίνακας. |
| x | Single | Η συντεταγμένη X για την τοποθέτηση του πίνακα. |
| y | Single | Η συντεταγμένη Y για την τοποθέτηση του πίνακα. |
| workbookStream | Stream | Ένα ρεύμα που περιέχει τα δεδομένα του βιβλίου εργασίας. |
| worksheetName | String | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | String | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

### Τιμή επιστροφής

Ο πίνακας που προστέθηκε στη συλλογή σχημάτων.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν οποιαδήποτε απαιτούμενη παράμετρος είναι null ή κενή, ή όταν το καθορισμένο φύλλο εργασίας ή η περιοχή κελιών είναι άκυρα. |
| InvalidOperationException | Εκτοπίζεται όταν τα δεδομένα εισόδου είναι σε μορφή που δεν υποστηρίζεται. |

### Παραδείγματα

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* διεπαφή [ITable](../../../aspose.slides/itable)
* διεπαφή [IShapeCollection](../../../aspose.slides/ishapecollection)
* κλάση [ExcelWorkbookImporter](../../excelworkbookimporter)
* χώρος ονομάτων [Aspose.Slides.Import](../../excelworkbookimporter)
* συγκρότημα [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->