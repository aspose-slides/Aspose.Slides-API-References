---
title: GetCell()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et les coordonnées de la cellule.
type: docs
weight: 27
url: /fr/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) method

Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et les coordonnées de la cellule.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index de la feuille de calcul basé sur zéro. |
| row | **int32_t** | Index de ligne basé sur zéro de la cellule. |
| column | **int32_t** | Index de colonne basé sur zéro de la cellule. |

### Valeur de retour

La cellule à l'emplacement spécifié.

## Remarques

Exemple :
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) method

Récupère une cellule de la feuille de calcul spécifiée en utilisant son nom et les coordonnées de la cellule.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul. |
| row | **int32_t** | Index de ligne basé sur zéro de la cellule. |
| column | **int32_t** | Index de colonne basé sur zéro de la cellule. |

### Valeur de retour

La cellule à l'emplacement spécifié.

## Remarques

Exemple :
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) method

Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et le nom de cellule de style Excel (par ex., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index de la feuille de calcul basé sur zéro. |
| cellName | [System::String](../../../system/string/) | La référence de cellule de style Excel (par ex., "A1", "C5"). |

### Valeur de retour

La cellule à l'emplacement spécifié.

## Remarques

Exemple :
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) method

Récupère une cellule de la feuille de calcul spécifiée en utilisant le nom de cellule de style Excel (par ex., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul. |
| cellName | [System::String](../../../system/string/) | La référence de cellule de style Excel (par ex., "A1", "C5"). |

### Valeur de retour

La cellule à l'emplacement spécifié.

## Remarques

Exemple :
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IExcelDataCell](../../iexceldatacell/)
* Classe [ExcelDataWorkbook](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::Excel](../../)
* Bibliothèque [Aspose.Slides](../../../)