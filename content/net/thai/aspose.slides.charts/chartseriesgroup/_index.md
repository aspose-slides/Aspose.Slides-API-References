---
title: ChartSeriesGroup
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: แทนกลุ่มของซีรีส์.
type: docs
weight: 1470
url: /th/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup คลาส

แทนกลุ่มของซีรีส์

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | ระบุวิธีที่ค่าขนาดฟองแสดงบนแผนภูมิบับเบิล. อ่าน/เขียน [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | ระบุค่าอัตราส่วนสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | ส่งคืนแผนภูมิแม่. อ่านอย่างเดียว [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | ระบุขนาดของช่องว่างในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่วาด). อ่าน/เขียน Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิพายหรือโดนัท, หน่วยเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | รับหรือกำหนดระยะห่างระหว่างชุดข้อมูลในแผนภูมิโค้ด 3 มิติ, เป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | รับหรือกำหนดช่องว่างระหว่างกลุ่มแถบหรือคอลัมน์, เป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | เป็นจริงถ้าแผนภูมิมีเส้นซีรีส์. ใช้กับแผนภูมิแถบซ้อนและ OfPie. อ่าน/เขียน Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | ระบุรูปแบบ HiLowLines. HiLowLines ใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | ระบุว่าแต่ละมาร์กเกอร์ข้อมูลในซีรีส์มีสีที่แตกต่างกัน. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันเท่าไรบนแผนภูมิกระดาน 2 มิติ, เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). - -100%: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์). - 0%: บาร์วางเคียงกันโดยไม่มีการทับซ้อนหรือช่องว่าง. - 100%: การทับซ้อนสูงสุด (บาร์ทับกันทั้งหมด). คุณสมบัตินี้อ่าน/เขียน SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | ข้อมูลการแยกส่วนที่กำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกส่วนกำหนดเอง. ประกอบด้วยจุดข้อมูลที่ควรวาดในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่านอย่างเดียว [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | ระบุค่าที่จะใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | บ่งชี้ว่าซีรีส์ของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. อ่านอย่างเดียว Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | ระบุขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie, เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | ส่งคืนคอลเลกชันของซีรีส์. อ่านอย่างเดียว [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | ส่งคืนประเภทของกลุ่มซีรีส์นี้. อ่านอย่างเดียว [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | ให้การเข้าถึงแถบขึ้น/ลงของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [`IUpDownBarsManager`](../iupdownbarsmanager). |

### หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของซีรีส์มีบางคุณสมบัติของซีรีส์ที่เป็นร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม ("series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายเป็นอ่านอย่างเดียวในคลาส ChartSeries.

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartSeriesGroup](../ichartseriesgroup)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->