---
title: ChartSeriesGroup
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: แสดงถึงกลุ่มของชุดข้อมูล.
type: docs
weight: 1460
url: /th/aspose.slides.charts/chartseriesgroup/
---
## คลาส ChartSeriesGroup

Represents group of series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | ระบุวิธีการแสดงค่าขนาดฟองบนแผนภูมิฟองอากาศ. อ่าน/เขียน [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | ระบุตัวคูณสเกลสำหรับแผนภูมิฟองอากาศ (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | คืนค่าแผนภูมิแม่. อ่านอย่างเดียว [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). อ่าน/เขียน Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | รับหรือกำหนดมุมของชิ้นส่วนแรกของแผนภูมิวงกลมหรือโดนัท, หน่วยเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | รับหรือกำหนดระยะทาง, เป็นเปอร์เซ็นต์ของความกว้างของเครื่องหมาย, ระหว่างชุดข้อมูลในแผนภูมิ 3 มิติ. อ่าน/เขียน UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | ระบุช่องว่างระหว่างกลุ่มแถบหรือคอลัมน์, เป็นเปอร์เซ็นต์ของความกว้างของแถบหรือคอลัมน์. อ่าน/เขียน UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | เป็นจริงถ้าแผนภูมิมีเส้นชุดข้อมูล. ใช้กับแผนภูมิแถบซ้อนและ OfPie. อ่าน/เขียน Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | ระบุรูปแบบ HiLowLines. HiLowLines ใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | ระบุว่าตัวทำเครื่องหมายข้อมูลแต่ละตัวในชุดข้อมูลมีสีที่ต่างกัน. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | ระบุว่าบาร์และคอลัมน์จะทับซ้อนกันเท่าใดบนแผนภูมิ 2-มิติ, เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). - -100%: ระยะห่างสูงสุด (บาร์แยกจากกันทั้งหมด). - 0%: บาร์วางเคียงกันโดยไม่มีการทับซ้อนหรือระยะห่าง. - 100%: การทับซ้อนสูงสุด (บาร์ทับซ้อนกันทั้งหมด). คุณลักษณะนี้อ่าน/เขียน SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. ประกอบด้วยจุดข้อมูลที่จะถูกวาดในพายหรือแถบที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่านอย่างเดียว [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | ระบุว่าชุดข้อมูลของกลุ่มนี้ถูกแสดงบนแกนรองหรือไม่. อ่านอย่างเดียว Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | ระบุขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie, เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | คืนคอลเลกชันของชุดข้อมูล. อ่านอย่างเดียว [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | คืนค่าชนิดของกลุ่มชุดข้อมูลนี้. อ่านอย่างเดียว [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | ให้เข้าถึงแถบ up/down ของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [`IUpDownBarsManager`](../iupdownbarsmanager). |

### หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของชุดข้อมูลมีบางคุณสมบัติของชุดข้อมูลที่เป็นที่ใช้ร่วมกันสำหรับแต่ละชุดข้อมูลในกลุ่ม ("คุณสมบัติของกลุ่มชุดข้อมูล"). "คุณสมบัติของกลุ่มชุดข้อมูล" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน. แต่ละ "คุณสมบัติของกลุ่มชุดข้อมูล" สามารถมีการฉายภาพอ่านอย่างเดียวในคลาส ChartSeries.

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartSeriesGroup](../ichartseriesgroup)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->