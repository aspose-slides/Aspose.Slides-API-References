---
title: GetChartsFromWorksheet()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera un dizionario contenente gli indici e i nomi di tutti i grafici nel foglio di lavoro specificato di una cartella di lavoro Excel.
type: docs
weight: 40
url: /it/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) metodo

Recupera un dizionario contenente gli indici e i nomi di tutti i grafici nel foglio di lavoro specificato di una [Excel](../../) cartella di lavoro.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro da cercare per i grafici. |

### Valore di ritorno

Un dizionario in cui la chiave è l'indice del grafico e il valore è il nome del grafico.

## Osservazioni



Esempio: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [ExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Libreria [Aspose.Slides](../../../)