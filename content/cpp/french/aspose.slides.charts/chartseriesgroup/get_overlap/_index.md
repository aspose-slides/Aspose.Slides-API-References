---
title: get_Overlap()
second_title: Référence de l'API Aspose.Slides for C++
description: Spécifie combien les barres et les colonnes doivent se chevaucher sur les graphiques 2-D, en pourcentage (de -100% à 100%).
type: docs
weight: 157
url: /fr/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() méthode


Spécifie combien les barres et les colonnes doivent se chevaucher sur les graphiques 2-D, en pourcentage (de -100 % à 100 %).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Remarques


* -100 % : espacement maximal (les barres sont complètement séparées).
* 0 % : les barres sont placées côte à côte sans chevauchement ni espacement.
* 100 % : chevauchement maximal (les barres se chevauchent complètement). Cette propriété est lecture/écriture **int8_t**.



L’exemple suivant montre comment définir le chevauchement pour un groupe de séries de graphique et rendre le graphique résultant sur un formulaire : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Définir le chevauchement à 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## Voir aussi

* Classe [ChartSeriesGroup](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)