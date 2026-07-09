---
title: IChartSeriesGroup
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: แสดงถึงกลุ่มของซีรีส์.
type: docs
weight: 1950
url: /th/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup อินเทอร์เฟซ

แสดงถึงกลุ่มของซีรีส์

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | อนุญาตให้ดึงอินเทอร์เฟซ IChartComponent พื้นฐานได้. อ่านอย่างเดียว [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | กำหนดวิธีที่ค่าขนาดของบับเบิลถูกแสดงบนแผนภูมิบับเบิล. อ่าน/เขียน [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | กำหนดสเกลแฟกเตอร์สำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | กำหนดขนาดของช่องว่างในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). อ่าน/เขียน Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | รับหรือกำหนดมุมของชิ้นพายหรือโดนัทชิ้นแรก, เป็นองศา (ตามเข็มนอนจากบน, จาก 0 ถึง 360 องศา). อ่าน/เขียน UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | ส่งคืนหรือกำหนดระยะห่าง, เป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์, ระหว่างชุดข้อมูลในแผนภูมิ 3 มิติ. อ่าน/เขียน UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | กำหนดช่องว่างระหว่างกลุ่มแถบหรือคอลัมน์, เป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. อ่าน/เขียน UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | เป็นจริงหากแผนภูมิมีเส้นซีรีส์. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน/เขียน Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | กำหนดรูปแบบ HiLowLines. HiLowLines ถูกใช้ร่วมกับ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose chart types. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | กำหนดให้แต่ละมาร์คเกอร์ข้อมูลในซีรีส์มีสีที่ต่างกัน. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | กำหนดว่าบาร์และคอลัมน์จะทับซ้อนกันบนแผนภูมิ 2-D อย่างไร, เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). -100%: ระยะห่างสูงสุด (บาร์แยกจากกันทั้งหมด). 0%: บาร์วางข้างกันโดยไม่มีการทับซ้อนหรือช่องว่าง. 100%: ทับซ้อนสูงสุด (บาร์ทับซ้อนกันทั้งหมด). คุณสมบัตินี้เป็นอ่าน/เขียน SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | กำหนดวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ควรวาดในพายหรือแถบที่สอง. อ่านอย่างเดียว [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | กำหนดค่าที่จะใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | บ่งบอกว่าซีรีส์ของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. อ่านอย่างเดียว Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | กำหนดขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie, เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | ส่งคืนคอลเลกชันแบบอ่านอย่างเดียวของซีรีส์แผนภูมิ. อ่านอย่างเดียว [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | ส่งคืนประเภทของกลุ่มซีรีส์นี้. อ่านอย่างเดียว [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | ให้การเข้าถึงบาร์ขึ้น/ลงของแผนภูมิ Line- หรือ Stock-chart. อ่านอย่างเดียว [`IUpDownBarsManager`](../iupdownbarsmanager). |

### หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับ ChartSeriesGroupCollection คลาสและ CombinableSeriesTypesGroup enum. 2) กลุ่มของซีรีส์มีคุณสมบัติของซีรีส์บางอย่างที่เป็นร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม ("คุณสมบัติของกลุ่มซีรีส์"). "คุณสมบัติของกลุ่มซีรีส์" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน. แต่ละ "คุณสมบัติของกลุ่มซีรีส์" สามารถมีการฉายภาพแบบอ่านอย่างเดียวในคลาส ChartSeries.

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartComponent](../ichartcomponent)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->