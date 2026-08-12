---
title: SmartArtNode
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทนโหนดของอ็อบเจกต์ SmartArt
type: docs
weight: 79
url: /th/aspose.slides.smartart/smartartnode/
---
## SmartArtNode คลาส


แทนโหนดของอ็อบเจกต์ [SmartArt](../smartart/)

```cpp
class SmartArtNode : public Aspose::Slides::SmartArt::ISmartArtNode
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_BulletFillFormat](./get_bulletfillformat/)() override | คืนค่าอ็อบเจกต์ [FillFormat](../../aspose.slides/fillformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบการเติมสีสำหรับจุดหัวข้อของโหนด หมายเหตุ: สามารถคืนค่า null สำหรับบางประเภทของการจัดรูปแบบ [SmartArt](../smartart/) ที่ไม่ได้ให้จุดหัวข้อสำหรับโหนด อ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_ChildNode](./get_childnode/)(**int32_t**) override | คืนค่าโหนดลูกของโหนดนี้ที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_ChildNodes](./get_childnodes/)() override | คืนค่าชุดของโหนดลูกทั้งหมดของโหนดปัจจุบัน อ่านอย่างเดียว [ISmartArtNodeCollection](../ismartartnodecollection/). |
| **bool** [get_IsAssistant](./get_isassistant/)() override | คืนค่าโหนดเป็นผู้ช่วย อ่าน **bool**. |
| **bool** [get_IsHidden](./get_ishidden/)() override | คืนค่า true หากโหนดนี้เป็นโหนดที่ซ่อนอยู่ในโมเดลข้อมูล อ่านอย่างเดียว **bool**. |
| **int32_t** [get_Level](./get_level/)() override | คืนค่าระดับการซ้อนของโหนด อ่านอย่างเดียว **int32_t**. |
| [OrganizationChartLayoutType](../organizationchartlayouttype/) [get_OrganizationChartLayout](./get_organizationchartlayout/)() override | คืนค่าชนิดการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน อ่าน [OrganizationChartLayoutType](../organizationchartlayouttype/). |
| **int32_t** [get_Position](./get_position/)() override | คืนค่าตำแหน่งโดยเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง อ่าน **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtShape](../ismartartshape/)\> [get_Shape](./get_shape/)(**int32_t**) override | คืนค่า shape ที่เชื่อมโยงกับโหนดนี้ที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Aspose::Slides::SmartArt::ISmartArtShape](../ismartartshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtShapeCollection](../ismartartshapecollection/)\> [get_Shapes](./get_shapes/)() override | คืนค่าชุดของ shape ทั้งหมดที่เชื่อมโยงกับโหนดนี้ อ่านอย่างเดียว [ISmartArtShapeCollection](../ismartartshapecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | คืนค่า text frame ของโหนด อ่านอย่างเดียว [ITextFrame](../../aspose.slides/itextframe/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานแบบคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์ เป็นการทำงานแบบคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นการทำงานแบบคล้ายกับโอเปอร์เรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการทำงานแบบคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้ทำการคัดลอกอะไรจริง ๆ เพียงแต่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้ทำการคัดลอกอะไรจริง ๆ เพียงแต่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงประเภทค่าเทียบกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| **bool** [Remove](./remove/)() override | ลบโหนดปัจจุบัน. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_IsAssistant](./set_isassistant/)(**bool**) override | ตั้งค่าโหนดเป็นผู้ช่วย เขียน **bool**. |
| void [set_OrganizationChartLayout](./set_organizationchartlayout/)([OrganizationChartLayoutType](../organizationchartlayouttype/)) override | ตั้งค่าชนิดการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน เขียน [OrganizationChartLayoutType](../organizationchartlayouttype/). |
| void [set_Position](./set_position/)(**int32_t**) override | ตั้งค่าตำแหน่งโดยเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง เขียน **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) ให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการทำงานแบบคล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการแบบ C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [ISmartArtNode](../ismartartnode/)
* เนมสเปซ [Aspose::Slides::SmartArt](../)
* ไลบรารี [Aspose.Slides](../../)