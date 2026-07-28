---
title: GetCells()
second_title: Aspose.Slides C++ API referencia
description: A munkafüzetből egy adott képletre illeszkedő cellákat tartalmazó gyűjteményt kér le.
type: docs
weight: 1
url: /hu/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) method

A megadott képlettel egyező cellákat tartalmazó gyűjteményt kér le a munkafüzetből.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | A képlet vagy tartománykifejezés (pl. \"Sheet1!A1:B3\"), amely a célcellák azonosítására szolgál. |
| skipHiddenCells | **bool** | Ha **true**, a rejtett cellák (pl. rejtett sorokban vagy oszlopokban) ki lesznek zárva az eredményből. |

### Visszatérési érték

A megadott képlettel egyező cellákat tartalmazó csak olvasható lista.
## Megjegyzések



Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Osztály [IExcelDataCell](../../iexceldatacell/)
* Osztály [String](../../../system/string/)
* Osztály [IExcelDataWorkbook](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)