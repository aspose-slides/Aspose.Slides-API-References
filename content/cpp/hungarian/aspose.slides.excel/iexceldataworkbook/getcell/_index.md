---
title: GetCell()
second_title: Aspose.Slides C++ API-referencia
description: Lekéri a megadott munkalap celláját az index és a cellakoordináták használatával.
type: docs
weight: 14
url: /hu/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metódus


Lekéri a cellát a megadott munkalapról az index és a cella koordináták használatával.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | **int32_t** | A munkalap nullától induló indexe. |
| row | **int32_t** | A cella sorának nullától induló indexe. |
| column | **int32_t** | A cella oszlopának nullától induló indexe. |

### Visszatérési érték

A megadott helyen lévő cella.
## Megjegyzések



Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metódus


Lekéri a cellát a megadott munkalapról a neve és a cella koordináták használatával.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve. |
| row | **int32_t** | A cella sorának nullától induló indexe. |
| column | **int32_t** | A cella oszlopának nullától induló indexe. |

### Visszatérési érték

A megadott helyen lévő cella.
## Megjegyzések



Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) metódus


Lekéri a cellát a megadott munkalapról az index és az Excel-stílusú cellanév (pl. „B2”) használatával.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | **int32_t** | A munkalap nullától induló indexe. |
| cellName | [System::String](../../../system/string/) | Az Excel-stílusú cellahivatkozás (pl. „A1”, „C5”). |

### Visszatérési érték

A megadott helyen lévő cella.
## Megjegyzések



Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) metódus


Lekéri a cellát a megadott munkalapról Excel-stílusú cellanév (pl. „B2”) használatával.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | A munkalap neve. |
| cellName | [System::String](../../../system/string/) | Az Excel-stílusú cellahivatkozás (pl. „A1”, „C5”). |

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
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [IExcelDataWorkbook](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)