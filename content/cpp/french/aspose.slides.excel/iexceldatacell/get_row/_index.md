---
title: get_Row()
second_title: Référence API Aspose.Slides pour C++
description: Obtient l'indice de ligne basé sur zéro dans la feuille de calcul où la cellule est située. Lecture seule int32_t.
type: docs
weight: 27
url: /fr/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() méthode

Renvoie l'indice de ligne basé sur zéro dans la feuille de calcul où la cellule est située. Lecture seule **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Remarques


Exemple:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```



## Voir aussi

* Classe [IExcelDataCell](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)