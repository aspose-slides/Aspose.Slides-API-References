---
title: get_Column()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient l'index basé sur zéro de la colonne dans la feuille de calcul où se trouve la cellule. Lecture seule int32_t.
type: docs
weight: 40
url: /fr/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() méthode


Obtient l'index basé sur zéro de la colonne dans la feuille de calcul où se trouve la cellule. Lecture seule **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Remarques


Exemple :
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Voir aussi

* Classe [IExcelDataCell](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)