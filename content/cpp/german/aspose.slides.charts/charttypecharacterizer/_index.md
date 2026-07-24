---
title: ChartTypeCharacterizer
second_title: Aspose.Slides für C++ API-Referenz
description: Hilfsmittel zum Abrufen zusätzlicher Informationen über Diagramme und Serien anhand ihres ChartType.
type: docs
weight: 339
url: /de/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer Klasse


Hilfsmittel zum Abrufen zusätzlicher Informationen über Diagramme und Serien anhand ihres ChartType.

```cpp
class ChartTypeCharacterizer
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | Gibt zurück, ob für den angegebenen Serientyp Trendlinien vorhanden sind. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | Gibt true zurück, wenn *chartType* einer der 2D-Diagrammtypen ist. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | Gibt true zurück, wenn *chartType* einer der 3D-Diagrammtypen ist. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Untertypen von bar3DChart ist (3D-Säulen oder -Balken). |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Area-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Bar-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Bubble-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der [Column](../../aspose.slides/column/)-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Doughnut-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Line-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Pie-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Radar-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Scatter-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Stock-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | Gibt true zurück, wenn chartType einer der Surface-Untertypen ist. Die Menge der Untertypen entspricht der entsprechenden Menge in PowerPoint (siehe \"Change Chart Type\"-Dialog in PowerPoint): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | Gibt zurück, ob Fehlerbalken X für den angegebenen Serientyp zulässig sind. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | Gibt zurück, ob Fehlerbalken Y für den angegebenen Serientyp zulässig sind. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | Gibt zurück, ob Bubble-Größenkoordinaten für den angegebenen Serientyp verwendet werden können. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | Gibt zurück, ob der angegebene Serientyp Wertkoordinaten verwendet. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | Gibt zurück, ob der angegebene Serientyp X-Wertkoordinaten verwendet. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | Gibt zurück, ob der angegebene Serientyp Y-Wertkoordinaten verwendet. |
## Siehe auch

* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)