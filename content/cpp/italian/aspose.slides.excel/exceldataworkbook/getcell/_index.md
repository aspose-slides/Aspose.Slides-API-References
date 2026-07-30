---
title: GetCell()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera una cella dal foglio di lavoro specificato usando il suo indice e le coordinate della cella.
type: docs
weight: 27
url: /it/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metodo


Recupera una cella dal foglio di lavoro specificato usando il suo indice e le coordinate della cella.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice basato su zero del foglio di lavoro. |
| row | **int32_t** | Indice basato su zero della riga della cella. |
| column | **int32_t** | Indice basato su zero della colonna della cella. |

### Valore di ritorno

La cella nella posizione specificata.
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metodo


Recupera una cella dal foglio di lavoro specificato usando il suo nome e le coordinate della cella.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro. |
| row | **int32_t** | Indice basato su zero della riga della cella. |
| column | **int32_t** | Indice basato su zero della colonna della cella. |

### Valore di ritorno

La cella nella posizione specificata.
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) metodo


Recupera una cella dal foglio di lavoro specificato usando il suo indice e il nome della cella in stile Excel (ad es., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice basato su zero del foglio di lavoro. |
| cellName | [System::String](../../../system/string/) | Il riferimento alla cella in stile Excel (ad es., "A1", "C5"). |

### Valore di ritorno

La cella nella posizione specificata.
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) metodo


Recupera una cella dal foglio di lavoro specificato usando il nome della cella in stile Excel (ad es., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro. |
| cellName | [System::String](../../../system/string/) | Il riferimento alla cella in stile Excel (ad es., "A1", "C5"). |

### Valore di ritorno

La cella nella posizione specificata.
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IExcelDataCell](../../iexceldatacell/)
* Classe [ExcelDataWorkbook](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)