---
title: ErrorBarsFormat
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แสดงแท่งความผิดพลาดของชุดข้อมูลแผนภูมิ ค่าที่กำหนดเองของ ErrorBars อยู่ใน IChartDataPointCollection (ในคุณสมบัติ IChartDataPoint::get_ErrorBarsCustomValues())"
type: docs
weight: 482
url: /th/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat คลาส


แสดงแท่งความผิดพลาดของชุดข้อมูลแผนภูมิ. ค่าที่กำหนดเองของ ErrorBars อยู่ใน [IChartDataPointCollection](../ichartdatapointcollection/) (ในคุณสมบัติ [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/)).

```cpp
class ErrorBarsFormat : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::ChartSeries>>,
                        public Aspose::Slides::Charts::IErrorBarsFormat
```


## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนแบบจุดลอยตามสไตล์ C# ที่ถือว่า NaN สองค่าเท่ากันแม้ตามมาตรา IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนแบบจุดลอยตามสไตล์ C# ที่ถือว่า NaN สองค่าเท่ากันแม้ตามมาตรา IEC 60559:1989 NaN จะไม่เท่ากับค่าใด  ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | คืนค่าแผนภูมิต้นแบบ. อ่านอย่างเดียว [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | แสดงรูปแบบของแท่งความผิดพลาด. อ่าน [IFormat](../iformat/). |
| **bool** [get_HasEndCap](./get_hasendcap/)() override | ระบุว่าหัวปลายไม่ถูกวาดบนแท่งความผิดพลาด. อ่าน **bool**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | รับค่าการมองเห็นของ Error Bars. อ่าน **bool**. |
| [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() override | รับประเภทของแท่งความผิดพลาด. อ่าน [ErrorBarType](../errorbartype/). |
| **float** [get_Value](./get_value/)() override | รับค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแท่งความผิดพลาด. ในกรณีอื่นจะคืนค่า NaN. อ่าน **float**. |
| [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() override | แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของแท่งความผิดพลาด. ในกรณีของประเภทค่าที่กำหนดเองเพื่อระบุค่าให้ใช้คุณสมบัติ [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) ของจุดข้อมูลเฉพาะในคอลเลกชัน DataPoints ของชุดข้อมูล. ในกรณีของประเภทค่า Fixed, Percentage หรือ StandardDeviation ให้ใช้คุณสมบัติ Value เพื่อระบุค่า. 

 อ่าน [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ตามแบบของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถทำแฮชของอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. ตามแบบการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. ตามหลักการของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ตามแบบของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถทำสำเนาประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาในคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาในคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | แสดงรูปแบบของแท่งความผิดพลาด. เขียน [IFormat](../iformat/). |
| void [set_HasEndCap](./set_hasendcap/)(**bool**) override | ระบุว่าหัวปลายไม่ถูกวาดบนแท่งความผิดพลาด. เขียน **bool**. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | ตั้งค่าการมองเห็นของ Error Bars. เขียน **bool**. |
| void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) override | ตั้งค่าประเภทของแท่งความผิดพลาด. เขียน [ErrorBarType](../errorbartype/). |
| void [set_Value](./set_value/)(**float**) override | ตั้งค่าค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแท่งความผิดพลาด. ในกรณีอื่นจะคืนค่า NaN. เขียน **float**. |
| void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) override | แสดงวิธีที่เป็นไปได้ในการกำหนดความยาวของแท่งความผิดพลาด. ในกรณีของประเภทค่าที่กำหนดเองเพื่อระบุค่าให้ใช้คุณสมบัติ [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) ของจุดข้อมูลเฉพาะในคอลเลกชัน DataPoints ของชุดข้อมูล. ในกรณีของประเภทค่า Fixed, Percentage หรือ StandardDeviation ให้ใช้คุณสมบัติ Value เพื่อระบุค่า. 

 เขียน [ErrorBarValueType](../errorbarvaluetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ตั้งค่า argument template ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ตามแบบของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [DomObject](../../aspose.slides/domobject/)
* คลาส [IErrorBarsFormat](../ierrorbarsformat/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)