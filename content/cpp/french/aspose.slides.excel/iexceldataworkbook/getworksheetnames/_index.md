---
title: GetWorksheetNames()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère les noms de toutes les feuilles de calcul contenues dans le classeur Excel.
type: docs
weight: 40
url: /fr/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() method


Récupère les noms de toutes les feuilles de calcul contenues dans le classeur [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### Valeur de retour

Une liste de noms de feuilles de calcul
## Remarques



Exemple:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IList](../../../system.collections.generic/ilist/)
* Classe [String](../../../system/string/)
* Classe [IExcelDataWorkbook](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)