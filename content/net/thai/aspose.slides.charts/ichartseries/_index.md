---
title: IChartSeries
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: เป็นตัวแทนของซีรีส์แผนภูมิ.
type: docs
weight: 1930
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
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | อนุญาตให้ดึงอินเทอร์เฟซ IChartComponent พื้นฐาน. อ่านอย่างเดียว [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | ระบุรูปร่างของซีรีส์ในแผนภูมิบาร์ 3 มิติ. การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของซีรีส์เปลี่ยนแปลงโดยอัตโนมัติ. อ่าน/เขียน [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | ระบุวิธีการแสดงค่าขนาดบับเบิลบนแผนภูมิบับเบิล. นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeScale อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | ส่งคืนคอลเลกชันของจุดข้อมูลของซีรีส์นี้. อ่านอย่างเดียว [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.DoughnutHoleSize อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | แทน ErrorBars ของซีรีส์ที่มีทิศทาง X. ErrorBars ที่มีทิศทาง X มีให้ใช้กับซีรีส์ประเภท area, bar, scatter และ bubble. สำหรับประเภทแผนภูมิอื่นคุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีค่าที่กำหนดเอง ใช้คอลเลกชัน DataPoints เพื่อระบุมค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | แทน ErrorBars ของซีรีส์ที่มีทิศทาง Y. ErrorBars ที่มีทิศทาง Y มีให้ใช้กับซีรีส์ประเภท area, bar, line, scatter และ bubble. สำหรับประเภทแผนภูมิอื่นคุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีค่าที่กำหนดเอง ใช้คอลเลกชัน DataPoints เพื่อระบุมค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | ระยะห่างของชิ้นพายที่เปิดออกจากศูนย์กลางของแผนภูมิปาย แสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางของพาย. อ่าน/เขียน Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | ระบุมุมของชิ้นพายหรือโดนัทชิ้นแรกเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศ). นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.FirstSliceAngle อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | ส่งคืนรูปแบบของซีรีส์. อ่านอย่างเดียว [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | ส่งคืนหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างของมาร์คเกอร์ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3D. นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.GapDepth อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | ระบุพื้นที่ว่างระหว่างคลัสเตอร์ของบาร์หรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของบาร์หรือคอลัมน์. นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.GapWidth อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | กำหนดว่ามีเส้นซีรีส์สำหรับซีรีส์นี้และซีรีส์ที่เกี่ยวข้องหรือไม่. นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.HasSeriesLines อ่าน/เขียน เพื่อเปลี่ยนค่า. ใช้คุณสมบัติ ParentSeriesGroup.SeriesLinesFormat เพื่อจัดรูปแบบเส้นซีรีส์. อ่านอย่างเดียว Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่. นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars.HasUpDownBars อ่าน/เขียน เพื่อเปลี่ยนค่า. ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars เพื่อจัดรูปแบบแถบขึ้น/ลง. อ่านอย่างเดียว Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | ระบุสีทึบกลับของซีรีส์. เพื่อใช้การตั้งค่าสีให้ตั้งค่า FillType ของรูปแบบซีรีส์เป็น FillType.Solid. อ่าน/เขียน [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | ระบุว่าบาร์, คอลัมน์หรือซีรีส์บับเบิลจะกลับสีของมันหากค่าติดลบ. อ่าน/เขียน Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีต่างกัน. นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.IsColorVaried อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | ส่งคืน Labels ของซีรีส์. อ่านอย่างเดียว [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | ส่งคืนมาร์คเกอร์ของซีรีส์. อ่านอย่างเดียว [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | ส่งคืนชื่อซีรีส์. อ่านอย่างเดียว [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับขนาดบับเบิลของซีรีส์. อ่าน/เขียน String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่าในซีรีส์. อ่าน/เขียน String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า x ของซีรีส์. อ่าน/เขียน String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | ส่งคืนหรือกำหนดรูปแบบตัวเลขสำหรับค่า y ของซีรีส์. อ่าน/เขียน String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | ส่งคืนลำดับของซีรีส์. อ่าน/เขียน Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | ระบุว่าบาร์และคอลัมน์ทับกันเท่าไหร่ในแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่. เป็นการฉายของคุณสมบัติเช่นกันในกลุ่มซีรีส์แม่, ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. เพื่อเปลี่ยนค่าให้ใช้คุณสมบัติ ParentSeriesGroup.Overlap อ่าน/เขียน. อ่านอย่างเดียว SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | แทนการจัดวางของป้ายชื่อหมวดหมู่แม่. ใช้ได้กับแผนภูมิ Treemap เท่านั้น. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | ส่งคืนกลุ่มซีรีส์แม่. อ่านอย่างเดียว [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.PieSplitBy อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | ข้อมูลการแยกที่กำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกกำหนดเอง. ประกอบด้วยจุดข้อมูลที่ควรวาดในพายหรือบาร์ที่สอง. นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. อ่านอย่างเดียว [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.PieSplitPosition อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | ระบุว่าซีรีส์นี้ถูกวาดบนแกนค่าที่สองหรือไม่. อ่าน/เขียน Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | แทนวิธี quartile. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | แทนรายการคำอธิบายที่เกี่ยวข้องกับซีรีส์นี้. อ่านอย่างเดียว [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). นี้เป็นคุณสมบัติเบื้องต้นของซีรีส์นี้และของซีรีส์ทั้งหมดในกลุ่มซีรีส์แม่ - เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์แม่. ใช้คุณสมบัติ ParentSeriesGroup.SecondPieSize อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | แทนเส้นเชื่อมต่อ. ใช้ได้เฉพาะแผนภูมิ Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | แทนจุดภายใน. จริงหากจุดภายในแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | แทนมาร์คเกอร์ค่าเฉลี่ย. จริงหากเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | แทนมาร์คเกอร์ค่าเฉลี่ย. จริงหากมาร์คเกอร์ค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | แทนจุดเบี่ยงเบน. จริงหากจุดเบี่ยงเบนแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. อ่าน/เขียน Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | แทนการทำให้เส้นโค้งเรียบ. จริงหากเปิดการทำให้เส้นโค้งเรียบสำหรับแผนภูมิ line หรือ scatter. ใช้ได้เฉพาะแผนภูมิ line และ scatter ที่เชื่อมต่อด้วยเส้น. อ่าน/เขียน Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | คอลเลกชันของเส้นแนวโน้มของซีรีส์. อ่านอย่างเดียว [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | ส่งคืนประเภทของซีรีส์นี้. อ่าน/เขียน [`ChartType`](../charttype). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | ส่งคืนสีอัตโนมัติของซีรีส์ที่อิงจากดัชนีซีรีส์และสไตล์ของแผนภูมิ. สีนี้จะถูกใช้โดยค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartComponent](../ichartcomponent)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->