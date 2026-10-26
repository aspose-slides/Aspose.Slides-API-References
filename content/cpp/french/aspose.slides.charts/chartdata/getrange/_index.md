---
title: GetRange()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la plage de données du graphique.
type: docs
weight: 157
url: /fr/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() méthode


Obtient la plage de données du graphique.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Valeur de retour

Formule de plage de données des cellules. Par exemple : "Sheet1!$A$1:$C$4"
## Remarques




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)