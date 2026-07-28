---
title: GetCell()
second_title: Aspose.Slides for C++ API referenciája
description: Lekéri a cellát a megadott munkalapról az indexe és a cella koordinátái alapján.
type: docs
weight: 27
url: /hu/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metódus

Lekéri a cellát a megadott munkalapról az indexe és a cella koordinátái alapján.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | **int32_t** | A munkalap nullaalapú indexe. |
| row | **int32_t** | A cella sorának nullaalapú indexe. |
| column | **int32_t** | A cella oszlopának nullaalapú indexe. |

### Visszatérési érték

A megadott helyen lévő cella.
## Megjegyzések

Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metódus

Lekéri a cellát a megadott munkalapról a neve és a cella koordinátái alapján.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve. |
| row | **int32_t** | A cella sorának nullaalapú indexe. |
| column | **int32_t** | A cella oszlopának nullaalapú indexe. |

### Visszatérési érték

A megadott helyen lévő cella.
## Megjegyzések

Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) metódus

Lekéri a cellát a megadott munkalapról az indexe és az Excel-stílusú cellanév (pl. "B2") alapján.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | **int32_t** | A munkalap nullaalapú indexe. |
| cellName | [System::String](../../../system/string/) | Az Excel-stílusú cellahivatkozás (pl. "A1", "C5"). |

### Visszatérési érték

A megadott helyen lévő cella.
## Megjegyzések

Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) metódus

Lekéri a cellát a megadott munkalapról Excel-stílusú cellanév (pl. "B2") alapján.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve. |
| cellName | [System::String](../../../system/string/) | Az Excel-stílusú cellahivatkozás (pl. "A1", "C5"). |

### Visszatérési érték

A megadott helyen lévő cella.
## Megjegyzések

Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IExcelDataCell](../../iexceldatacell/)
* Osztály [ExcelDataWorkbook](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)