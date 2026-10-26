---
title: GetCells()
second_title: Aspose.Slides for C++ API referencia
description: Lekéri a munkafüzetből a megadott képlettel egyező cellák gyűjteményét.
type: docs
weight: 14
url: /hu/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) method


Lekéri a munkafüzetből a megadott képlettel egyező cellák gyűjteményét.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Egy képlet vagy tartománykifejezés (pl. \"Sheet1!A1:B3\"), amely a célcellák azonosítására szolgál. |
| skipHiddenCells | **bool** | Ha **true**, a rejtett cellák (például rejtett sorokban vagy oszlopokban) kizárásra kerülnek az eredményből. |

### Visszatérési érték

Írásvédett lista a megadott képlettel egyező cellákról.
## Megjegyzések



Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Osztály [IExcelDataCell](../../iexceldatacell/)
* Osztály [String](../../../system/string/)
* Osztály [ExcelDataWorkbook](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)