---
title: ChartTypeCharacterizer
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตัวช่วยสำหรับรับข้อมูลเพิ่มเติมเกี่ยวกับแผนภูมิและชุดข้อมูลตาม ChartType ของมัน.
type: docs
weight: 339
url: /th/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer คลาส

ตัวช่วยสำหรับรับข้อมูลเพิ่มเติมเกี่ยวกับแผนภูมิและชุดข้อมูลตาม ChartType ของมัน.

```cpp
class ChartTypeCharacterizer
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | ตรวจสอบว่ามีเส้นแนวโน้มของชุดข้อมูลสำหรับประเภทชุดข้อมูลที่ระบุหรือไม่ |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | คืนค่า true หาก *chartType* อยู่ในประเภทแผนภูมิ 2D |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | คืนค่า true หาก *chartType* อยู่ในประเภทแผนภูมิ 3D |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ bar3DChart (คอลัมน์หรือแถบ 3D) |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Area. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Bar. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Bubble. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ [Column](../../aspose.slides/column/). เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Doughnut. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Line. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Pie. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Radar. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Scatter. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Stock. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | คืนค่า true หาก chartType อยู่ในประเภทย่อยของ Surface. เซตประเภทย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการโต้ตอบ "Change Chart Type" ใน PowerPoint): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | ตรวจสอบว่าบาร์ข้อผิดพลาด X ได้รับอนุญาตสำหรับประเภทชุดข้อมูลที่ระบุหรือไม่ |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | ตรวจสอบว่าบาร์ข้อผิดพลาด Y ได้รับอนุญาตสำหรับประเภทชุดข้อมูลที่ระบุหรือไม่ |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | ตรวจสอบว่าค่าพิกัดขนาดฟองอาจใช้ได้สำหรับประเภทชุดข้อมูลที่ระบุหรือไม่ |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | ตรวจสอบว่าประเภทชุดข้อมูลที่ระบุใช้ค่าพิกัดหรือไม่ |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | ตรวจสอบว่าประเภทชุดข้อมูลที่ระบุใช้ค่าพิกัด X หรือไม่ |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | ตรวจสอบว่าประเภทชุดข้อมูลที่ระบุใช้ค่าพิกัด Y หรือไม่ |
## ดูเพิ่มเติม

* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)