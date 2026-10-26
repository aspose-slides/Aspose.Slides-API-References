---
title: GetCells()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft eine Sammlung von Zellen aus der Arbeitsmappe ab, die der angegebenen Formel entsprechen.
type: docs
weight: 1
url: /de/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) Methode

Ruft eine Sammlung von Zellen aus der Arbeitsmappe ab, die der angegebenen Formel entsprechen.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Eine Formel oder Bereichsausdruck (z. B. "Sheet1!A1:B3") zur Identifizierung der Zielzellen. |
| skipHiddenCells | **bool** | Wenn **true**, werden versteckte Zellen (z. B. in ausgeblendeten Zeilen oder Spalten) aus dem Ergebnis ausgeschlossen. |

### Return Value

Eine schreibgeschützte Liste von Zellen, die der angegebenen Formel entsprechen.

## Hinweise



Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Klasse [IExcelDataCell](../../iexceldatacell/)
* Klasse [String](../../../system/string/)
* Klasse [IExcelDataWorkbook](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)