---
title: ChartSeries
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดง series ของแผนภูมิ.
type: docs
weight: 1440
url: /th/aspose.slides.charts/chartseries/
---
## ChartSeries คลาส

แสดง series ของแผนภูมิ

```csharp
public class ChartSeries : IChartSeries
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | ระบุรูปทรงของ series ของแผนภูมิแท่ง 3-มิติ การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของ series เปลี่ยนโดยอัตโนมัติ อ่าน/เขียน [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | ระบุวิธีการแสดงค่าขนาดฟองบนแผนภูมิบับเบิล นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทุกตัวในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0-และ 300 เปอร์เซ็นต์ของขนาดเริ่มต้น) นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeScale อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | ส่งคืนแผนภูมิแม่ อ่านอย่างเดียว [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | ส่งคืนคอลเลกชันของจุดข้อมูลของ series นี้ อ่านอย่างเดียว [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | ระบุขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 10-และ 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต) นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.DoughnutHoleSize อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | แสดง ErrorBars ของ series ที่มีทิศทาง X. ErrorBars ที่มีทิศทาง X มีให้ใช้กับ series ประเภท area, bar, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3 มิติ) ในกรณีที่ต้องการค่ากำหนดเอง ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)) อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | แสดง ErrorBars ของ series ที่มีทิศทาง Y. ErrorBars ที่มีทิศทาง Y มีให้ใช้กับ series ประเภท area, bar, line, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3 มิติ) ในกรณีที่ต้องการค่ากำหนดเอง ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)) อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | ระยะของชิ้นพายเปิดจากศูนย์กลางของแผนภูมิปายแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางของพาย อ่าน/เขียน Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | ระบุมุมของชิ้นพายหรือโดนัทแรกในหน่วยองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา) นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.FirstSliceAngle อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | ส่งคืนรูปแบบของ series. อ่านอย่างเดียว [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | ส่งคืนหรือกำหนดระยะทางเป็นเปอร์เซ็นต์ของความกว้างของ marker ระหว่าง series ของข้อมูลในแผนภูมิ 3 มิติ นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.GapDepth อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | ระบุช่องว่างระหว่างกลุ่มบาร์หรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างบาร์หรือคอลัมน์ นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.GapWidth อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | ระบุว่ามีเส้น series หรือไม่สำหรับ series นี้และ series ที่เกี่ยวข้อง นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.HasSeriesLines อ่าน/เขียน เพื่อเปลี่ยนค่า ใช้คุณสมบัติ ParentSeriesGroup.SeriesLinesFormat สำหรับกำหนดรูปแบบเส้น series อ่านอย่างเดียว Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | ระบุว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่ นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars.HasUpDownBars อ่าน/เขียน เพื่อเปลี่ยนค่า ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars สำหรับกำหนดรูปแบบแถบขึ้น/ลง อ่านอย่างเดียว Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | ระบุสีทึบกลับสำหรับ series เพื่อใช้การตั้งค่าสีให้ตั้ง FillType ของรูปแบบ series เป็น FillType.Solid อ่าน/เขียน [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | ระบุว่าบาร์, คอลัมน์หรือ series ฟองจะกลับสีของมันหากค่าเป็นลบ อ่าน/เขียน Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | ระบุว่าตัวทำเครื่องหมายข้อมูลแต่ละจุดใน series มีสีที่แตกต่างกัน นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.IsColorVaried อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | ส่งคืน Labels ของ series. อ่านอย่างเดียว [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | ตัวทำเครื่องหมาย. อ่านอย่างเดียว [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | ส่งคืนชื่อ series. อ่านอย่างเดียว [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. อ่าน/เขียน String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. อ่าน/เขียน String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. อ่าน/เขียน String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. อ่าน/เขียน String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | ส่งคืนลำดับของ series. อ่าน/เขียน Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | ระบุว่าบาร์และคอลัมน์ทับซ้อนกันเท่าไหร่บนแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%) นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่มพาเรนท์ ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว เพื่อเปลี่ยนค่าให้ใช้คุณสมบัติ !:ParentSeriesGroup.Overlap อ่าน/เขียน อ่านอย่างเดียว SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | แสดงเลย์เอาต์ของป้ายชื่อหมวดแม่. ใช้ได้เฉพาะกับแผนภูมิ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. อ่านอย่างเดียว [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.PieSplitBy อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง มีจุดข้อมูลที่ต้องวาดในพายหรือบาร์ที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie นี้เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม อ่านอย่างเดียว [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie ใช้ร่วมกับคุณสมบัติ PieSplitBy นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.PieSplitPosition อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | ระบุว่ series นี้ถูกพล็อตบนแกนรองหรือไม่ อ่าน/เขียน Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | แสดงวิธีควอร์ไทล์ ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | แสดงรายการใน legend ที่เกี่ยวข้องกับ series นี้ อ่านอย่างเดียว [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (อาจอยู่ระหว่าง 5-และ 200 เปอร์เซ็นต์) นี่เป็นคุณสมบัติไม่เพียงของ series นี้เท่านั้นแต่ของ series ทั้งหมดในกลุ่ม series พาเรนท์ - เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนท์ ใช้คุณสมบัติ ParentSeriesGroup.SecondPieSize อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | แสดงเส้นเชื่อมต่อ ใช้ได้เฉพาะกับแผนภูมิ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | แสดงจุดภายใน เป็น true หากจุดภายในแสดงบนแผนภูมิ BoxAndWhisker ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker อ่าน/เขียน Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | แสดงเส้นค่าเฉลี่ย เป็น true หากเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker อ่าน/เขียน Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | แสดงเครื่องหมายค่าเฉลี่ย เป็น true หากเครื่องหมายค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker อ่าน/เขียน Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | แสดงจุด outlier เป็น true หากจุด outlier แสดงบนแผนภูมิ BoxAndWhisker ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker อ่าน/เขียน Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | แสดงการทำให้เส้นโค้งเรียบ เป็น true หากเปิดการทำให้เส้นโค้งเรียบสำหรับแผนภูมิ line หรือ scatter ใช้ได้เฉพาะกับแผนภูมิ line และ scatter ที่เชื่อมต่อด้วยเส้น อ่าน/เขียน Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | คอลเลกชันของเส้นแนวโน้ม series. อ่านอย่างเดียว [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | ส่งคืนประเภทของ series นี้. อ่าน/เขียน [`ChartType`](../charttype). |

## วิธีการ

| Name | Description |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | ส่งคืนสีอัตโนมัติของ series ที่ขึ้นอยู่กับดัชนี series และสไตล์ของแผนภูมิ สีนี้จะถูกใช้โดยค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartSeries](../ichartseries)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->