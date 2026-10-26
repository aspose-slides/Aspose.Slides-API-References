---
title: GetCell()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère une cellule de la feuille de calcul spécifiée en utilisant son indice et les coordonnées de la cellule.
type: docs
weight: 14
url: /fr/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) méthode


Récupère une cellule de la feuille de calcul spécifiée en utilisant son indice et les coordonnées de la cellule.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice de la feuille de calcul basé sur zéro. |
| row | **int32_t** | Indice de ligne de la cellule basé sur zéro. |
| column | **int32_t** | Indice de colonne de la cellule basé sur zéro. |

### Valeur de retour

La cellule à l'emplacement spécifié.
## Remarques



Exemple :
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) méthode


Récupère une cellule de la feuille de calcul spécifiée en utilisant son nom et les coordonnées de la cellule.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul. |
| row | **int32_t** | Indice de ligne de la cellule basé sur zéro. |
| column | **int32_t** | Indice de colonne de la cellule basé sur zéro. |

### Valeur de retour

La cellule à l'emplacement spécifié.
## Remarques



Exemple :
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) méthode


Récupère une cellule de la feuille de calcul spécifiée en utilisant son indice et le nom de cellule au format Excel (par ex., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indice de la feuille de calcul basé sur zéro. |
| cellName | [System::String](../../../system/string/) | La référence de cellule au format Excel (par ex., "A1", "C5"). |

### Valeur de retour

La cellule à l'emplacement spécifié.
## Remarques



Exemple :
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) méthode


Récupère une cellule de la feuille de calcul spécifiée en utilisant le nom de cellule au format Excel (par ex., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul. |
| cellName | [System::String](../../../system/string/) | La référence de cellule au format Excel (par ex., "A1", "C5"). |

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
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [IExcelDataWorkbook](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)