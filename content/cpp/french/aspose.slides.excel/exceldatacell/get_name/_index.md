---
title: get_Name()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le nom de la cellule de données du graphique.
type: docs
weight: 14
url: /fr/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() méthode


Obtient le nom de la cellule de données du graphique.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Remarques


Exemple : 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ExcelDataCell](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)