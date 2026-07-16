---
title: get_Value()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Obtient la valeur contenue dans la cellule Excel. Lecture seule System::Object."
type: docs
weight: 1
url: /fr/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() méthode


Obtient la valeur contenue dans la cellule [Excel](../../). Lecture seule [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Remarques


Exemple : 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [IExcelDataCell](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)