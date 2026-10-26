---
title: ChartTypeCharacterizer
second_title: Referência da API Aspose.Slides para C++
description: Auxiliar para obter informações adicionais sobre gráficos e séries a partir de seu ChartType.
type: docs
weight: 339
url: /pt/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer classe

Auxiliar para obter informações adicionais sobre gráficos e séries a partir de seu ChartType.

```cpp
class ChartTypeCharacterizer
```

## Métodos

| Method | Description |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | Retorna se há linhas de tendência de série para o tipo de série especificado. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | Retorna verdadeiro se *chartType* for um dos tipos de gráfico 2D. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | Retorna verdadeiro se *chartType* for um dos tipos de gráfico 3D. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de bar3DChart (colunas ou barras 3D). |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Área. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Barra. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Bolha. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de [Column](../../aspose.slides/column/). O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Rosquinha. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Linha. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Pizza. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Radar. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Dispersão. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Estoque. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | Retorna verdadeiro se chartType for um dos subtipos de Superfície. O conjunto de subtipos corresponde ao conjunto apropriado no PowerPoint (veja a caixa de diálogo "Change Chart Type" no PowerPoint): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | Retorna se barras de erro X são permitidas para o tipo de série especificado. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | Retorna se barras de erro Y são permitidas para o tipo de série especificado. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | Retorna se as coordenadas de tamanho da bolha podem ser usadas para o tipo de série especificado. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | Retorna se o tipo de série especificado usa coordenadas de valor. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | Retorna se o tipo de série especificado usa coordenadas de valor X. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | Retorna se o tipo de série especificado usa coordenadas de valor Y. |

## Veja Também

* Namespace [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)