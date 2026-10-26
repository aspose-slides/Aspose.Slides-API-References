---
title: GetChartsFromWorksheet()
second_title: Referência da API Aspose.Slides para C++
description: Recupera um dicionário contendo os índices e nomes de todos os gráficos na planilha especificada de uma pasta de trabalho do Excel.
type: docs
weight: 40
url: /pt/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) method

Recupera um dicionário contendo os índices e nomes de todos os gráficos na planilha especificada de um [Excel](../../) workbook.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha onde procurar os gráficos. |

### Valor de Retorno

Um dicionário onde a chave é o índice do gráfico e o valor é o nome do gráfico.
## Observações

Exemplo: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [ExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)