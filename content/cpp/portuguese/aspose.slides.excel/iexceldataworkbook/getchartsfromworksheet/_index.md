---
title: GetChartsFromWorksheet()
second_title: Referência da API Aspose.Slides para C++
description: Recupera um dicionário contendo os índices e nomes de todos os gráficos na planilha especificada de uma pasta de trabalho Excel.
type: docs
weight: 27
url: /pt/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) method

Recupera um dicionário contendo os índices e nomes de todos os gráficos na planilha especificada de uma pasta de trabalho [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | O nome da planilha a ser pesquisada por gráficos. |

### Valor de retorno

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

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)