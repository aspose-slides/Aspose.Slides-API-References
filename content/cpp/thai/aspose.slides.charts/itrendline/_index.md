---
title: ITrendline
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คลาสแสดงเส้นแนวโน้มของชุดข้อมูลในแผนภูมิ
type: docs
weight: 1223
url: /th/aspose.slides.charts/itrendline/
---
## ITrendline คลาส

คลาสแทนเส้นแนวโน้มของชุดข้อมูลในแผนภูมิ

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## วิธีการ

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ \"text\" หาก TextFrameForOverriding ถูกเริ่มต้นแล้วจะทำการเปลี่ยนข้อความของมันเท่านั้น |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่งสองค่า NaN ถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่งสองค่า NaN ถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual **double** [get_Backward](./get_backward/)() | ระบุจำนวนประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปก่อนข้อมูลของชุดที่กำลังเทรนด์ ในแผนภูมิกระจายและแผนภูมิที่ไม่ใช่กระจาย ค่าใดก็ได้ที่ไม่เป็นลบ อ่าน **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | ส่งคืนแผนภูมิ อ่านอย่างเดียว [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | กำหนดให้สมการของเส้นแนวโน้มแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับค่า Rsquaredvalue) อ่าน **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | กำหนดให้ค่าระยะกำลังสอง (R-squared) ของเส้นแนวโน้มแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับสมการ) อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | แสดงรูปแบบของเส้นแนวโน้ม อ่าน [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | ระบุจำนวนประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปหลังข้อมูลของชุดที่กำลังเทรนด์ ในแผนภูมิกระจายและแผนภูมิที่ไม่ใช่กระจาย ค่าใดก็ได้ที่ไม่เป็นลบ อ่าน **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | ระบุค่าที่เส้นแนวโน้มจะตัดแกน y คุณสมบัตินี้สนับสนุนเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly อ่าน **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | ระบุลำดับของเส้นแนวโน้มพหุนาม จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น ๆ ค่าต้องอยู่ระหว่าง 2 ถึง 6 อ่าน **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | ระบุรอบของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่ ค่าจะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น ๆ ค่าต้องอยู่ระหว่าง 2 ถึง 255 อ่าน **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ส่งคืนการนำเสนอ อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | แสดงรายการคำอธิบายที่เกี่ยวข้องกับเส้นแนวโน้มนี้ อ่านอย่างเดียว [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ส่งคืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | ส่งคืนรูปแบบข้อความของแผนภูมิ อ่านอย่างเดียว [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | สามารถบรรจุข้อความที่จัดรูปแบบอย่างละเอียดได้ หากคุณสมบัตินี้ไม่เป็นค่า null ค่าข้อความที่จัดรูปแบบนี้จะทับข้อความที่สร้างอัตโนมัติ ข้อความที่สร้างอัตโนมัติเป็นคุณสมบัติแฝงของป้ายกำกับข้อมูล, ป้ายกำกับหน่วยแสดงของแกนค่า, ชื่อแกน, ชื่อแผนภูมิ, ป้ายกำกับของเส้นแนวโน้ม ข้อความที่สร้างอัตโนมัติมีรูปแบบตามคุณสมบัติ [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) อ่านอย่างเดียว [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | รับชื่อของเส้นแนวโน้ม อ่าน [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | รับประเภทของเส้นแนวโน้ม อ่าน [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเคียงของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชวัตถุที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ เป็นเทียบเคียงของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นเทียบเคียงของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเทียบเคียงของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรั๊กเตอร์คัดลอก ไม่ทำการคัดลอกสิ่งใดจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ทำการคัดลอกสิ่งใดจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_Backward](./set_backward/)(**double**) | ระบุจำนวนประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปก่อนข้อมูลของชุดที่กำลังเทรนด์ ในแผนภูมิกระจายและแผนภูมิที่ไม่ใช่กระจาย ค่าใดก็ได้ที่ไม่เป็นลบ เขียน **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | กำหนดให้สมการของเส้นแนวโน้มแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับค่า Rsquaredvalue) เขียน **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | กำหนดให้ค่าระยะกำลังสอง (R-squared) ของเส้นแนวโน้มแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับสมการ) เขียน **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | แสดงรูปแบบของเส้นแนวโน้ม เขียน [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | ระบุจำนวนประเภท (หรือหน่วยในแผนภูมิกระจาย) ที่เส้นแนวโน้มขยายออกไปหลังข้อมูลของชุดที่กำลังเทรนด์ ในแผนภูมิกระจายและแผนภูมิที่ไม่ใช่กระจาย ค่าใดก็ได้ที่ไม่เป็นลบ เขียน **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | ระบุค่าที่เส้นแนวโน้มจะตัดแกน y คุณสมบัตินี้สนับสนุนเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly เขียน **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | ระบุลำดับของเส้นแนวโน้มพหุนาม จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น ๆ ค่าต้องอยู่ระหว่าง 2 ถึง 6 เขียน **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | ระบุรอบของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่ ค่าจะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น ๆ ค่าต้องอยู่ระหว่าง 2 ถึง 255 เขียน **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | ตั้งชื่อของเส้นแนวโน้ม เขียน [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | ตั้งประเภทของเส้นแนวโน้ม เขียน [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตลำดับที่ n ให้เป็น weak pointer (แทนที่จะแบ่งปัน) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเทียบเคียงของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงวัตถุที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [IOverridableText](../ioverridabletext/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)