---
title: set_Overlap()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la quantité de chevauchement des barres et des colonnes sur les graphiques 2-D, exprimée en pourcentage (de -100% à 100%).
type: docs
weight: 196
url: /fr/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) méthode


Spécifie la quantité de chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100 % à 100 %).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Remarques


* -100%: Espacement maximal (les barres sont complètement séparées).
* 0%: Les barres sont placées côte à côte sans chevauchement ni espacement.
* 100%: Chevauchement maximal (les barres se chevauchent complètement). Cette propriété est en lecture/écriture **int8_t**.



L'exemple suivant montre comment définir le chevauchement pour un groupe de séries de graphique et rendre le graphique résultant sur un formulaire : 
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

* Classe [IChartSeriesGroup](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)