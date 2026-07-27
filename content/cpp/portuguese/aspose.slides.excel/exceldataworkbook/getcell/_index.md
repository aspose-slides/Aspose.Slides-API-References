---
title: GetCell()
second_title: Referência da API Aspose.Slides para C++
description: Recupera uma célula da planilha especificada usando seu índice e as coordenadas da célula.
type: docs
weight: 27
url: /pt/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) método


Recupera uma célula da planilha especificada usando seu índice e coordenadas da célula.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice baseado em zero da planilha. |
| row | **int32_t** | Índice de linha baseado em zero da célula. |
| column | **int32_t** | Índice de coluna baseado em zero da célula. |

### Valor de Retorno

A célula na localização especificada.
## Observações



Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) método


Recupera uma célula da planilha especificada usando seu nome e coordenadas da célula.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha. |
| row | **int32_t** | Índice de linha baseado em zero da célula. |
| column | **int32_t** | Índice de coluna baseado em zero da célula. |

### Valor de Retorno

A célula na localização especificada.
## Observações



Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) método


Recupera uma célula da planilha especificada usando seu índice e o nome da célula no estilo Excel (por exemplo, "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice baseado em zero da planilha. |
| cellName | [System::String](../../../system/string/) | A referência da célula no estilo Excel (por exemplo, "A1", "C5"). |

### Valor de Retorno

A célula na localização especificada.
## Observações



Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) método


Recupera uma célula da planilha especificada usando o nome da célula no estilo Excel (por exemplo, "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha. |
| cellName | [System::String](../../../system/string/) | A referência da célula no estilo Excel (por exemplo, "A1", "C5"). |

### Valor de Retorno

A célula na localização especificada.
## Observações



Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [ExcelDataWorkbook](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)