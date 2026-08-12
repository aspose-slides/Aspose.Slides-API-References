---
title: ChartDataPoint
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงจุดข้อมูลของชุด.
type: docs
weight: 144
url: /th/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint คลาส


Represents series data point.

```cpp
class ChartDataPoint : public Aspose::Slides::Charts::IChartDataPoint,
                       public Aspose::Slides::IDOMObject
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้กฎการทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **float** [get_ActualHeight](./get_actualheight/)() override | ระบุความสูงจริงขององค์ประกอบแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float**. |
| **float** [get_ActualX](./get_actualx/)() override | ระบุตำแหน่ง x (ด้านซ้าย) จริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float**. |
| **float** [get_ActualY](./get_actualy/)() override | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() override | BubbleSize. อ่านอย่างเดียว [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() override | คืนค่าระดับสีของจุดข้อมูลแผนภูมิ ใช้กับแผนภูมิแบบแผนที่ อ่านอย่างเดียว [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) override | คืนค่าระดับจุดข้อมูลที่ตำแหน่งที่ระบุ ใช้สำหรับชุด Treeamp และ Sunburst การจัดลำดับระดับจุดข้อมูลเริ่มจากศูนย์. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() override | คืนค่ากล่องบรรจุระดับจุดข้อมูล ใช้สำหรับชุด Treeamp และ Sunburst การจัดลำดับระดับจุดข้อมูลเริ่มจากศูนย์. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() override | เป็นค่าบาร์ความผิดพลาดของชุดในกรณีประเภทค่า Custom อ่านอย่างเดียว [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| **int32_t** [get_Explosion](./get_explosion/)() override | ระบุปริมาณที่จุดข้อมูลควรย้ายออกจากศูนย์กลางของแผนภูมิแบบพาย อ่าน **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | เป็นคุณสมบัติการจัดรูปแบบ อ่าน [IFormat](../iformat/). |
| **uint32_t** [get_Index](./get_index/)() override | กำหนดว่าข้อมูลจุดนี้ใช้กับคอลเลกชันเด็กของพาเรนต์คอลเลกชันใด อ่าน **uint32_t**. |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | ระบุว่าจุดข้อมูลจะกลับสีหากค่าติดลบ อ่าน **bool**. |
| **bool** [get_IsBubble3D](./get_isbubble3d/)() override | ระบุว่าฟองน้ำจะมีเอฟเฟค 3-D ใส่ไว้ อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() override | ป้ายกำกับ. อ่านอย่างเดียว [IDataLabel](../idatalabel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | ระบุเครื่องหมายข้อมูล อ่านอย่างเดียว [IMarker](../imarker/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | คุณสมบัติของรายการคำอธิบายที่สอดคล้องกันในกรณีของประเภทแผนภูมิจากรายการนี้: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). อ่านอย่างเดียว [ILegendEntryProperties](../ilegendentryproperties/). |
| **bool** [get_SetAsTotal](./get_setastotal/)() override | ตั้งค่าจุดข้อมูลเป็นยอดรวม ใช้สำหรับชุดประเภท Waterfall เท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() override | คืนค่าขนาดของจุดข้อมูลแผนภูมิ ใช้กับแผนภูมิ Treemap และ Sunburst อ่านอย่างเดียว [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() override | ค่า. อ่านอย่างเดียว [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() override | XValue. อ่านอย่างเดียว [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() override | YValue. อ่านอย่างเดียว [IDoubleChartValue](../idoublechartvalue/). |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() override | คืนค่าสีอัตโนมัติของจุดข้อมูลโดยอิงจากดัชนีชุด, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์ของแผนภูมิ หาก FillType เท่ากับ NotDefined จะใช้สีนี้เป็นค่าเริ่มต้น. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้การแฮชของอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นอเนกประสงค์ของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้คอนสตรัคเตอร์คัดลอกซับคลาสทำงานได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้คอนสตรัคเตอร์คัดลอกซับคลาสทำงานได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| void [Remove](./remove/)() override | ลบ DataPoint จากชุดข้อมูลแผนภูมิ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | ระบุปริมาณที่จุดข้อมูลควรย้ายออกจากศูนย์กลางของแผนภูมิแบบพาย เขียน **int32_t**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | เป็นคุณสมบัติการจัดรูปแบบ เขียน [IFormat](../iformat/). |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | ระบุว่าจุดข้อมูลจะกลับสีหากค่าติดลบ เขียน **bool**. |
| void [set_IsBubble3D](./set_isbubble3d/)(**bool**) override | ระบุว่าฟองน้ำจะมีเอฟเฟค 3-D ใส่ไว้ เขียน **bool**. |
| void [set_SetAsTotal](./set_setastotal/)(**bool**) override | ตั้งค่าจุดข้อมูลเป็นยอดรวม ใช้สำหรับชุดประเภท Waterfall เท่านั้น. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า argument เทมเพลตที่ n เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมกันและคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IChartDataPoint](../ichartdatapoint/)
* คลาส [IDOMObject](../../aspose.slides/idomobject/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)