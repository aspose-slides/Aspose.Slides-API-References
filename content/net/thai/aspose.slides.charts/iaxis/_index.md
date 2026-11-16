---
title: IAxis
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: บรรจุวัตถุที่เป็นตัวแทนแกนของแผนภูมิ
type: docs
weight: 1720
url: /th/aspose.slides.charts/iaxis/
---
## IAxis อินเทอร์เฟซ

บรรจุวัตถุที่เป็นตัวแทนแกนของแผนภูมิ

```csharp
public interface IAxis : IFormattedTextContainer
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | ระบุหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | ระบุมาตราส่วนหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | ระบุค่าสูงสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | ระบุหน่วยย่อยจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | ระบุมาตราส่วนหน่วยย่อยจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | ระบุค่าต่ำสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | แสดงประเภทการรวมของแกนประเภท (การจัดกลุ่ม). ใช้กับหมวด. ใช้เฉพาะกับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | อนุญาตให้รับอินเทอร์เฟซ IFormattedTextContainer พื้นฐาน. อ่านอย่างเดียว [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | แสดงว่าตรงแกนค่าที่ตัดแกนประเภทระหว่างหมวดหรือไม่. คุณสมบัตินี้ใช้ได้เฉพาะกับแกนประเภท และไม่ใช้กับแผนภูมิ 3 มิติ. อ่าน/เขียน Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | ระบุหน่วยเวลาเล็กที่สุดที่แสดงบนแกนวันที่. อ่าน/เขียน [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | ระบุความกว้างของถังเมื่อค่าคุณสมบัติ AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth. ใช้กับแกนประเภท. ใช้เฉพาะกับชุดข้อมูล Histogram หรือ HistogramParego เท่านั้น. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | ระบุประเภทของแกนประเภท. อ่าน/เขียน [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | แสดงจุดบนแกนที่แกนตั้งฉากตัดผ่าน. อ่าน/เขียน Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | แสดง CrossType บนแกนที่ระบุที่แกนอื่นตัด. อ่าน/เขียน [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | ระบุค่าการปรับสเกลของหน่วยแสดงผลสำหรับแกนค่า. อ่าน/เขียน [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | แสดงรูปแบบของแกน. อ่านอย่างเดียว [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | กำหนดว่าแกนมีหัวข้อที่มองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | ระบุว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | ระบุว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | ระบุว่าหน่วยย่อยของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | ระบุว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | ระบุค่าถัง overflow อัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | ระบุค่าการเว้นระยะป้ายกำกับติกอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ TickLabelSpacing. อ่าน/เขียน Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | ระบุค่าการเว้นระยะเครื่องหมายติกอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ TickMarksSpacing. อ่าน/เขียน Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | ระบุค่าถัง underflow อัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | แสดงว่าประเภทสเกลของแกนค่าคือโลกริทึมหรือไม่. อ่าน/เขียน Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | ระบุว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่. อ่าน/เขียน Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | ระบุว่าถัง overflow ถูกใช้หรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าถัง overflow. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | แสดงว่า MS PowerPoint วางจุดข้อมูลจากสุดท้ายไปแรกหรือไม่. อ่าน/เขียน Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | ระบุว่าถัง underflow ถูกใช้หรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าถัง underflow. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | แสดงว่าแกนมองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | ระยะห่างของป้ายจากแกน. ใช้กับแกนประเภทหรือวันที่. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%. อ่าน/เขียน UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | แสดงฐานของโลกริทึม. ค่าเริ่มต้นคือ 10. อ่าน/เขียน Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | แสดงรูปแบบเส้นกริดหลักบนแกนแผนภูมิ. อ่านอย่างเดียว [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | แสดงประเภทของเครื่องหมายติกหลักสำหรับแกนที่ระบุ. อ่าน/เขียน [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า. อ่าน/เขียน Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | แสดงมาตราส่วนหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | แสดงค่าสูงสุดบนแกนค่า. อ่าน/เขียน Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | แสดงรูปแบบเส้นกริดย่อยบนแกนแผนภูมิ. อ่านอย่างเดียว [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | แสดงประเภทของเครื่องหมายติกย่อยสำหรับแกนที่ระบุ. อ่าน/เขียน [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | แสดงหน่วยย่อยสำหรับแกนวันที่หรือค่า. อ่าน/เขียน Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | แสดงมาตราส่วนหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | แสดงค่าต่ำสุดบนแกนค่า. อ่าน/เขียน Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | แสดงสตริงรูปแบบสำหรับป้ายแกน. อ่าน/เขียน String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | ระบุจำนวนถังเมื่อค่าคุณสมบัติ AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins. ใช้กับแกนประเภท. ใช้เฉพาะกับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | ระบุค่าถัง overflow ที่กำหนดเอง. ใช้เมื่อคุณสมบัติ IsAutomaticOverflowBin ตั้งเป็น false และคุณสมบัติ IsOverflowBin มีค่าเป็น true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | แสดงตำแหน่งของแกน. อ่าน/เขียน [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | แสดงว่าตะแกรงหลักถูกแสดงหรือไม่. อ่านอย่างเดียว Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | แสดงว่าตะแกรงย่อยถูกแสดงหรือไม่. อ่านอย่างเดียว Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | แสดงตำแหน่งของป้ายกำกับเครื่องหมายติกบนแกนที่ระบุ. อ่าน/เขียน [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | แสดงมุมการหมุนของป้ายติก. อ่าน/เขียน Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | ระบุจำนวนป้ายติกที่ข้ามระหว่างป้ายที่วาด. อ่าน/เขียน UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | ระบุจำนวนเครื่องหมายติกที่ควรข้ามก่อนที่เครื่องหมายต่อไปจะถูกวาด. ใช้กับแกนประเภทหรือชุดข้อมูล. อ่าน/เขียน UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | รับหัวข้อของแกน. อ่านอย่างเดียว [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | ระบุค่าถัง underflow ที่กำหนดเอง. ใช้เมื่อคุณสมบัติ IsAutomaticUnderflowBin ตั้งเป็น false และคุณสมบัติ IsUnderflowBin มีค่าเป็น true. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่ถูกกำหนดโดยอัตโนมัติตามข้อมูลแกน. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IFormattedTextContainer](../iformattedtextcontainer)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->