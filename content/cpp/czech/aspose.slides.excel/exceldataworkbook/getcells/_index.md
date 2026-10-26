---
title: GetCells()
second_title: Aspose.Slides pro C++ API Reference
description: Načte kolekci buněk z pracovního sešitu, které odpovídají zadanému vzorci.
type: docs
weight: 14
url: /cs/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) metoda

Načte kolekci buněk z pracovního sešitu, které odpovídají zadanému vzorci.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Vzorec nebo rozsahový výraz (např. "Sheet1!A1:B3") používaný k určení cílových buněk. |
| skipHiddenCells | **bool** | Pokud je **true**, skryté buňky (např. ve skrytých řádcích nebo sloupcích) budou vyloučeny z výsledku. |

### Návratová hodnota

Seznam buněk jen pro čtení, které odpovídají zadanému vzorci.

## Poznámky



Příklad: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Třída [IExcelDataCell](../../iexceldatacell/)
* Třída [String](../../../system/string/)
* Třída [ExcelDataWorkbook](../)
* Jmenný prostor [Aspose::Slides::Excel](../../)
* Knihovna [Aspose.Slides](../../../)