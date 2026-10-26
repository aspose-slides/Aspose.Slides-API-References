---
title: GetChartsFromWorksheet()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera un dizionario contenente gli indici e i nomi di tutti i grafici nel foglio di lavoro specificato di una cartella di lavoro Excel.
type: docs
weight: 27
url: /it/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) metodo

Recupera un dizionario contenente gli indici e i nomi di tutti i grafici nel foglio di lavoro specificato di una cartella di lavoro [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro in cui cercare i grafici. |

### Valore restituito

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
* Classe [IExcelDataWorkbook](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Libreria [Aspose.Slides](../../../)