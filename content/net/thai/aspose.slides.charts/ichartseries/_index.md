---
title: IChartSeries
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: แสดง series ของแผนภูมิ.
type: docs
weight: 1930
url: /th/aspose.slides.charts/ichartseries/
---
## IChartSeries อินเทอร์เฟซ

แสดง series ของแผนภูมิ

```csharp
public interface IChartSeries : IChartComponent
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | อนุญาตให้ดึงอินเทอร์เฟซ IChartComponent พื้นฐาน. อ่านอย่างเดียว [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | ระบุรูปร่างของ series ของแผนภูมิแท่ง 3-D. การเปลี่ยนค่าอาจทำให้ประเภทของ series เปลี่ยนโดยอัตโนมัติ. อ่าน/เขียน [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | ระบุวิธีการที่ค่าขนาดฟองอากาศแสดงในแผนภูมิบับเบิล. นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeRepresentation อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | ระบุสเกลแฟกเตอร์สำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0-300 % ของขนาดเริ่มต้น). นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.BubbleSizeScale อ่าน/เขียน เพื่อเปลี่ยนค่า. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | คืนค่าคอลเลกชันของจุดข้อมูลของ series นี้. อ่านอย่างเดียว [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | ระบุขนาดของช่องในแผนภูมิดอนัท (สามารถอยู่ระหว่าง 10-90 % ของขนาดพื้นที่พล็อต). นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.DoughnutHoleSize อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | แสดง ErrorBars ของ series ที่มีทิศทาง X. ErrorBars ที่มีทิศทาง X มีให้สำหรับ series ประเภท area, bar, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีค่าที่กำหนดเองใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | แสดง ErrorBars ของ series ที่มีทิศทาง Y. ErrorBars ที่มีทิศทาง Y มีให้สำหรับ series ประเภท area, bar, line, scatter และ bubble. สำหรับประเภทแผนภูมิอื่น ๆ คุณสมบัตินี้จะคืนค่า null (รวมถึงแผนภูมิ 3D). ในกรณีค่าที่กำหนดเองใช้คอลเลกชัน DataPoints เพื่อระบุค่า (ด้วยคุณสมบัติ [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). อ่านอย่างเดียว [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | ระยะห่างของชิ้นพายเปิดจากศูนย์กลางของแผนภูมิปาย แสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. อ่าน/เขียน Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | ระบุมุมของชิ้นพายหรือชิ้นดอนัทแรก, หน่วยเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360). นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.FirstSliceAngle อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | คืนค่าฟอร์แมตของ series. อ่านอย่างเดียว [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | คืนค่าหรือกำหนดระยะห่าง (เป็นเปอร์เซ็นต์ของความกว้าง marker) ระหว่าง series ในแผนภูมิ 3D. นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.GapDepth อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | ระบุช่องว่างระหว่างกลุ่มแท่งหรือคอลัมน์, เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.GapWidth อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | กำหนดว่ามีเส้น series สำหรับ series นี้และ series ที่เกี่ยวข้องหรือไม่. นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.HasSeriesLines อ่าน/เขียน เพื่อเปลี่ยนค่า. ใช้คุณสมบัติ ParentSeriesGroup.SeriesLinesFormat สำหรับฟอร์แมตเส้น series. อ่านอย่างเดียว Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | กำหนดว่ากราฟเส้นหรือกราฟหุ้นมีแท่งขึ้น/ลงหรือไม่. นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars.HasUpDownBars อ่าน/เขียน เพื่อเปลี่ยนค่า. ใช้คุณสมบัติ ParentSeriesGroup.UpDownBars สำหรับฟอร์แมตแท่งขึ้น/ลง. อ่านอย่างเดียว Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | ระบุสีทึบกลับของ series. เพื่อใช้การตั้งค่าสีให้ตั้ง FillType ของฟอร์แมต series เป็น FillType.Solid. อ่าน/เขียน [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | ระบุว่าชุดแท่ง, คอลัมน์ หรือ bubble series จะสลับสีหากค่าเป็นลบ. อ่าน/เขียน Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | ระบุว่าตัวทำเครื่องหมายข้อมูลแต่ละรายการใน series มีสีแตกต่างกัน. นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.IsColorVaried อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | คืนค่า Labels ของ series. อ่านอย่างเดียว [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | คืนค่า marker ของ series. อ่านอย่างเดียว [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | คืนค่าชื่อของ series. อ่านอย่างเดียว [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | คืนค่าหรือกำหนดรูปแบบตัวเลขสำหรับขนาดฟองของ series. อ่าน/เขียน String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | คืนค่าหรือกำหนดรูปแบบตัวเลขสำหรับค่าของ series. อ่าน/เขียน String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | คืนค่า或กำหนดรูปแบบตัวเลขสำหรับค่า x ของ series. อ่าน/เขียน String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | คืนค่า或กำหนดรูปแบบตัวเลขสำหรับค่า y ของ series. อ่าน/เขียน String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | คืนค่าลำดับของ series. อ่าน/เขียน Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | ระบุระดับการทับของแท่งและคอลัมน์บนแผนภูมิ 2-D, เป็นเปอร์เซ็นต์ (จาก -100 % ถึง 100 %). นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. เพื่อเปลี่ยนค่าให้ใช้ ParentSeriesGroup.Overlap อ่าน/เขียน. อ่านอย่างเดียว SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | แทนเลย์เอาต์ของป้ายหมวดพาเรนต์. ใช้ได้เฉพาะแผนภูมิเคี้ยน. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | คืนค่ากลุ่ม series พาเรนต์. อ่านอย่างเดียว [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | ระบุวิธีการกำหนดว่าข้อมูลใดอยู่ในพายหรือแท่งที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.PieSplitBy อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. ประกอบด้วยจุดข้อมูลที่จะวาดในพายหรือแท่งที่สอง. นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. อ่านอย่างเดียว [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | ระบุค่าที่ใช้กำหนดว่าข้อมูลใดอยู่ในพายหรือแท่งที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.PieSplitPosition อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | ระบุว่ากราฟนี้วาดบนแกนค่าแบบที่สองหรือไม่. อ่าน/เขียน Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | แทนวิธีการคำนวณควอร์ไทล์. ใช้ได้เฉพาะแผนภูมิกล่องและคีบ. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | แทนรายการคำอธิบายของ legend ที่เกี่ยวข้องกับ series นี้. อ่านอย่างเดียว [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie, เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5-200 %). นี้เป็นคุณสมบัติของไม่เพียง series นี้แต่ของทุก series ในกลุ่ม series พาเรนต์ – เป็นการฉายของคุณสมบัติที่เหมาะสมในกลุ่ม. ดังนั้นคุณสมบัตินี้เป็นอ่านอย่างเดียว. ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่ม series พาเรนต์. ใช้คุณสมบัติ ParentSeriesGroup.SecondPieSize อ่าน/เขียน เพื่อเปลี่ยนค่า. อ่านอย่างเดียว UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | แทนเส้นเชื่อมต่อ. ใช้ได้เฉพาะแผนภูมิกระแสเงิน. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | แทนจุดภายใน. true ถ้าจะแสดงจุดภายในบนแผนภูมิกล่องและคีบ. ใช้ได้เฉพาะแผนภูมิกล่องและคีบ. อ่าน/เขียน Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | แทนเครื่องหมายค่ากลาง. true ถ้าแสดงเส้นค่ากลางบนแผนภูมิกล่องและคีบ. ใช้ได้เฉพาะแผนภูมิกล่องและคีบ. อ่าน/เขียน Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | แทนเครื่องหมายค่ากลาง. true ถ้าแสดงเครื่องหมายค่ากลางบนแผนภูมิกล่องและคีบ. ใช้ได้เฉพาะแผนภูมิกล่องและคีบ. อ่าน/เขียน Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | แทนจุดที่อยู่นอกค่าปกติ. true ถ้าแสดงจุดที่อยู่นอกค่าปกติบนแผนภูมิกล่องและคีบ. ใช้ได้เฉพาะแผนภูมิกล่องและคีบ. อ่าน/เขียน Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | แทนการทำให้เส้นโค้งเรียบ. true ถ้าการทำให้เส้นโค้งเรียบเปิดสำหรับแผนภูมิเส้นหรือกระจายที่เชื่อมต่อด้วยเส้น. ใช้ได้เฉพาะแผนภูมิเส้นและกระจายที่เชื่อมต่อด้วยเส้น. อ่าน/เขียน Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | คอลเลกชันของเส้นแนวโน้มของ series. อ่านอย่างเดียว [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | คืนค่าชนิดของ series นี้. อ่าน/เขียน [`ChartType`](../charttype). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | คืนค่าสีอัตโนมัติของ series ตามดัชนี series และสไตล์แผนภูมิ. สีนี้จะใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChartComponent](../ichartcomponent)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->