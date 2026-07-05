---
title: ChartSeries
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แทนชุดข้อมูลของแผนภูมิ.
type: docs
weight: 1440
url: /th/aspose.slides.charts/chartseries/
---
## ChartSeries คลาส

แทนชุดข้อมูลของแผนภูมิ

```csharp
public class ChartSeries : IChartSeries
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | ระบุรูปร่างของชุดข้อมูลของแผนภูมิแท่ง 3-D. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของชุดข้อมูลเปลี่ยนโดยอัตโนมัติ. อ่าน/เขียน [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | ระบุวิธีการแสดงค่าขนาดฟองบนแผนภูมิฟอง. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation แบบอ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | ระบุปัจจัยสเกลสำหรับแผนภูมิฟอง (สามารถอยู่ระหว่าง 0-และ 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeScale แบบอ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | คืนค่าแผนภูมิแม่. อ่านอย่างเดียว [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | คืนค่าคอลเลกชันของจุดข้อมูลของชุดข้อมูลนี้. อ่านอย่างเดียว [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | ระบุขนาดของช่องว่างในแผนภูมิโค้ง (อาจอยู่ระหว่าง 10-และ 90 เปอร์เซ็นต์ของขนาดของพื้นที่พล็อต). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | แทน ErrorBars ของชุดข้อมูลที่มีทิศทาง X. ErrorBars ที่มีทิศทาง X สามารถใช้ได้กับชุดข้อมูลประเภท area, bar, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีค่าที่กำหนดเองใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | แทน ErrorBars ของชุดข้อมูลที่มีทิศทาง Y. ErrorBars ที่มีทิศทาง Y สามารถใช้ได้กับชุดข้อมูลประเภท area, bar, line, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีค่าที่กำหนดเองใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | ระยะห่างของสไลซ์พายที่เปิดจากศูนย์กลางของแผนภูมิพาย แสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางของพาย. อ่าน/เขียน Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | ระบุมุมของสไลซ์แรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากบน, 0-ถึง 360 องศา). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | คืนค่าฟอร์แมตของชุดข้อมูล. อ่านอย่างเดียว [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างเครื่องหมายระหว่างชุดข้อมูลในแผนภูมิ 3D. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | ระบุช่องว่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | กำหนดว่ามีเส้นชุดข้อมูลสำหรับชุดข้อมูลนี้และชุดข้อมูลที่เกี่ยวข้องหรือไม่. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | ระบุสีทึบแบบกลับด้านสำหรับชุดข้อมูล. เพื่อใช้การตั้งค่าสีตั้งค่า FillType ของฟอร์แมตชุดข้อมูลเป็น FillType.Solid. อ่าน/เขียน [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | ระบุว่าชุดข้อมูลแท่ง, คอลัมน์หรือฟองจะกลับสีหากค่าติดลบ. อ่าน/เขียน Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | ระบุว่าเครื่องหมายข้อมูลแต่ละตัวในชุดข้อมูลมีสีต่างกัน. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | คืนค่า Labels ของชุดข้อมูล. อ่านอย่างเดียว [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | เครื่องหมาย. อ่านอย่างเดียว [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | คืนชื่อชุดข้อมูล. อ่านอย่างเดียว [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. อ่าน/เขียน String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. อ่าน/เขียน String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. อ่าน/เขียน String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. อ่าน/เขียน String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | คืนค่าลำดับของชุดข้อมูล. อ่าน/เขียน Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | ระบุว่าบาร์และคอลัมน์ทับซ้อนกันเท่าไหร่ในแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | แทนการจัดวางของป้ายชื่อหมวดหมู่แม่. ใช้ได้เฉพาะแผนภูมิ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. อ่านอย่างเดียว [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | ระบุวิธีการกำหนดว่า datapoints ใดอยู่ในพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มี datapoints ที่ต้องวาดในพายหรือบาร์ที่สองของแผนภูมิ. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่ม. อ่านอย่างเดียว [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | ระบุค่าที่ใช้กำหนดว่า datapoints ใดอยู่ในพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่ม. อ่านอย่างเดียว Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | ระบุว่าชุดข้อมูลนี้ถูกพล็อตบนแกนรองหรือไม่. อ่าน/เขียน Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | แทนวิธีการ quartile. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | แทนรายการคำอธิบายที่เกี่ยวข้องกับชุดข้อมูลนี้. อ่านอย่างเดียว [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5-และ 200 เปอร์เซ็นต์). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้เท่านั้น แต่ของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | แทนเส้นเชื่อมต่อ. ใช้ได้เฉพาะแผนภูมิ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | แทนจุดใน. เป็นจริงหากจุดในแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | แทนเส้นค่าเฉลี่ย. เป็นจริงหากเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | แทนเครื่องหมายค่าเฉลี่ย. เป็นจริงหากเครื่องหมายค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | แทนจุดนอกเหนือ. เป็นจริงหากจุดนอกเหนือแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | แทนการทำให้เส้นโค้งเรียบ. เป็นจริงหากการทำให้เส้นโค้งเรียบเปิดใช้งานสำหรับแผนภูมิเส้นหรือ scatter. ใช้ได้เฉพาะแผนภูมิ line และ scatter ที่เชื่อมต่อด้วยเส้น. อ่าน/เขียน Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | คอลเลกชันของเส้นแนวโน้มของชุดข้อมูล. อ่านอย่างเดียว [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | คืนค่าประเภทของชุดข้อมูลนี้. อ่าน/เขียน [`ChartType`](../charttype). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | คืนค่าสีอัตโนมัติของชุดข้อมูลโดยอิงตามดัชนีชุดข้อมูลและสไตล์แผนภูมิ. สีนี้จะใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartSeries](../ichartseries)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->