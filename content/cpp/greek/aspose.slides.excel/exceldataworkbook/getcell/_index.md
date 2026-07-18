---
title: GetCell()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το δείκτη του και τις συντεταγμένες του κελιού.
type: docs
weight: 27
url: /el/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) μέθοδος

Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το δείκτη του και τις συντεταγμένες του κελιού.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Δείκτης του φύλλου εργασίας με βάση το μηδέν. |
| row | **int32_t** | Δείκτης γραμμής του κελιού με βάση το μηδέν. |
| column | **int32_t** | Δείκτης στήλης του κελιού με βάση το μηδέν. |

### Τιμή Επιστροφής

Το κελί στην καθορισμένη θέση.

## Παρατηρήσεις



Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) μέθοδος

Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομά του και τις συντεταγμένες του κελιού.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας. |
| row | **int32_t** | Δείκτης γραμμής του κελιού με βάση το μηδέν. |
| column | **int32_t** | Δείκτης στήλης του κελιού με βάση το μηδέν. |

### Τιμή Επιστροφής

Το κελί στην καθορισμένη θέση.

## Παρατηρήσεις



Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) μέθοδος

Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το δείκτη του και το όνομα κελιού σε μορφή Excel (π.χ., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Δείκτης του φύλλου εργασίας με βάση το μηδέν. |
| cellName | [System::String](../../../system/string/) | Η αναφορά κελιού σε μορφή Excel (π.χ., "A1", "C5"). |

### Τιμή Επιστροφής

Το κελί στην καθορισμένη θέση.

## Παρατηρήσεις



Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) μέθοδος

Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομα φύλλου και το όνομα κελιού σε μορφή Excel (π.χ., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας. |
| cellName | [System::String](../../../system/string/) | Η αναφορά κελιού σε μορφή Excel (π.χ., "A1", "C5"). |

### Τιμή Επιστροφής

Το κελί στην καθορισμένη θέση.

## Παρατηρήσεις



Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IExcelDataCell](../../iexceldatacell/)
* Κλάση [ExcelDataWorkbook](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)