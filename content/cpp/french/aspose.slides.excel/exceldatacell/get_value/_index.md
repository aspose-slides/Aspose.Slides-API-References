---
title: get_Value()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la valeur contenue dans la cellule Excel.
type: docs
weight: 1
url: /fr/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() méthode


Obtient la valeur contenue dans la cellule [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Remarques


Exemple:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ExcelDataCell](../)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)