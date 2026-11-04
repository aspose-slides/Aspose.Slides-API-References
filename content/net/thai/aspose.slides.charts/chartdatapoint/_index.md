---
title: ChartDataPoint
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: แสดงจุดข้อมูลของซีรีส์.
type: docs
weight: 1340
url: /th/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint คลาส

แสดงถึงจุดข้อมูลของซีรีส์.

```csharp
public class ChartDataPoint : IChartDataPoint
```


## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | กำหนดความสูงจริงขององค์ประกอบแผนภูมิ เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง อ่าน Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | กำหนดความกว้างจริงขององค์ประกอบแผนภูมิ เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง อ่าน Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | กำหนดตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมบนซ้ายของแผนภูมิ เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง อ่าน Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | กำหนดตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมบนซ้ายของแผนภูมิ เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง อ่าน Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. อ่านอย่างเดียว [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | รับขนาดฟองสบู่ที่แคชของจุดข้อมูลแผนภูมิ อ่านอย่างเดียว [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | รับค่าที่แคชของจุดข้อมูลแผนภูมิ อ่านอย่างเดียว [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | รับค่า X ที่แคชของจุดข้อมูลแผนภูมิ อ่านอย่างเดียว [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | รับค่า Y ที่แคชของจุดข้อมูลแผนภูมิ อ่านอย่างเดียว [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | คืนค่าตัวสีของจุดข้อมูลแผนภูมิ ใช้กับแผนภูมิแผนที่ อ่านอย่างเดียว [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | คืนค่าตัวบ่งชี้ของระดับจุดข้อมูล ใช้กับซีรีส์ Treeamp และ Sunburst การจัดลำดับระดับจุดข้อมูลเริ่มที่ศูนย์. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | แสดงค่าบาร์ข้อผิดพลาดของซีรีส์ในกรณีประเภทค่า Custom อ่านอย่างเดียว [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | กำหนดปริมาณที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย อ่าน/เขียน Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | แสดงคุณสมบัติการจัดรูปแบบ อ่าน/เขียน [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | กำหนดให้จุดข้อมูลกลับสีของมันหากค่าติดลบ อ่าน/เขียน Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | กำหนดว่าฟองสบู่มีเอฟเฟ็กต์ 3 มิติถูกนำไปใช้ อ่าน/เขียน Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. อ่านอย่างเดียว [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | กำหนดตัวทำเครื่องหมายข้อมูล อ่านอย่างเดียว [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | คุณสมบัติของรายการคำอธิบายที่สอดคล้องในกรณีประเภทแผนภูมิจากรายการนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. อ่านอย่างเดียว [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | ตั้งค่าจุดข้อมูลเป็นผลรวม ใช้เฉพาะประเภทซีรีส์ Waterfall เท่านั้น. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | คืนค่าขนาดของจุดข้อมูลแผนภูมิ ใช้กับแผนภูมิ Treemap และ Sunburst อ่านอย่างเดียว [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. อ่านอย่างเดียว [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. อ่านอย่างเดียว [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. อ่านอย่างเดียว [`IDoubleChartValue`](../idoublechartvalue). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | คืนค่าสีอัตโนมัติของจุดข้อมูลโดยอิงจากดัชนีซีรีส์ ดัชนีจุดข้อมูล คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์ของแผนภูมิ สีนี้จะถูกใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | ลบ DataPoint จากซีรีส์ของแผนภูมิ. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartDataPoint](../ichartdatapoint)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->