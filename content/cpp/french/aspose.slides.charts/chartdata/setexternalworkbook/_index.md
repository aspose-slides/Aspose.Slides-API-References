---
title: SetExternalWorkbook()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit le classeur externe comme source de données pour le graphique. Les données du graphique seront mises à jour à partir du classeur cible.
type: docs
weight: 183
url: /fr/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) méthode

Définit le classeur externe comme source de données pour le graphique. [Chart](../../chart/) les données seront mises à jour à partir du classeur cible.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
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

## ChartData::SetExternalWorkbook(System::String, bool) méthode

Définit le classeur externe comme source de données pour le graphique.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Chemin vers le classeur cible |
| updateChartData | **bool** | Si la valeur est false, seul le chemin du classeur sera mis à jour. [Chart](../../chart/) les données ne seront pas chargées et mises à jour à partir du classeur cible. Peut être utilisé lorsque le classeur cible n'existe pas ou n'est pas disponible. Si la valeur est true, les données du graphique seront mises à jour à partir du classeur cible. |
## Remarques

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)