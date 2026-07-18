---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ανακτά ένα λεξικό που περιέχει τους δείκτες και τα ονόματα όλων των διαγραμμάτων στο καθορισμένο φύλλο εργασίας ενός αρχείου Excel.
type: docs
weight: 27
url: /el/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) μέθοδος


Ανακτά ένα λεξικό που περιέχει τους δείκτες και τα ονόματα όλων των διαγραμμάτων στο καθορισμένο φύλλο εργασίας ενός [Excel](../../) βιβλίου εργασίας.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας για την αναζήτηση διαγραμμάτων. |

### Τιμή επιστροφής

Ένα λεξικό όπου το κλειδί είναι ο δείκτης του διαγράμματος και η τιμή είναι το όνομα του διαγράμματος.

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
* Κλάση [IExcelDataWorkbook](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)