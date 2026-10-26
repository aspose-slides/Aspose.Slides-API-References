---
title: get_Row()
second_title: Aspose.Slides for C++ Référence de l'API
description: Obtient l'index basé sur zéro de la ligne dans la feuille de calcul où la cellule se trouve. Lecture seule int32_t.
type: docs
weight: 27
url: /fr/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() méthode

Obtient l'index basé sur zéro de la ligne dans la feuille de calcul où la cellule se trouve. Lecture seule **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Remarques

Exemple :
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## Voir aussi

* Classe [ExcelDataCell](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)