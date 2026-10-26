---
title: GetCell()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera la cella che può essere utilizzata per le serie o le categorie del grafico
type: docs
weight: 40
url: /it/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) metodo


Recupera la cella che può essere utilizzata per le serie o le categorie del grafico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nome del foglio di lavoro. |
| row | **int32_t** | La riga. |
| column | **int32_t** | La colonna. |

### Valore di ritorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) metodo


Recupera la cella che può essere utilizzata per le serie o le categorie del grafico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice del foglio di lavoro. |
| row | **int32_t** | La riga. |
| column | **int32_t** | La colonna. |

### Valore di ritorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String) metodo


Recupera la cella che può essere utilizzata per le serie o le categorie del grafico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice del foglio di lavoro. |
| cellName | [System::String](../../../system/string/) | Nome della cella. |

### Valore di ritorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) metodo


Recupera la cella che può essere utilizzata per le serie o le categorie del grafico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice del foglio di lavoro. |
| cellName | [System::String](../../../system/string/) | Nome della cella. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Il valore. |

### Valore di ritorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) metodo


Recupera la cella che può essere utilizzata per le serie o le categorie del grafico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice del foglio di lavoro. |
| row | **int32_t** | La riga. |
| column | **int32_t** | La colonna. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Il valore. |

### Valore di ritorno

[Cell](../../../aspose.slides/cell/) object

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [String](../../../system/string/)
* Classe [IChartDataWorkbook](../)
* Classe [Object](../../../system/object/)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)