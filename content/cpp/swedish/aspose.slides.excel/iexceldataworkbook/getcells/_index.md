---
title: GetCells()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en samling celler från arbetsboken som matchar den angivna formeln.
type: docs
weight: 1
url: /sv/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) metod

Hämtar en samling celler från arbetsboken som matchar den angivna formeln.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | En formel eller intervalsexpression (t.ex. "Sheet1!A1:B3") som används för att identifiera målceller. |
| skipHiddenCells | **bool** | Om **true**, dolda celler (t.ex. i dolda rader eller kolumner) kommer att uteslutas från resultatet. |

### Returvärde

En skrivskyddad lista med celler som matchar den angivna formeln.

## Anmärkningar

Exempel:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Klass [IExcelDataCell](../../iexceldatacell/)
* Klass [String](../../../system/string/)
* Klass [IExcelDataWorkbook](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)