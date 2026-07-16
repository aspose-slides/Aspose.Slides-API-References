---
title: SetExternalWorkbook()
second_title: Référence de l'API Aspose.Slides for C++
description: Définit un classeur externe comme source de données pour le diagramme. Les données du diagramme seront mises à jour à partir du classeur cible.
type: docs
weight: 196
url: /fr/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) méthode

Définit un classeur externe comme source de données pour le diagramme. [Chart](../../chart/) les données seront mises à jour à partir du classeur cible.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Chemin vers le classeur cible |

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) méthode

Définit un classeur externe comme source de données pour le diagramme.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Chemin vers le classeur cible |
| updateChartData | **bool** | Si la valeur est false, seul le chemin du classeur sera mis à jour. [Chart](../../chart/) les données ne seront pas chargées ni mises à jour à partir du classeur cible. Cela peut être utilisé lorsque le classeur cible n'existe pas ou n'est pas disponible. Si la valeur est true, les données du diagramme seront mises à jour à partir du classeur cible. |

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)