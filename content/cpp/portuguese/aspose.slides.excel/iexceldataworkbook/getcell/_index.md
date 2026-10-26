---
title: GetCell()
second_title: Aspose.Slides for C++ Referência da API
description: Recupera uma célula da planilha especificada usando seu índice e as coordenadas da célula.
type: docs
weight: 14
url: /pt/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) método

Recupera uma célula da planilha especificada usando seu índice e as coordenadas da célula.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice baseado em zero da planilha. |
| row | **int32_t** | Índice da linha baseado em zero da célula. |
| column | **int32_t** | Índice da coluna baseado em zero da célula. |

### Valor de retorno

A célula no local especificado.

## Observações



Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) método

Recupera uma célula da planilha especificada usando seu nome e as coordenadas da célula.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha. |
| row | **int32_t** | Índice da linha baseado em zero da célula. |
| column | **int32_t** | Índice da coluna baseado em zero da célula. |

### Valor de retorno

A célula no local especificado.

## Observações



Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) método

Recupera uma célula da planilha especificada usando seu índice e o nome da célula no estilo Excel (por exemplo, \"B2\").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice baseado em zero da planilha. |
| cellName | [System::String](../../../system/string/) | A referência de célula no estilo Excel (por exemplo, \"A1\", \"C5\"). |

### Valor de retorno

A célula no local especificado.

## Observações



Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) método

Recupera uma célula da planilha especificada usando o nome da célula no estilo Excel (por exemplo, \"B2\").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha. |
| cellName | [System::String](../../../system/string/) | A referência de célula no estilo Excel (por exemplo, \"A1\", \"C5\"). |

### Valor de retorno

A célula no local especificado.

## Observações



Exemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IExcelDataCell](../../iexceldatacell/)
* Classe [IExcelDataWorkbook](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)