---
title: get_Value()
second_title: Aspose.Slides C++ API referencia
description: "A Excel cellában lévő értéket adja vissza. Csak olvasható System::Object."
type: docs
weight: 1
url: /hu/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() metódus


A [Excel](../../) cellában tárolt értéket adja vissza. Csak olvasható [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [IExcelDataCell](../)
* Névtér [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)