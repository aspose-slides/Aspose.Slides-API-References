---
title: IAxis
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ห่อหุ้มวัตถุที่เป็นตัวแทนแกนของแผนภูมิ.
type: docs
weight: 534
url: /th/aspose.slides.charts/iaxis/
---
## IAxis คลาส

Encapsulates the object that represents a chart's axis. → บรรจุวัตถุที่เป็นตัวแทนของแกนของแผนภูมิ.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | ระบุหน่วยหลักจริงของแกน เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้านี้เพื่อรับค่าจริง. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | ระบุสเกลหน่วยหลักจริงของแกน เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้านี้เพื่อรับค่าจริง. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | ระบุค่าสูงสุดจริงบนแกน เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้านี้เพื่อรับค่าจริง. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | ระบุหน่วยรองจริงของแกน เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้านี้เพื่อรับค่าจริง. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | ระบุสเกลหน่วยรองจริงของแกน เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้านี้เพื่อรับค่าจริง. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | ระบุค่าต่ำสุดจริงบนแกน เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้านี้เพื่อรับค่าจริง. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | แสดงประเภทการรวมของแกนหมวดหมู่ (การจัดกลุ่ม) ใช้กับหมวดหมู่ ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | แสดงว่ากราฟแกนค่าข้ามแกนหมวดหมู่ระหว่างหมวดหมู่หรือไม่ คุณสมบัตินี้ใช้กับแกนหมวดหมู่เท่านั้นและไม่ใช้กับแผนภูมิ 3 มิติ อ่าน **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | ระบุหน่วยเวลาเล็กที่สุดที่แสดงบนแกนวันที่ อ่าน [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | ระบุความกว้างของบล็อกเมื่อค่า Property AggregationType ตั้งเป็น [AxisAggregationType::ByBinWidth](../axisaggregationtype/) ใช้กับแกนหมวดหมู่ ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | ระบุประเภทของแกนหมวดหมู่ อ่าน [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | คืนค่าแผนภูมิ อ่านอย่างเดียว [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน อ่าน **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้าม อ่าน [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | ระบุค่าการปรับขนาดของหน่วยแสดงผลสำหรับแกนค่า อ่าน [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | แสดงรูปแบบของแกน อ่านอย่างเดียว [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | กำหนดว่าแกนมีชื่อที่มองเห็นได้หรือไม่ อ่าน **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดอัตโนมัติหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | บ่งชี้ว่าค่าสูงสุดถูกกำหนดอัตโนมัติหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดอัตโนมัติหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | บ่งชี้ว่าค่าต่ำสุดถูกกำหนดอัตโนมัติหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | ระบุค่าบล็อก overflow เป็นอัตโนมัติ หากเป็น false: ใช้ Property OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | ระบุค่าระยะห่างป้ายแท็กอัตโนมัติ หากเป็น false: ใช้ Property TickLabelSpacing อ่าน **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | ระบุค่าระยะห่างเครื่องหมายติ๊กอัตโนมัติ หากเป็น false: ใช้ Property TickMarksSpacing อ่าน **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | ระบุค่าบล็อก underflow เป็นอัตโนมัติ หากเป็น false: ใช้ Property UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | แสดงว่าประเภทสเกลแกนค่าคือโลการิทึมหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | บ่งชี้ว่าการจัดรูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | ระบุว่าบล็อก overflow ถูกนำไปใช้หรือไม่ ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบล็อก overflow. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | แสดงว่า MS PowerPoint วาดจุดข้อมูลจากสุดท้ายไปแรกหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | ระบุว่าบล็อก underflow ถูกนำไปใช้หรือไม่ ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบล็อก underflow. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | แสดงว่าแกนมองเห็นได้หรือไม่ อ่าน **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | ระบุระยะห่างของป้ายจากแกน ใช้กับแกนหมวดหมู่หรือวันที่ ค่าต้องอยู่ระหว่าง 0% ถึง 1000% อ่าน **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | แสดงฐานลอการิทึม ค่าเริ่มต้นคือ 10 อ่าน **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | แสดงรูปแบบเส้นกริดหลักบนแกนแผนภูมิ อ่านอย่างเดียว [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | แสดงประเภทของเครื่องหมายติ๊กหลักสำหรับแกนที่ระบุ อ่าน [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า อ่าน **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | แสดงสเกลหน่วยหลักสำหรับแกนวันที่ อ่าน [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | แสดงค่าสูงสุดบนแกนค่า อ่าน **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | แสดงรูปแบบเส้นกริดรองบนแกนแผนภูมิ อ่านอย่างเดียว [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | แสดงประเภทของเครื่องหมายติ๊กรองสำหรับแกนที่ระบุ อ่าน [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | แสดงหน่วยรองสำหรับแกนวันที่หรือค่า อ่าน **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | แสดงสเกลหน่วยหลักสำหรับแกนวันที่ อ่าน [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | แสดงค่าต่ำสุดบนแกนค่า อ่าน **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | แสดงสตริงรูปแบบสำหรับป้าย [Axis](../axis/) อ่าน [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | ระบุจำนวนบล็อกเมื่อค่า Property AggregationType ตั้งเป็น [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) ใช้กับแกนหมวดหมู่ ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | ระบุค่าบล็อก overflow แบบกำหนดเอง ใช้เมื่อ Property IsAutomaticOverflowBin ตั้งเป็น false และ Property IsOverflowBin มีค่า true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | แสดงตำแหน่งของแกน อ่าน [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนสไลด์โชว์ อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | แสดงว่าเส้นกริดหลักถูกแสดงหรือไม่ อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | แสดงว่าเส้นกริดรองถูกแสดงหรือไม่ อ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | คืนสไลด์พื้นฐานอ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | คืนรูปแบบข้อความแผนภูมิอ่านอย่างเดียว [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | แสดงตำแหน่งของป้ายเครื่องหมายติ๊กบนแกนที่ระบุ อ่าน [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | แสดงมุมการหมุนของป้ายติ๊ก อ่าน **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | ระบุจำนวนป้ายติ๊กที่จะข้ามระหว่างป้ายที่วาดอ่าน **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | ระบุจำนวนเครื่องหมายติ๊กที่จะข้ามก่อนที่จะวาดเครื่องหมายต่อไป ใช้กับแกนหมวดหมู่หรือซีรีส์ อ่าน **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | รับชื่อของแกนอ่านอย่างเดียว [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | ระบุค่าบล็อก underflow แบบกำหนดเอง ใช้เมื่อ Property IsAutomaticUnderflowBin ตั้งเป็น false และ Property IsUnderflowBin มีค่า true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำแฮชวัตถุที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นอนาล็อกของตัวดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาของคลาสย่อยได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาของคลาสย่อยได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของวัตถุประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | แสดงประเภทการรวมของแกนหมวดหมู่ (การจัดกลุ่ม) ใช้กับหมวดหมู่ ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | แสดงว่ากราฟแกนค่าข้ามแกนหมวดหมู่ระหว่างหมวดหมู่หรือไม่ คุณสมบัตินี้ใช้กับแกนหมวดหมู่เท่านั้นและไม่ใช้กับแผนภูมิ 3 มิติ เขียน **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | ระบุหน่วยเวลาเล็กที่สุดที่แสดงบนแกนวันที่ เขียน [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | ระบุความกว้างของบล็อกเมื่อค่า Property AggregationType ตั้งเป็น [AxisAggregationType::ByBinWidth](../axisaggregationtype/) ใช้กับแกนหมวดหมู่ ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | ระบุประเภทของแกนหมวดหมู่ เขียน [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน เขียน **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้าม เขียน [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | ระบุค่าการปรับขนาดของหน่วยแสดงผลสำหรับแกนค่า เขียน [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | กำหนดว่าแกนมีชื่อที่มองเห็นได้หรือไม่ เขียน **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดอัตโนมัติหรือไม่ เขียน **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | บ่งชี้ว่าค่าสูงสุดถูกกำหนดอัตโนมัติหรือไม่ เขียน **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดอัตโนมัติหรือไม่ เขียน **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | บ่งชี้ว่าค่าต่ำสุดถูกกำหนดอัตโนมัติหรือไม่ เขียน **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | ระบุค่าบล็อก overflow เป็นอัตโนมัติ หากเป็น false: ใช้ Property OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | ระบุค่าระยะห่างป้ายแท็กอัตโนมัติ หากเป็น false: ใช้ Property TickLabelSpacing เขียน **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | ระบุค่าระยะห่างเครื่องหมายติ๊กอัตโนมัติ หากเป็น false: ใช้ Property TickMarksSpacing เขียน **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | ระบุค่าบล็อก underflow เป็นอัตโนมัติ หากเป็น false: ใช้ Property UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | แสดงว่าประเภทสเกลแกนค่าคือโลการิทึมหรือไม่ เขียน **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | บ่งชี้ว่าการจัดรูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ เขียน **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | ระบุว่าบล็อก overflow ถูกนำไปใช้หรือไม่ ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบล็อก overflow. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | แสดงว่า MS PowerPoint วาดจุดข้อมูลจากสุดท้ายไปแรกหรือไม่ เขียน **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | ระบุว่าบล็อก underflow ถูกนำไปใช้หรือไม่ ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบล็อก underflow. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | แสดงว่าแกนมองเห็นได้หรือไม่ เขียน **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | ระบุระยะห่างของป้ายจากแกน ใช้กับแกนหมวดหมู่หรือวันที่ ค่าต้องอยู่ระหว่าง 0% ถึง 1000% เขียน **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | แสดงฐานลอการิทึม ค่าเริ่มต้นคือ 10 เขียน **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | แสดงประเภทของเครื่องหมายติ๊กหลักสำหรับแกนที่ระบุ เขียน [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า เขียน **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | แสดงสเกลหน่วยหลักสำหรับแกนวันที่ เขียน [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | แสดงค่าสูงสุดบนแกนค่า เขียน **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | แสดงประเภทของเครื่องหมายติ๊กรองสำหรับแกนที่ระบุ เขียน [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | แสดงหน่วยรองสำหรับแกนวันที่หรือค่า เขียน **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | แสดงสเกลหน่วยหลักสำหรับแกนวันที่ เขียน [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | แสดงค่าต่ำสุดบนแกนค่า เขียน **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | แสดงสตริงรูปแบบสำหรับป้าย [Axis](../axis/) เขียน [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | ระบุจำนวนบล็อกเมื่อค่า Property AggregationType ตั้งเป็น [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) ใช้กับแกนหมวดหมู่ ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | ระบุค่าบล็อก overflow แบบกำหนดเอง ใช้เมื่อ Property IsAutomaticOverflowBin ตั้งเป็น false และ Property IsOverflowBin มีค่า true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | แสดงตำแหน่งของแกน เขียน [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | แสดงตำแหน่งของป้ายเครื่องหมายติ๊กบนแกนที่ระบุ เขียน [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | แสดงมุมการหมุนของป้ายติ๊ก เขียน **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | ระบุจำนวนป้ายติ๊กที่จะข้ามระหว่างป้ายที่วาด เขียน **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | ระบุจำนวนเครื่องหมายติ๊กที่จะข้ามก่อนที่จะวาดเครื่องหมายต่อไป ใช้กับแกนหมวดหมู่หรือซีรีส์ เขียน **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | ระบุค่าบล็อก underflow แบบกำหนดเอง ใช้เมื่อ Property IsAutomaticUnderflowBin ตั้งเป็น false และ Property IsUnderflowBin มีค่า true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | กำหนดค่า Property IAxis::get(set)_CategoryAxisType ด้วยค่าที่กำหนดอัตโนมัติตามข้อมูลของแกน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) ช่วยให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงวัตถุที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือน C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IFormattedTextContainer](../iformattedtextcontainer/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)