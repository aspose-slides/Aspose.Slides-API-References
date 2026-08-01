---
title: GetCells()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een verzameling cellen op uit de werkmap die overeenkomen met de opgegeven formule.
type: docs
weight: 14
url: /nl/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) method


Haal een verzameling cellen op uit de werkmap die overeenkomen met de opgegeven formule.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Een formule of bereikexpressie (bijv. \"Sheet1!A1:B3\") die wordt gebruikt om doelcellen te identificeren. |
| skipHiddenCells | **bool** | Als **true**, worden verborgen cellen (bijv. in verborgen rijen of kolommen) uit het resultaat geëxcludeerd. |

### Retourwaarde

Een alleen-lezen lijst van cellen die overeenkomen met de opgegeven formule.
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Klasse [IExcelDataCell](../../iexceldatacell/)
* Klasse [String](../../../system/string/)
* Klasse [ExcelDataWorkbook](../)
* Naamruimte [Aspose::Slides::Excel](../../)
* Bibliotheek [Aspose.Slides](../../../)