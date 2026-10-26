---
title: GetCell()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera una cella dal foglio di lavoro specificato utilizzando il suo indice e le coordinate della cella.
type: docs
weight: 14
url: /it/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metodo


Recupera una cella dal foglio di lavoro specificato utilizzando il suo indice e le coordinate della cella.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice basato su zero del foglio di lavoro. |
| row | **int32_t** | Indice di riga basato su zero della cella. |
| column | **int32_t** | Indice di colonna basato su zero della cella. |

### Valore restituito

La cella nella posizione specificata.
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metodo


Recupera una cella dal foglio di lavoro specificato utilizzando il suo nome e le coordinate della cella.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro. |
| row | **int32_t** | Indice di riga basato su zero della cella. |
| column | **int32_t** | Indice di colonna basato su zero della cella. |

### Valore restituito

La cella nella posizione specificata.
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) metodo


Recupera una cella dal foglio di lavoro specificato utilizzando il suo indice e il nome della cella in stile Excel (ad es., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice basato su zero del foglio di lavoro. |
| cellName | [System::String](../../../system/string/) | Il riferimento della cella in stile Excel (ad es., "A1", "C5"). |

### Valore restituito

La cella nella posizione specificata.
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) metodo


Recupera una cella dal foglio di lavoro specificato utilizzando il nome della cella in stile Excel (ad es., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro. |
| cellName | [System::String](../../../system/string/) | Il riferimento della cella in stile Excel (ad es., "A1", "C5"). |

### Valore restituito

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
* Classe [IExcelDataWorkbook](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)