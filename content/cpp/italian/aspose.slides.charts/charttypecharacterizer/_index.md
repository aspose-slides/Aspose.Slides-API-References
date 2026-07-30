---
title: ChartTypeCharacterizer
second_title: Riferimento API di Aspose.Slides per C++
description: Assistente per ottenere informazioni aggiuntive sui grafici e le serie tramite il suo ChartType.
type: docs
weight: 339
url: /it/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer classe

Helper per ottenere informazioni aggiuntive su grafici e serie tramite il suo ChartType.

```cpp
class ChartTypeCharacterizer
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | Restituisce se esistono linee di tendenza per la serie specificata. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei tipi di grafico 2D. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei tipi di grafico 3D. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi bar3DChart (colonne o barre 3D). |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Area. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Bar. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Bubble. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi [Column](../../aspose.slides/column/). L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Doughnut. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Line. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Pie. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Radar. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Scatter. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Stock. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | Restituisce true se *chartType* è uno dei sottotipi Surface. L'insieme dei sottotipi corrisponde a quello appropriato in PowerPoint (vedi finestra di dialogo “Change Chart Type” in PowerPoint): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | Restituisce se le barre di errore X sono consentite per il tipo di serie specificato. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | Restituisce se le barre di errore Y sono consentite per il tipo di serie specificato. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | Restituisce se le coordinate della dimensione delle bolle possono essere utilizzate per il tipo di serie specificato. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | Restituisce se il tipo di serie specificato utilizza coordinate valore. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | Restituisce se il tipo di serie specificato utilizza coordinate valore X. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | Restituisce se il tipo di serie specificato utilizza coordinate valore Y. |

## Vedi anche

* Namespace [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)