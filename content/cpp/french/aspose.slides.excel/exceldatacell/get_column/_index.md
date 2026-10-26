---
title: get_Column()
second_title: Référence API Aspose.Slides pour C++
description: Obtient l'indice basé sur zéro de la colonne dans la feuille de calcul où se trouve la cellule. Lecture seule int32_t.
type: docs
weight: 40
url: /fr/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() méthode

Obtient l'indice basé sur zéro de la colonne dans la feuille de calcul où se trouve la cellule. Lecture seule **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Voir aussi

* Classe [ExcelDataCell](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)