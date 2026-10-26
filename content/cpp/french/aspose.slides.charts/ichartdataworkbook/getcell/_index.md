---
title: GetCell()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la cellule qui peut être utilisée pour les séries ou les catégories de diagramme
type: docs
weight: 40
url: /fr/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) méthode


Obtient la cellule qui peut être utilisée pour les séries ou les catégories de diagramme

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nom de la feuille de calcul. |
| row | **int32_t** | La ligne. |
| column | **int32_t** | La colonne. |

### Valeur de retour

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) méthode


Obtient la cellule qui peut être utilisée pour les séries ou les catégories de diagramme

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index de la feuille de calcul. |
| row | **int32_t** | La ligne. |
| column | **int32_t** | La colonne. |

### Valeur de retour

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String) méthode


Obtient la cellule qui peut être utilisée pour les séries ou les catégories de diagramme

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index de la feuille de calcul. |
| cellName | [System::String](../../../system/string/) | Nom de la cellule. |

### Valeur de retour

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) méthode


Obtient la cellule qui peut être utilisée pour les séries ou les catégories de diagramme

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index de la feuille de calcul. |
| cellName | [System::String](../../../system/string/) | Nom de la cellule. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | La valeur. |

### Valeur de retour

[Cell](../../../aspose.slides/cell/) object

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) méthode


Obtient la cellule qui peut être utilisée pour les séries ou les catégories de diagramme

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Index de la feuille de calcul. |
| row | **int32_t** | La ligne. |
| column | **int32_t** | La colonne. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | La valeur. |

### Valeur de retour

[Cell](../../../aspose.slides/cell/) object

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [String](../../../system/string/)
* Classe [IChartDataWorkbook](../)
* Classe [Object](../../../system/object/)
* Espace de noms [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)