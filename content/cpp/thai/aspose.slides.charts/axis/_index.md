---
title: Axis
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ห่อหุ้มอ็อบเจ็กต์ที่เป็นตัวแทนแกนของแผนภูมิ
type: docs
weight: 14
url: /th/aspose.slides.charts/axis/
---
## คลาส Axis

Encapsulates the object that represents a chart's axis.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ C# [Object.Equals](../../system/object/equals/) ความหมาย. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการใช้งานภายในเท่านั้น. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | ระบุหน่วยหลักจริงของแกน. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้าเพื่อรับค่าจริง. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | ระบุสเกลหน่วยหลักจริงของแกน. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้าเพื่อรับค่าจริง. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | ระบุค่าสูงสุดจริงบนแกน. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้าเพื่อรับค่าจริง. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | ระบุหน่วยย่อยจริงของแกน. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้าเพื่อรับค่าจริง. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | ระบุสเกลหน่วยย่อยจริงของแกน. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้าเพื่อรับค่าจริง. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | ระบุค่าต่ำสุดจริงบนแกน. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนหน้าเพื่อรับค่าจริง. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | แสดงประเภทการรวบรวมของแกนประเภท (การจัดกลุ่ม). ใช้กับประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | แสดงว่าหากแกนค่าเดินข้ามแกนประเภทระหว่างประเภท. คุณสมบัตินี้ใช้กับแกนประเภทเท่านั้น และไม่ใช้กับแผนภูมิ 3 มิติ. อ่าน **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. อ่าน [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | ระบุความกว้างของไบน์เมื่อค่า AggregationType ตั้งเป็น [AxisAggregationType::ByBinWidth](../axisaggregationtype/). ใช้กับแกนประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | ระบุประเภทของแกนประเภท. อ่าน [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | ส่งคืนแผนภูมิโบ๊ท. อ่านอย่างเดียว [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | แสดงจุดบนแกนที่แกนตั้งฉากตัดผ่าน. อ่าน **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | แสดง CrossType บนแกนที่ระบุที่แกนอื่นตัดผ่าน. อ่าน [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | ระบุค่าการปรับขนาดของหน่วยแสดงผลสำหรับแกนค่า. อ่าน [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | แสดงรูปแบบของแกน. อ่านอย่างเดียว [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | กำหนดว่าแกนมีชื่อเรื่องที่มองเห็นได้หรือไม่. อ่าน **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดอัตโนมัติหรือไม่. อ่าน **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | บ่งชี้ว่าค่าสูงสุดถูกกำหนดอัตโนมัติหรือไม่. อ่าน **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | บ่งชี้ว่าหน่วยย่อยของแกนถูกกำหนดอัตโนมัติหรือไม่. อ่าน **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | บ่งชี้ว่าค่าต่ำสุดถูกกำหนดอัตโนมัติหรือไม่. อ่าน **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | ระบุค่าบินโอเวอร์โฟลว์อัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | ระบุค่าระยะห่างป้ายขีดอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ TickLabelSpacing. อ่าน **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | ระบุค่าระยะห่างเครื่องหมายติกอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ TickMarksSpacing. อ่าน **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | ระบุค่าบินอันเดอร์โฟลวอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | แสดงว่าประเภทสเกลของแกนค่าคือโลการิทึมหรือไม่. อ่าน **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่. อ่าน **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | ระบุว่ามีการใช้ไบน์โอเวอร์โฟลว์หรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบินโอเวอร์โฟลว์. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | แสดงว่า MS PowerPoint วางจุดข้อมูลจากสุดท้ายไปแรกหรือไม่. อ่าน **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | ระบุว่ามีการใช้ไบน์อันเดอร์โฟลว์หรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบินอันเดอร์โฟลว์. |
| **bool** [get_IsVisible](./get_isvisible/)() override | แสดงว่าแกนมองเห็นได้หรือไม่. อ่าน **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | ระบุระยะห่างของป้ายจากแกน. ใช้กับแกนประเภทหรือวันที่. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%. อ่าน **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | แสดงฐานของลอการิทึม. ค่าเริ่มต้นคือ 10. อ่าน **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | แสดงรูปแบบของเส้นกริดหลักบนแกนแผนภูมิ. อ่านอย่างเดียว [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | แสดงประเภทของเครื่องหมายติกหลักสำหรับแกนที่ระบุ. อ่าน [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า. อ่าน **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | แสดงสเกลหน่วยหลักสำหรับแกนวันที่. อ่าน [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | แสดงค่าสูงสุดบนแกนค่า. อ่าน **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | แสดงรูปแบบของเส้นกริดย่อยบนแกนแผนภูมิ. อ่านอย่างเดียว [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | แสดงประเภทของเครื่องหมายติกย่อยสำหรับแกนที่ระบุ. อ่าน [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | แสดงหน่วยย่อยสำหรับแกนวันที่หรือค่า. อ่าน **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | แสดงสเกลหน่วยหลักสำหรับแกนวันที่. อ่าน [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | แสดงค่าต่างสุดบนแกนค่า. อ่าน **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | แสดงสตริงรูปแบบสำหรับป้าย [Axis](./). อ่าน [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | ระบุจำนวนไบน์เมื่อค่า AggregationType ตั้งเป็น [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). ใช้กับแกนประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | ระบุค่าตรงของไบน์โอเวอร์โฟลว์. ใช้เมื่อคุณสมบัติ IsAutomaticOverflowBin ตั้งเป็น false และ IsOverflowBin เป็น true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | แสดงตำแหน่งของแกน. อ่าน [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | เพื่อซ่อนกริดหลักตั้งค่า [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() เป็น [FillType::NoFill](../../aspose.slides/filltype/). อ่านอย่างเดียว **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | เพื่อซ่อนกริดย่อยตั้งค่า [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() เป็น [FillType::NoFill](../../aspose.slides/filltype/). อ่านอย่างเดียว **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | แสดงรูปแบบของข้อความ. อ่านอย่างเดียว [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | แสดงตำแหน่งของป้ายเครื่องหมายติกบนแกนที่ระบุ. อ่าน [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | แสดงมุมการหมุนของป้ายติก. อ่าน **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | ระบุจำนวนป้ายติกที่จะข้ามระหว่างป้ายที่วาด. ใช้กับแกนประเภทหรือซีรีส์. อ่าน **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | ระบุจำนวนเครื่องหมายติกที่ต้องข้ามก่อนวาดเครื่องหมายต่อไป. ใช้กับแกนประเภทหรือซีรีส์. อ่าน **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | รับชื่อหัวข้อของแกน. อ่านอย่างเดียว [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | ระบุค่าตรงของไบน์อันเดอร์โฟลว์. ใช้เมื่อคุณสมบัติ IsAutomaticUnderflowBin ตั้งเป็น false และ IsUnderflowBin เป็น true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). รองรับการสร้างแฮชของวัตถุที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เทียบเคียงกับออปเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). รองรับการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ ไม่ได้คัดลอกอะไร, เพียงเริ่มต้นวัตถุใหม่และเปิดใช้การคัดลอกสร้างคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไร, เพียงเริ่มต้นวัตถุใหม่และเปิดใช้การคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมตามค่าที่ระบุ. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | แสดงประเภทการรวบรวมของแกนประเภท (การจัดกลุ่ม). ใช้กับประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | แสดงว่าหากแกนค่าตัดกับแกนประเภทระหว่างประเภท. คุณสมบัตินี้ใช้กับแกนประเภทเท่านั้นและไม่ใช้กับแผนภูมิ 3 มิติ. เขียน **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. เขียน [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | ระบุความกว้างของไบน์เมื่อค่า AggregationType ตั้งเป็น [AxisAggregationType::ByBinWidth](../axisaggregationtype/). ใช้กับแกนประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | ระบุประเภทของแกนประเภท. เขียน [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | แสดงจุดบนแกนที่แกนตั้งฉากตัดผ่าน. เขียน **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | แสดง CrossType บนแกนที่ระบุที่แกนอื่นตัดผ่าน. เขียน [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | ระบุค่าการปรับขนาดของหน่วยแสดงผลสำหรับแกนค่า. เขียน [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | กำหนดว่าตำแหน่งของแกนมีชื่อเรื่องที่มองเห็นได้หรือไม่. เขียน **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดอัตโนมัติหรือไม่. เขียน **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | บ่งชี้ว่าค่าสูงสุดถูกกำหนดอัตโนมัติหรือไม่. เขียน **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | บ่งชี้ว่าหน่วยย่อยของแกนถูกกำหนดอัตโนมัติหรือไม่. เขียน **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | บ่งชี้ว่าค่าต่ำสุดถูกกำหนดอัตโนมัติหรือไม่. เขียน **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | ระบุค่าบินโอเวอร์โฟลว์อัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | ระบุค่าระยะห่างป้ายขีดอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ TickLabelSpacing. เขียน **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | ระบุค่าระยะห่างเครื่องหมายติกอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ TickMarksSpacing. เขียน **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | ระบุค่าบินอันเดอร์โฟลวอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | แสดงว่าประเภทสเกลของแกนค่าคือโลการิทึมหรือไม่. เขียน **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่. เขียน **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | ระบุว่ามีการใช้ไบน์โอเวอร์โฟลว์หรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบินโอเวอร์โฟลว์. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | แสดงว่า MS PowerPoint วางจุดข้อมูลจากสุดท้ายไปแรกหรือไม่. เขียน **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | ระบุว่ามีการใช้ไบน์อันเดอร์โฟลว์หรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบินอันเดอร์โฟลว์. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | แสดงว่าแกนมองเห็นได้หรือไม่. เขียน **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | ระบุระยะห่างของป้ายจากแกน. ใช้กับแกนประเภทหรือวันที่. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%. เขียน **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | แสดงฐานของลอการิทึม. ค่าเริ่มต้นคือ 10. เขียน **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | แสดงประเภทของเครื่องหมายติกหลักสำหรับแกนที่ระบุ. เขียน [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า. เขียน **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | แสดงสเกลหน่วยหลักสำหรับแกนวันที่. เขียน [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | แสดงค่าสูงสุดบนแกนค่า. เขียน **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | แสดงประเภทของเครื่องหมายติกย่อยสำหรับแกนที่ระบุ. เขียน [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | แสดงหน่วยย่อยสำหรับแกนวันที่หรือค่า. เขียน **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | แสดงสเกลหน่วยหลักสำหรับแกนวันที่. เขียน [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | แสดงค่าต่ำสุดบนแกนค่า. เขียน **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | แสดงสตริงรูปแบบสำหรับป้าย [Axis](./). เขียน [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | ระบุจำนวนไบน์เมื่อค่า AggregationType ตั้งเป็น [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). ใช้กับแกนประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | ระบุค่าตรงของไบน์โอเวอร์โฟลว์. ใช้เมื่อ IsAutomaticOverflowBin ตั้งเป็น false และ IsOverflowBin เป็น true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | แสดงตำแหน่งของแกน. เขียน [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | แสดงตำแหน่งของป้ายเครื่องหมายติกบนแกนที่ระบุ. เขียน [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | แสดงมุมการหมุนของป้ายติก. เขียน **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | ระบุจำนวนป้ายติกที่จะข้ามระหว่างป้ายที่วาด. ใช้กับแกนประเภทหรือซีรีส์. เขียน **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | ระบุจำนวนเครื่องหมายติกที่ต้องข้ามก่อนวาดเครื่องหมายต่อไป. ใช้กับแกนประเภทหรือซีรีส์. เขียน **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | ระบุค่าตรงของไบน์อันเดอร์โฟลว์. ใช้เมื่อ IsAutomaticUnderflowBin ตั้งเป็น false และ IsUnderflowBin เป็น true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | ตั้งค่าคุณสมบัติ IAxis::get(set)_CategoryAxisType ด้วยค่าที่กำหนดโดยอัตโนมัติตามข้อมูลแกน. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นสถานะ weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). รองรับการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [DomObject](../../aspose.slides/domobject/)
* คลาส [IAxis](../iaxis/)
* เนมสเปส [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)