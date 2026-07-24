---
title: ChartTypeCharacterizer
second_title: Aspose.Slides for C++ API Referansı
description: Chart ve seriler hakkında ChartType kullanarak ek bilgi almak için yardımcı.
type: docs
weight: 339
url: /tr/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer sınıf

Chart ve seriler hakkında ek bilgi almak için ChartType kullanarak yardımcı.

```cpp
class ChartTypeCharacterizer
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | Belirtilen seri tipi için seri trend çizgileri olup olmadığını döndürür. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | Eğer *chartType*  2D grafik tiplerinden biriyse true döndürür. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | Eğer *chartType*  3D grafik tiplerinden biriyse true döndürür. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | Eğer chartType bar3DChart alt tiplerinden biriyse (3D sütunlar veya çubuklar) true döndürür. |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | Eğer chartType Area alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | Eğer chartType Bar alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | Eğer chartType Bubble alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | Eğer chartType [Column](../../aspose.slides/column/) alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | Eğer chartType Doughnut alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | Eğer chartType Line alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | Eğer chartType Pie alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | Eğer chartType Radar alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | Eğer chartType Scatter alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | Eğer chartType Stock alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | Eğer chartType Surface alt tiplerinden biriyse true döndürür. Alt tipler kümesi PowerPoint'teki ilgili kümeye karşılık gelir (PowerPoint'te "Change Chart Type" iletişim kutusuna bakın): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | Belirtilen seri tipi için X hata çubuklarına izin verilip verilmediğini döndürür. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | Belirtilen seri tipi için Y hata çubuklarına izin verilip verilmediğini döndürür. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | Belirtilen seri tipi için baloncuk boyutu koordinatlarının kullanılabilir olup olmadığını döndürür. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | Belirtilen seri tipinin değer koordinatlarını kullanıp kullanmadığını döndürür. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | Belirtilen seri tipinin X değer koordinatlarını kullanıp kullanmadığını döndürür. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | Belirtilen seri tipinin Y değer koordinatlarını kullanıp kullanmadığını döndürür. |

## Ayrıca Bakınız

* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)