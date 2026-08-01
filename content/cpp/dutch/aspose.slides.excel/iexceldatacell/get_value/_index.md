---
title: get_Value()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de waarde op die zich in de Excel-cel bevindt. Alleen-lezen System::Object."
type: docs
weight: 1
url: /nl/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() methode


Haalt de waarde op die zich in de [Excel](../../) cel bevindt. Alleen-lezen [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [IExcelDataCell](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)