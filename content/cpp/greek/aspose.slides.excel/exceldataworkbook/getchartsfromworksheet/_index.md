---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανακτά ένα λεξικό που περιέχει τα ευρετήρια και τα ονόματα όλων των διαγραμμάτων στο καθορισμένο φύλλο εργασίας ενός βιβλίου εργασίας Excel.
type: docs
weight: 40
url: /el/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) μέθοδος

Ανακτά ένα λεξικό που περιέχει τα ευρετήρια και τα ονόματα όλων των διαγραμμάτων στο καθορισμένο φύλλο εργασίας ενός [Excel](../../) βιβλίου εργασίας.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας για την αναζήτηση διαγραμμάτων. |

### Τιμή Επιστροφής

Ένα λεξικό όπου το κλειδί είναι το ευρετήριο του διαγράμματος και η τιμή είναι το όνομα του διαγράμματος.
## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IDictionary](../../../system.collections.generic/idictionary/)
* Κλάση [String](../../../system/string/)
* Κλάση [ExcelDataWorkbook](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)