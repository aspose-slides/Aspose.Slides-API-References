---
title: ChartSeriesGroup
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: แสดงถึงกลุ่มของซีรีส์.
type: docs
weight: 1460
url: /th/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup คลาส

แทนกลุ่มของ series

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | ระบุวิธีที่ค่าขนาดฟองอากาศแสดงบนแผนภูมิกลุ่มฟอง. อ่าน/เขียน [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | ระบุตัวคูณสเกลสำหรับแผนภูมิกลุ่มฟอง (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | คืนค่าแผนภูมิต้นแบบ. อ่านอย่างเดียว [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | ระบุขนาดของรูในแผนภูมุน้ำพุ (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). อ่าน/เขียน Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | รับหรือกำหนดมุมของชิ้นส่วนแรกของแผนภูมิพายหรือแผนภูมุน้ำพุ, เป็นองศา (ตามเข็มนาฬิกาตั้งจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | คืนค่า หรือกำหนดระยะห่าง, เป็นเปอร์เซ็นต์ของความกว้างของมาร์กเกอร์, ระหว่างชุดข้อมูลในแผนภูมุมิติที่สาม. อ่าน/เขียน UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | ระบุช่องว่างระหว่างกลุ่มแถบหรือคอลัมน์, เป็นเปอร์เซ็นต์ของความกว้างของแถบหรือคอลัมน์. อ่าน/เขียน UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True หากแผนภูคิมีเส้นซีรีส์. ใช้กับแผนภูมิแถบซ้อนและ OfPie. อ่าน/เขียน Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | ระบุมาตรฐาน HiLowLines. HiLowLines ใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | ระบุว่าตัวทำเครื่องหมายข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | ระบุว่าบาร์และคอลัมน์ควรทับกันเท่าใดบนแผนภูมิตาราง 2 มิติ, เป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). - -100%: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์). - 0%: บาร์วางเคียงกันโดยไม่มีการทับหรือช่องว่าง. - 100%: การทับสูงสุด (บาร์ทับกันอย่างสมบูรณ์). คุณสมบัตินี้อ่าน/เขียน SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | ระบุวิธีกำหนดว่าข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | ข้อมูลการแยกส่วนแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกส่วนกำหนดเอง. มีจุดข้อมูลที่ต้องวาดในพายหรือแถบที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่านอย่างเดียว [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | ระบุค่าที่จะใช้กำหนดว่าข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | ระบุกลุ่มซีรีส์นี้ถูกพล็อตบนแกนรองหรือไม่. อ่านอย่างเดียว Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | ระบุขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie, เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | คืนค่าชุดของซีรีส์. อ่านอย่างเดียว [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | คืนค่าประเภทของกลุ่มซีรีส์นี้. อ่านอย่างเดียว [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | ให้การเข้าถึงบาร์ขึ้น/ลงของแผนภูมิเส้นหรือแผนภูมิสต็อก. อ่านอย่างเดียว [`IUpDownBarsManager`](../iupdownbarsmanager). |

### หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของซีรีส์มีคุณสมบัติของซีรีส์บางอย่างที่เป็นร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม ("series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส ChartSeries.

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartSeriesGroup](../ichartseriesgroup)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->