---
title: GetCell()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém a célula que pode ser usada para séries ou categorias de gráfico
type: docs
weight: 40
url: /pt/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) método


Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nome da planilha. |
| row | **int32_t** | A linha. |
| column | **int32_t** | A coluna. |

### Valor de Retorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) método


Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice da planilha. |
| row | **int32_t** | A linha. |
| column | **int32_t** | A coluna. |

### Valor de Retorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String) método


Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice da planilha. |
| cellName | [System::String](../../../system/string/) | Nome da célula. |

### Valor de Retorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) método


Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice da planilha. |
| cellName | [System::String](../../../system/string/) | Nome da célula. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | O valor. |

### Valor de Retorno

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) método


Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice da planilha. |
| row | **int32_t** | A linha. |
| column | **int32_t** | A coluna. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | O valor. |

### Valor de Retorno

[Cell](../../../aspose.slides/cell/) object

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [String](../../../system/string/)
* Classe [IChartDataWorkbook](../)
* Classe [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)