---
title: GetCells()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft eine Sammlung von Zellen aus der Arbeitsmappe ab, die der angegebenen Formel entsprechen.
type: docs
weight: 14
url: /de/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) Methode


Ruft eine Sammlung von Zellen aus der Arbeitsmappe ab, die der angegebenen Formel entsprechen.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Eine Formel oder Bereichsausdruck (z. B. "Sheet1!A1:B3") zur Identifizierung der Zielzellen. |
| skipHiddenCells | **bool** | Falls **true**, werden versteckte Zellen (z. B. in versteckten Zeilen oder Spalten) vom Ergebnis ausgeschlossen. |

### Rückgabewert

Eine schreibgeschützte Liste von Zellen, die der angegebenen Formel entsprechen.
## Anmerkungen



Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [String](../../../system/string/)
* Class [ExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)