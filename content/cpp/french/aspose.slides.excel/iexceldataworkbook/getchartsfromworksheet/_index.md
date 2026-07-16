---
title: GetChartsFromWorksheet()
second_title: Référence API Aspose.Slides pour C++
description: Récupère un dictionnaire contenant les index et les noms de tous les graphiques dans la feuille de calcul spécifiée d'un classeur Excel.
type: docs
weight: 27
url: /fr/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) méthode

Récupère un dictionnaire contenant les index et les noms de tous les charts dans la feuille de calcul spécifiée d'un [Excel](../../) workbook.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Le nom du worksheet à rechercher les charts. |

### Valeur de retour

Un dictionnaire où la clé est l'index du chart et la valeur est le nom du chart.

## Remarques



Exemple :
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [IExcelDataWorkbook](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)