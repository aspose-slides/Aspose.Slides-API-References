---
title: IChartSeries
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: เป็นตัวแทนของชุดข้อมูลแผนภูมิ.
type: docs
weight: 1950
url: /th/aspose.slides.charts/ichartseries/
---
## IChartSeries อินเทอร์เฟซ

Represents a chart series.

```csharp
public interface IChartSeries : IChartComponent
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IChartComponent พื้นฐาน. อ่านอย่างเดียว [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | ระบุรูปร่างของชุดข้อมูลของแผนภูมิแท่ง 3 มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของชุดข้อมูลเปลี่ยนโดยอัตโนมัติ. อ่าน/เขียน [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | ระบุว่าค่าขนาดฟองอากาศแสดงอย่างไรบนแผนภูมิบับเบิล. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0–300 % ของขนาดเริ่มต้น). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeScale อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | คืนคอลเลกชันของจุดข้อมูลของชุดนี้. อ่านอย่างเดียว [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10–90 % ของขนาดพื้นที่พล็อต). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.DoughnutHoleSize อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | แสดง ErrorBars ของชุดข้อมูลที่มีทิศทาง X. ErrorBars ที่มีทิศทาง X มีให้สำหรับชุดข้อมูลประเภท area, bar, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้คืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีค่าที่กำหนดเอง ให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | แสดง ErrorBars ของชุดข้อมูลที่มีทิศทาง Y. ErrorBars ที่มีทิศทาง Y มีให้สำหรับชุดข้อมูลประเภท area, bar, line, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้คืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีค่าที่กำหนดเอง ให้ใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | ระยะห่างของชิ้นพายเปิดจากศูนย์กลางของแผนภูมิปายแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. อ่าน/เขียน Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | ระบุมุมของชิ้นพายหรือดอนัทชิ้นแรกในองศา (ตามเข็มนาฬิกาจากตำแหน่งบน, 0–360°). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.FirstSliceAngle อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | คืนรูปแบบของชุดข้อมูล. อ่านอย่างเดียว [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | คืนหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คระหว่างชุดข้อมูลในแผนภูมิเชิงสามมิติ. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.GapDepth อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | ระบุระยะห่างระหว่างคลัสเตอร์ของแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.GapWidth อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | กำหนดว่ามีเส้นเชื่อมชุดข้อมูลสำหรับชุดนี้และชุดที่เกี่ยวข้องหรือไม่. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.HasSeriesLines อ่าน/เขียน เพื่อเปลี่ยนค่า. ใช้คุณสมบัติ ParentSeriesGroup.SeriesLinesFormat เพื่อกำหนดรูปแบบเส้นเชื่อม. อ่านอย่างเดียว Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | กำหนดว่ากราฟเส้นหรือกราฟหุ้นมีแถบขึ้น/ลงหรือไม่. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars.HasUpDownBars อ่าน/เขียน เพื่อเปลี่ยนค่า. ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars เพื่อกำหนดรูปแบบแถบขึ้น/ลง. อ่านอย่างเดียว Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | กำหนดสีทึบกลับด้านสำหรับชุดข้อมูล. เพื่อตั้งค่าสีให้ตั้งค่า FillType ของรูปแบบชุดข้อมูลเป็น FillType.Solid. อ่าน/เขียน [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | กำหนดให้ชุดแท่ง, คอลัมน์หรือบับเบิลกลับสีถ้าค่าติดลบ. อ่าน/เขียน Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | กำหนดว่าแต่ละมาร์คในชุดข้อมูลจะมีสีแตกต่างกัน. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.IsColorVaried อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | คืน Labels ของชุดข้อมูล. อ่านอย่างเดียว [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | คืนมาร์คของชุดข้อมูล. อ่านอย่างเดียว [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | คืนชื่อชุดข้อมูล. อ่านอย่างเดียว [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | คืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของชุดข้อมูล. อ่าน/เขียน String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | คืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าของชุดข้อมูล. อ่าน/เขียน String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | คืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า x ของชุดข้อมูล. อ่าน/เขียน String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | คืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า y ของชุดข้อมูล. อ่าน/เขียน String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | คืนลำดับของชุดข้อมูล. อ่าน/เขียน Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | ระบุว่าคลับและคอลัมน์ทับกันเท่าไหร่ในแผนภูมิ 2-D, เป็นเปอร์เซ็นต์ (จาก -100 % ถึง 100 %). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์. เป็นการแสดงผลของคุณสมบัติในกลุ่มพาเรนต์, ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. เพื่อเปลี่ยนค่าให้ใช้คุณสมบัติ ParentSeriesGroup.Overlap อ่าน/เขียน. อ่านอย่างเดียว SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | แสดงการจัดเรียงของป้ายชื่อประเภทพาเรนต์. ใช้ได้เฉพาะแผนภูมิ Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | คืนกลุ่มชุดข้อมูลพาเรนต์. อ่านอย่างเดียว [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.PieSplitBy อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | ข้อมูลการแยกส่วนที่กำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกส่วนกำหนดเอง. มีจุดข้อมูลที่ควรวาดในพายหรือแท่งที่สอง. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | ระบุค่าที่ใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.PieSplitPosition อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | ระบุว่าชุดข้อมูลนี้ถูกวาดบนแกนค่าที่สองหรือไม่. อ่าน/เขียน Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | แสดงวิธีการ quartile. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | แสดงรายการ legend ที่เกี่ยวกับชุดนี้. อ่านอย่างเดียว [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie, เป็นเปอร์เซ็นต์ของขนาดพายแรก (5–200 %). นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้ แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลพาเรนต์ - เป็นการแสดงผลของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลพาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.SecondPieSize อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | แสดงเส้นเชื่อมต่อ. ใช้ได้เฉพาะแผนภูมิ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | แสดงจุดภายใน. จริงหากจุดภายในแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | แสดงมาร์คค่าเฉลี่ย. จริงหากเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | แสดงมาร์คค่าเฉลี่ย. จริงหากมาร์คค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | แสดงจุด outlier. จริงหากจุด outlier แสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | แสดงการทำให้เส้นโค้งเรียบ. จริงหากเปิดการทำให้เส้นโค้งเรียบสำหรับแผนภูมิเส้นหรือ scatter. ใช้ได้เฉพาะแผนภูมิเส้นและ scatter ที่เชื่อมด้วยเส้น. อ่าน/เขียน Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | คอลเลกชันของเส้นแนวโน้มชุดข้อมูล. อ่านอย่างเดียว [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | คืนประเภทของชุดนี้. อ่าน/เขียน [`ChartType`](../charttype). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | คืนสีอัตโนมัติของชุดข้อมูลตามดัชนีชุดข้อมูลและสไตล์แผนภูมิ. สีนี้จะถูกใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartComponent](../ichartcomponent)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->