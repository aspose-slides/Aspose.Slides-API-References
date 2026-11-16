---
title: IChartSeriesGroup
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: แสดงกลุ่มของชุดข้อมูล.
type: docs
weight: 1970
url: /th/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup อินเทอร์เฟซ

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | อนุญาตให้รับ IChartComponent อินเทอร์เฟซฐาน. อ่านอย่างเดียว [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | ระบุว่าค่าขนาดฟองน้ำแสดงอย่างไรบนแผนภูมิบับเบิล. อ่าน/เขียน [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | ระบุขนาดของช่องในแผนภูมิดอนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). อ่าน/เขียน Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิพายหรือดอนัท, เป็นองศา (ทิศทางตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | รับหรือกำหนดระยะห่างระหว่างชุดข้อมูลในแผนภูมิมิติที่สาม, เป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | รับหรือกำหนดช่องว่างระหว่างกลุ่มแถบหรือคอลัมน์, เป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | เป็นจริงหากแผนภูมิมีเส้นชุดข้อมูล. ใช้กับแผนภูมิบาร์ซ้อนกันและ OfPie. อ่าน/เขียน Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | ระบุรูปแบบ HiLowLines. HiLowLines ใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละรายการในชุดมีสีที่ต่างกัน. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันเท่าใดในแผนภูมิกระดาน 2 มิติ, เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). - -100%: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์). - 0%: บาร์วางเคียงกันโดยไม่มีการทับซ้อนหรือระยะห่าง. - 100%: การทับซ้อนสูงสุด (บาร์ทับซ้อนกันทั้งหมด). คุณสมบัตินี้เป็นอ่าน/เขียน SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | ข้อมูลการแยกที่กำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกกำหนดเอง. มีจุดข้อมูลที่จะวาดในพายหรือบาร์ที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่านอย่างเดียว [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | บ่งชี้ว่าชุดข้อมูลในกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. อ่านอย่างเดียว Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie, เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | ส่งกลับคอลเลกชันอ่านอย่างเดียวของชุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | ส่งกลับประเภทของกลุ่มชุดข้อมูลนี้. อ่านอย่างเดียว [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | ให้เข้าถึงบาร์ขึ้น/ลงของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [`IUpDownBarsManager`](../iupdownbarsmanager). |

### หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มชุดข้อมูลมีคุณสมบัติบางอย่างของชุดข้อมูลที่เป็นร่วมกันสำหรับแต่ละชุดในกลุ่ม ("series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายเป็นอ่านอย่างเดียวในคลาส ChartSeries.

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartComponent](../ichartcomponent)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->