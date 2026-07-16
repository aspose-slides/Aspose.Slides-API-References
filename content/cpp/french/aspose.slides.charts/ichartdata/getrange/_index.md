---
title: GetRange()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la plage de données du graphique.
type: docs
weight: 170
url: /fr/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() méthode

Obtient la plage de données du graphique.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```

### Valeur de retour

Formule de la plage de données des cellules. Par ex. : "Sheet1!$A$1:$C$4"

## Remarques

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)