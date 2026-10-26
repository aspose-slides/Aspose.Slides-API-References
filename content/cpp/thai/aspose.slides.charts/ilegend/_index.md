---
title: ILegend
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของคุณสมบัติ legend ของแผนภูมิ.
type: docs
weight: 1080
url: /th/aspose.slides.charts/ilegend/
---
## ILegend คลาส

เป็นตัวแทนของคุณสมบัติ legend ของแผนภูมิ.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าหนึ่งค่าใด รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าหนึ่งค่าใด รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | กำหนดความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | กำหนดความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | กำหนดตำแหน่ง x จริง (ทางซ้าย) ขององค์ประกอบแผนภูมิเพื่อเทียบกับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | กำหนดตำแหน่งด้านบนจริงขององค์ประกอบแผนภูมิเพื่อเทียบกับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | รับตำแหน่งด้านบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. อ่านอย่างเดียว **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | คืนค่าแผนภูมิ. อ่านอย่างเดียว [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | รับรายการ legend. อ่านอย่างเดียว [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | รับคุณสมบัติของรายการ legend ที่สอดคล้องกับจุดข้อมูลในแผนภูมิที่ตำแหน่งดัชนีระบุ. ในกรณีของประเภทแผนภูมิ: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, จุดข้อมูลจะถูกนำมาจากซีรีส์แรก. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | คืนค่ารูปแบบของ legend. อ่านอย่างเดียว [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | กำหนดความสูงขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. อ่าน **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | กำหนดว่าควรอนุญาตให้ส่วนประกอบแผนภูมิอื่นทับ legend หรือไม่. อ่าน **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | กำหนดตำแหน่งของ legend บนแผนภูมิ. ค่าที่ไม่ใช่ NaN ของคุณสมบัติ X, Y, Width, Height จะทับผลของคุณสมบัตินี้. อ่าน [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนค่าส่วนเสนอ. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | รับตำแหน่งขวาขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. อ่านอย่างเดียว **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | คืนค่าสไลด์ฐาน. อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | คืนรูปแบบข้อความของแผนภูมิ. อ่านอย่างเดียว [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | กำหนดความกว้างขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. อ่าน **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | กำหนดตำแหน่ง x (ทางซ้าย) ขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. อ่าน **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | กำหนดตำแหน่งด้านบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. อ่าน **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกอนของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกอนของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอเนกอนของตัวดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกอนของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. ไม่ทำการคัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ทำการคัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นรูปแบบพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นรูปแบบพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | กำหนดความสูงขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. เขียน **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | กำหนดว่าควรอนุญาตให้ส่วนประกอบแผนภูมิอื่นทับ legend หรือไม่. เขียน **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | กำหนดตำแหน่งของ legend บนแผนภูมิ. ค่าที่ไม่ใช่ NaN ของคุณสมบัติ X, Y, Width, Height จะทับผลของคุณสมบัตินี้. เขียน [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | กำหนดความกว้างขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. เขียน **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | กำหนดตำแหน่ง x (ทางซ้าย) ขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. เขียน **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | กำหนดตำแหน่งด้านบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกอนของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ILayoutable](../ilayoutable/)
* คลาส [IFormattedTextContainer](../iformattedtextcontainer/)
* คลาส [IActualLayout](../iactuallayout/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)