---
title: Legend
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงคุณสมบัติ legend ของแผนภูมิ
type: docs
weight: 1262
url: /th/aspose.slides.charts/legend/
---
## Legend คลาส

แสดงคุณสมบัติ legend ของแผนภูมิ.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้ภายในเท่านั้น |
| **float** [get_ActualHeight](./get_actualheight/)() override | ระบุความสูงจริงขององค์ประกอบแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float** |
| **float** [get_ActualWidth](./get_actualwidth/)() override | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float** |
| **float** [get_ActualX](./get_actualx/)() override | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float** |
| **float** [get_ActualY](./get_actualy/)() override | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float** |
| **float** [get_Bottom](./get_bottom/)() override | ด้านล่าง อ่านอย่างเดียว **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | ส่งคืนแผนภูมิ อ่านอย่างเดียว [IChart](../ichart/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | รับรายการ legend. อ่านอย่างเดียว [ILegendEntryCollection](../ilegendentrycollection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | รับคุณสมบัติของรายการ legend ที่สอดคล้องกับจุดข้อมูลในแผนภูมิที่ตำแหน่งกำหนด ในกรณีของประเภทแผนภูมิ: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie จะใช้จุดข้อมูลจากชุดแรก |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | ส่งคืนรูปแบบของ legend. อ่านอย่างเดียว [IFormat](../iformat/) |
| **float** [get_Height](./get_height/)() override | ส่งคืนความสูงของ legend เป็นสัดส่วนของความสูงของแผนภูมิ อ่าน **float** |
| **bool** [get_Overlay](./get_overlay/)() override | กำหนดว่ารายการแผนภูมิอื่น ๆ สามารถทับซ้อนกับ legend ได้หรือไม่ อ่าน **bool** |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | ระบุตำแหน่งของ legend บนแผนภูมิ ค่าที่ไม่ใช่ NaN ของคุณสมบัติ X, Y, Width, Heigt จะทับผลของคุณสมบัตินี้ อ่าน [LegendPositionType](../legendpositiontype/) |
| **float** [get_Right](./get_right/)() override | ด้านขวา อ่านอย่างเดียว **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | รูปแบบข้อความ อ่านอย่างเดียว [IChartTextFormat](../icharttextformat/) |
| **float** [get_Width](./get_width/)() override | ส่งคืนความกว้างของ legend เป็นสัดส่วนของความกว้างของแผนภูมิ อ่าน **float** |
| **float** [get_X](./get_x/)() override | ส่งคืนพิกัด x ของ legend เป็นสัดส่วนของความกว้างของแผนภูมิ อ่าน **float** |
| **float** [get_Y](./get_y/)() override | ส่งคืนพิกัด y ของ legend เป็นสัดส่วนของความสูงของแผนภูมิ อ่าน **float** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เทียบเคียงกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำ lock. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล cloning ประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. ไม่คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_Height](./set_height/)(**float**) override | กำหนดความสูงของ legend เป็นสัดส่วนของความสูงของแผนภูมิ เขียน **float** |
| void [set_Overlay](./set_overlay/)(**bool**) override | กำหนดว่ารายการอื่นของแผนภูมิจะสามารถทับซ้อนกับ legend ได้หรือไม่ เขียน **bool** |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | ระบุตำแหน่งของ legend บนแผนภูมิ ค่าที่ไม่ใช่ NaN ของคุณสมบัติ X, Y, Width, Heigt จะทับผลของคุณสมบัตินี้ เขียน [LegendPositionType](../legendpositiontype/) |
| void [set_Width](./set_width/)(**float**) override | กำหนดความกว้างของ legend เป็นสัดส่วนของความกว้างของแผนภูมิ เขียน **float** |
| void [set_X](./set_x/)(**float**) override | กำหนดพิกัด x ของ legend เป็นสัดส่วนของความกว้างของแผนภูมิ เขียน **float** |
| void [set_Y](./set_y/)(**float**) override | กำหนดพิกัด y ของ legend เป็นสัดส่วนของความสูงของแผนภูมิ เขียน **float** |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลด lock. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [DomObject](../../aspose.slides/domobject/)
* คลาส [ILegend](../ilegend/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)