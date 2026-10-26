---
title: GetCells()
second_title: Référence API Aspose.Slides pour C++
description: Récupère une collection de cellules du classeur qui correspondent à la formule spécifiée.
type: docs
weight: 1
url: /fr/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) méthode

Récupère une collection de cellules du classeur qui correspondent à la formule spécifiée.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Une formule ou expression de plage (p. ex., "Sheet1!A1:B3") utilisée pour identifier les cellules cibles. |
| skipHiddenCells | **bool** | Si **true**, les cellules masquées (p. ex., dans des lignes ou colonnes masquées) seront exclues du résultat. |

### Valeur de retour

Une liste en lecture seule de cellules correspondant à la formule spécifiée.
## Remarques



Exemple : 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Classe [IExcelDataCell](../../iexceldatacell/)
* Classe [String](../../../system/string/)
* Classe [IExcelDataWorkbook](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)