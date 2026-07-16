---
title: GetChartsFromWorksheet()
second_title: Référence de l'API Aspose.Slides for C++
description: Récupère un dictionnaire contenant les index et les noms de tous les graphiques dans la feuille de calcul spécifiée d'un classeur Excel.
type: docs
weight: 40
url: /fr/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) méthode

Récupère un dictionnaire contenant les index et les noms de tous les graphiques dans la feuille de calcul spécifiée d'un classeur [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul pour rechercher les graphiques. |

### Valeur de retour

Un dictionnaire où la clé est l'index du graphique et la valeur est le nom du graphique.

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
* Classe [ExcelDataWorkbook](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)