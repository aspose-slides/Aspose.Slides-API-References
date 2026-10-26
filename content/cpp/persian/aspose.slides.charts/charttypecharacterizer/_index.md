---
title: ChartTypeCharacterizer
second_title: مرجع API Aspose.Slides برای C++
description: ابزاری برای دریافت اطلاعات اضافی درباره نمودارها و سری‌ها بر اساس ChartType آن.
type: docs
weight: 339
url: /fa/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer کلاس

ابزاری برای دریافت اطلاعات اضافی درباره نمودارها و سری‌ها بر اساس ChartType آن.

```cpp
class ChartTypeCharacterizer
```

## متدها

| Method | Description |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | برمی‌گرداند که آیا خطوط روند سری برای نوع سری مشخص وجود دارد یا خیر. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | در صورتی که *chartType* یکی از انواع نمودارهای 2D باشد، true برگردانده می‌شود. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | در صورتی که *chartType* یکی از انواع نمودارهای 3D باشد، true برگردانده می‌شود. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های bar3DChart (ستون‌ها یا میله‌های 3D) باشد، true برگردانده می‌شود. |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Area باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Bar باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Bubble باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های [Column](../../aspose.slides/column/) باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Doughnut باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Line باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Pie باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Radar باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Scatter باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Stock باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | در صورتی که chartType یکی از زیرنوع‌های Surface باشد، true برگردانده می‌شود. مجموعه زیرنوع‌ها با مجموعه مناسب در PowerPoint مطابقت دارد (به دیالگ "Change Chart Type" در PowerPoint مراجعه کنید): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | برمی‌گرداند که آیا نوارهای خطای X برای نوع سری مشخص اجازه دارند یا خیر. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | برمی‌گرداند که آیا نوارهای خطای Y برای نوع سری مشخص اجازه دارند یا خیر. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | برمی‌گرداند که آیا می‌توان از مختصات اندازه حباب برای نوع سری مشخص استفاده کرد یا خیر. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | برمی‌گرداند که آیا نوع سری مشخص از مختصات مقدار استفاده می‌کند یا خیر. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | برمی‌گرداند که آیا نوع سری مشخص از مختصات مقدار X استفاده می‌کند یا خیر. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | برمی‌گرداند که آیا نوع سری مشخص از مختصات مقدار Y استفاده می‌کند یا خیر. |
## موارد مرتبط

* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)