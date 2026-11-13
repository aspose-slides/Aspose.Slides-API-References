---
title: ChartSeries
second_title: Aspose.Sildes สำหรับ .NET API อ้างอิง
description: เป็นตัวแทนของชุดข้อมูลแผนภูมิ.
type: docs
weight: 1450
url: /th/aspose.slides.charts/chartseries/
---
## ChartSeries คลาส

แทนชุดข้อมูลแผนภูมิ

```csharp
public class ChartSeries : IChartSeries
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | ระบุรูปทรงของชุดข้อมูลในแผนภูมิแท่ง 3-มิติ การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของชุดข้อมูลเปลี่ยนโดยอัตโนมัติ อ่าน/เขียน [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | ระบุวิธีการแสดงค่าขนาดฟองบนแผนภูมิบับเบิล คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น) คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeScale อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | ส่งคืนแผนภูมิพาเรนต์ อ่านอย่างเดียว [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | ส่งคืนคอลเลกชันของจุดข้อมูลของชุดนี้ อ่านอย่างเดียว [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต) คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.DoughnutHoleSize อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | แสดง ErrorBars ของชุดข้อมูลที่ทิศทาง X ErrorBars ที่ทิศทาง X มีให้สำหรับชุดข้อมูลประเภท area, bar, scatter และ bubble สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D) ในกรณีค่าที่กำหนดเอง ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)) อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | แสดง ErrorBars ของชุดข้อมูลที่ทิศทาง Y ErrorBars ที่ทิศทาง Y มีให้สำหรับชุดข้อมูลประเภท area, bar, line, scatter และ bubble สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D) ในกรณีค่าที่กำหนดเอง ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)) อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | ระยะทางของชิ้นพายที่เปิดจากศูนย์กลางของแผนภูมิพาย แสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย อ่าน/เขียน Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | ระบุมุมของชิ้นพายหรือโดนัทชิ้นแรก เป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา) คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.FirstSliceAngle อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | ส่งคืนรูปแบบของชุดข้อมูล อ่านอย่างเดียว [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | ส่งคืนหรือกำหนดระยะทางเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์ระหว่างชุดข้อมูลในแผนภูมิ 3D คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.GapDepth อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | ระบุระยะห่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์ คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.GapWidth อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | กำหนดว่ามีเส้นชุดข้อมูลสำหรับชุดนี้และชุดที่เกี่ยวข้องหรือไม่ คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.HasSeriesLines อ่าน/เขียน เพื่อเปลี่ยนค่า ใช้คุณสมบัติ ParentSeriesGroup.SeriesLinesFormat สำหรับรูปแบบเส้นชุดข้อมูล อ่านอย่างเดียว Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่ คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars.HasUpDownBars อ่าน/เขียน เพื่อเปลี่ยนค่า ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars สำหรับรูปแบบแถบขึ้น/ลง อ่านอย่างเดียว Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | ระบุสีทึบกลับด้านสำหรับชุดข้อมูล เพื่อใช้การตั้งค่าสีตั้งค่า FillType ของรูปแบบชุดข้อมูลเป็น FillType.Solid. อ่าน/เขียน [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | ระบุว่าแท่ง, คอลัมน์ หรือชุดข้อมูลบับเบิลจะกลับสีหากค่าเป็นลบ อ่าน/เขียน Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละจุดในชุดข้อมูลมีสีต่างกัน คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.IsColorVaried อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | ส่งคืน Labels ของชุดข้อมูล อ่านอย่างเดียว [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | เครื่องหมาย อ่านอย่างเดียว [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | ส่งคืนชื่อชุดข้อมูล อ่านอย่างเดียว [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. อ่าน/เขียน String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. อ่าน/เขียน String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. อ่าน/เขียน String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. อ่าน/เขียน String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | ส่งคืนลำดับของชุดข้อมูล อ่าน/เขียน Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | ระบุเปอร์เซ็นต์การซ้อนทับของแท่งและคอลัมน์บนแผนภูมิ 2-D (ตั้งแต่ –100% ถึง 100%) คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ เป็นการฉายของคุณสมบัติของกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้ !:ParentSeriesGroup.Overlap อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | แสดงเค้าโครงของป้ายหมวดหมู่พาเรนต์ ใช้ได้เฉพาะกับแผนภูมิ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. อ่านอย่างเดียว [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | ระบุวิธีกำหนดจุดข้อมูลที่อยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie นี้เป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – การฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.PieSplitBy อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง มีจุดข้อมูลที่ควรวาดในพายหรือแท่งที่สอง อ่านอย่างเดียว [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | ระบุค่าที่ใช้กำหนดจุดข้อมูลที่อยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie ใช้ร่วมกับคุณสมบัติ PieSplitBy คุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.PieSplitPosition อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | ระบุว่าชุดข้อมูลนี้ถูกพล็อตบนแกนรองหรือไม่ อ่าน/เขียน Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | แสดงวิธีการ quartile ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | แสดงรายการ legend ที่เกี่ยวข้องกับชุดข้อมูลนี้ อ่านอย่างเดียว [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์) คุณสมบัตินี้ไม่เฉพาะกับชุดข้อมูลนี้เท่านั้น แต่เป็นของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลพาเรนต์ – การฉายของคุณสมบัติในกลุ่มที่เกี่ยวข้อง ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์ ใช้คุณสมบัติ ParentSeriesGroup.SecondPieSize อ่าน/เขียน เพื่อเปลี่ยนค่า อ่านอย่างเดียว UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | แสดงเส้นเชื่อม ใช้ได้เฉพาะกับแผนภูมิ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | แสดงจุดในเนื้อหา จริงหากจุดในเนื้อหาถูกแสดงบนแผนภูมิ BoxAndWhisker ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker อ่าน/เขียน Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | แสดงเส้นค่าเฉลี่ย จริงหากเส้นค่าเฉลี่ยถูกแสดงบนแผนภูมิ BoxAndWhisker ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker อ่าน/เขียน Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | แสดงมาร์คเกอร์ค่าเฉลี่ย จริงหากมาร์คเกอร์ค่าเฉลี่ยถูกแสดงบนแผนภูมิ BoxAndWhisker ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker อ่าน/เขียน Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | แสดงจุดข้อมูลนอกเหนือ จริงหากจุดข้อมูลนอกเหนือถูกแสดงบนแผนภูมิ BoxAndWhisker ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker อ่าน/เขียน Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | แสดงการทำให้เส้นโค้งเรียบ จริงหากการทำให้เส้นโค้งเรียบเปิดใช้งานสำหรับแผนภูมิ line หรือ scatter ใช้ได้เฉพาะกับแผนภูมิ line และ scatter ที่เชื่อมต่อด้วยเส้น อ่าน/เขียน Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | คอลเลกชันของเส้นเทรนด์ของชุดข้อมูล อ่านอย่างเดียว [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | ส่งคืนชนิดของชุดข้อมูลนี้ อ่าน/เขียน [`ChartType`](../charttype). |

## วิธีการ

| Name | Description |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | ส่งคืนสีอัตโนมัติของชุดข้อมูลตามดัชนีชุดข้อมูลและสไตล์แผนภูมิ สีนี้จะใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartSeries](../ichartseries)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->