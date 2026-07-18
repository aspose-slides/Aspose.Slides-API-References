---
title: GetCell()
second_title: Αναφορά API Aspose.Slides για C++
description: Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το ευρετήριο και τις συντεταγμένες του κελιού.
type: docs
weight: 14
url: /el/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) μέθοδος

Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το ευρετήριο και τις συντεταγμένες του κελιού.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Δείκτης του φύλλου εργασίας με μηδενική βάση. |
| row | **int32_t** | Δείκτης γραμμής του κελιού με μηδενική βάση. |
| column | **int32_t** | Δείκτης στήλης του κελιού με μηδενική βάση. |

### Τιμή επιστροφής

Το κελί στην καθορισμένη θέση.

## Σχόλια



Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) μέθοδος

Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομά του και τις συντεταγμένες του κελιού.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας. |
| row | **int32_t** | Δείκτης γραμμής του κελιού με μηδενική βάση. |
| column | **int32_t** | Δείκτης στήλης του κελιού με μηδενική βάση. |

### Τιμή επιστροφής

Το κελί στην καθορισμένη θέση.

## Σχόλια



Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) μέθοδος

Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το ευρετήριο και το όνομα κελιού σε μορφή Excel (π.χ., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Δείκτης του φύλλου εργασίας με μηδενική βάση. |
| cellName | [System::String](../../../system/string/) | Η αναφορά κελιού σε μορφή Excel (π.χ., "A1", "C5"). |

### Τιμή επιστροφής

Το κελί στην καθορισμένη θέση.

## Σχόλια



Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) μέθοδος

Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομα κελιού σε μορφή Excel (π.χ., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας. |
| cellName | [System::String](../../../system/string/) | Η αναφορά κελιού σε μορφή Excel (π.χ., "A1", "C5"). |

### Τιμή επιστροφής

Το κελί στην καθορισμένη θέση.

## Σχόλια



Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IExcelDataCell](../../iexceldatacell/)
* Κλάση [IExcelDataWorkbook](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)