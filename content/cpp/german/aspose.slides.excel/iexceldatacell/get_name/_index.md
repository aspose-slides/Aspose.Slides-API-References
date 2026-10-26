---
title: get_Name()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt den Namen der Diagrammdatenzelle zurück. Nur lesbar System::String."
type: docs
weight: 14
url: /de/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() Methode


Liefert den Namen der Diagrammdatenzelle. Nur lesbar [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IExcelDataCell](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)