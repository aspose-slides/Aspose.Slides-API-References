---
title: get_Name()
second_title: Aspose.Slides pour C++ Référence API
description: "Obtient le nom de la cellule de données du graphique. Lecture seule System::String."
type: docs
weight: 14
url: /fr/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() méthode


Obtient le nom de la cellule de données du graphique. Lecture seule [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IExcelDataCell](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)