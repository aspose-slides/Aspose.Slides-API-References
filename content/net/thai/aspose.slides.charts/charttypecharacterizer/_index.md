---
title: ChartTypeCharacterizer
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: ตัวช่วยสำหรับรับข้อมูลเพิ่มเติมเกี่ยวกับแผนภูมิและซีรีส์โดยใช้ ChartType.
type: docs
weight: 1510
url: /th/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer คลาส

Helper for getting additional information about charts and series by its ChartType.

```csharp
public static class ChartTypeCharacterizer
```

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| static [HasSeriesTrendLines](../../aspose.slides.charts/charttypecharacterizer/hasseriestrendlines)(ChartType) | ส่งคืนว่ามีเส้นแนวโน้มของซีรีส์สำหรับประเภทซีรีส์ที่ระบุหรือไม่. |
| static [Is2DChart](../../aspose.slides.charts/charttypecharacterizer/is2dchart)(ChartType) | ส่งคืน true หาก *chartType* เป็นหนึ่งในประเภทแผนภูมิ 2D. |
| static [Is3DChart](../../aspose.slides.charts/charttypecharacterizer/is3dchart)(ChartType) | ส่งคืน true หาก *chartType* เป็นหนึ่งในประเภทแผนภูมิ 3D. |
| static [IsBar3DChart](../../aspose.slides.charts/charttypecharacterizer/isbar3dchart)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ bar3DChart (คอลัมน์ 3D หรือบาร์ 3D). |
| static [IsChartTypeArea](../../aspose.slides.charts/charttypecharacterizer/ischarttypearea)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Area. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): Area, PercentsStackedArea, PercentsStackedArea3D, StackedArea, StackedArea3D, Area3D. |
| static [IsChartTypeBar](../../aspose.slides.charts/charttypecharacterizer/ischarttypebar)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Bar. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): ClusteredBar, ClusteredBar3D, PercentsStackedBar, PercentsStackedBar3D, StackedBar, StackedBar3D, ClusteredHorizontalCone, ClusteredHorizontalCylinder, ClusteredHorizontalPyramid, StackedHorizontalCone, StackedHorizontalCylinder, StackedHorizontalPyramid, PercentsStackedHorizontalCone, PercentsStackedHorizontalCylinder, PercentsStackedHorizontalPyramid. |
| static [IsChartTypeBubble](../../aspose.slides.charts/charttypecharacterizer/ischarttypebubble)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Bubble. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): Bubble, BubbleWith3D. |
| static [IsChartTypeColumn](../../aspose.slides.charts/charttypecharacterizer/ischarttypecolumn)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Column. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): ClusteredColumn, ClusteredColumn3D, ClusteredCone, ClusteredCylinder, ClusteredPyramid, PercentsStackedColumn, PercentsStackedColumn3D, PercentsStackedCone, PercentsStackedCylinder, PercentsStackedPyramid, StackedColumn, StackedColumn3D, StackedCone, StackedCylinder, StackedPyramid, Column3D, Cylinder3D, Cone3D, Pyramid3D. |
| static [IsChartTypeDoughnut](../../aspose.slides.charts/charttypecharacterizer/ischarttypedoughnut)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Doughnut. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): Doughnut, ExplodedDoughnut. |
| static [IsChartTypeLine](../../aspose.slides.charts/charttypecharacterizer/ischarttypeline)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Line. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): Line, LineWithMarkers, PercentsStackedLine, PercentsStackedLineWithMarkers, StackedLine, StackedLineWithMarkers, Line3D. |
| static [IsChartTypePie](../../aspose.slides.charts/charttypecharacterizer/ischarttypepie)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Pie. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): BarOfPie, ExplodedPie, ExplodedPie3D, Pie, Pie3D, PieOfPie. |
| static [IsChartTypeRadar](../../aspose.slides.charts/charttypecharacterizer/ischarttyperadar)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Radar. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): FilledRadar, Radar, RadarWithMarkers. |
| static [IsChartTypeScatter](../../aspose.slides.charts/charttypecharacterizer/ischarttypescatter)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Scatter. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): ScatterWithMarkers, ScatterWithSmoothLines, ScatterWithSmoothLinesAndMarkers, ScatterWithStraightLines, ScatterWithStraightLinesAndMarkers. |
| static [IsChartTypeStock](../../aspose.slides.charts/charttypecharacterizer/ischarttypestock)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Stock. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): HighLowClose, OpenHighLowClose, VolumeHighLowClose, VolumeOpenHighLowClose. |
| static [IsChartTypeSurface](../../aspose.slides.charts/charttypecharacterizer/ischarttypesurface)(ChartType) | ส่งคืน true หาก chartType เป็นหนึ่งในชนิดย่อยของ Surface. ชุดชนิดย่อยสอดคล้องกับชุดที่เหมาะสมใน PowerPoint (ดูการสนทนา "Change Chart Type" ใน PowerPoint): Surface3D, WireframeSurface3D, Contour, WireframeContour. |
| static [IsErrorBarsXAllowed](../../aspose.slides.charts/charttypecharacterizer/iserrorbarsxallowed)(ChartType) | ส่งคืนว่าตำแหน่งบาร์ผิดพลาด X สามารถใช้ได้สำหรับประเภทซีรีส์ที่ระบุ. |
| static [IsErrorBarsYAllowed](../../aspose.slides.charts/charttypecharacterizer/iserrorbarsyallowed)(ChartType) | ส่งคืนว่าตำแหน่งบาร์ผิดพลาด Y สามารถใช้ได้สำหรับประเภทซีรีส์ที่ระบุ. |
| static [IsSeriesUsesBubbleSizeCoordinate](../../aspose.slides.charts/charttypecharacterizer/isseriesusesbubblesizecoordinate)(ChartType) | ส่งคืนว่าพิกัดขนาดบับเบิลสามารถใช้ได้สำหรับประเภทซีรีส์ที่ระบุ. |
| static [IsSeriesUsesValueCoordinate](../../aspose.slides.charts/charttypecharacterizer/isseriesusesvaluecoordinate)(ChartType) | ส่งคืนว่าประเภทซีรีส์ที่ระบุใช้พิกัดค่า. |
| static [IsSeriesUsesXValueCoordinate](../../aspose.slides.charts/charttypecharacterizer/isseriesusesxvaluecoordinate)(ChartType) | ส่งคืนว่าประเภทซีรีส์ที่ระบุใช้พิกัดค่า X. |
| static [IsSeriesUsesYValueCoordinate](../../aspose.slides.charts/charttypecharacterizer/isseriesusesyvaluecoordinate)(ChartType) | ส่งคืนว่าประเภทซีรีส์ที่ระบุใช้พิกัดค่า Y. |

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->