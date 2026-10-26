---
title: GetCell()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a célula que pode ser usada para séries ou categorias de gráfico
type: docs
weight: 27
url: /pt/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) método

Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nome da planilha. |
| row | **int32_t** | A linha. |
| column | **int32_t** | A coluna. |

### Valor de Retorno

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) método

Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice da planilha. |
| row | **int32_t** | A linha. |
| column | **int32_t** | A coluna. |

### Valor de Retorno

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) método

Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice da planilha. |
| cellName | [System::String](../../../system/string/) | Nome da célula. |

### Valor de Retorno

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) método

Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice da planilha. |
| cellName | [System::String](../../../system/string/) | Nome da célula. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | O valor. |

### Valor de Retorno

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) método

Obtém a célula que pode ser usada para séries ou categorias de gráfico

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
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
* Classe [ChartDataWorkbook](../)
* Classe [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)