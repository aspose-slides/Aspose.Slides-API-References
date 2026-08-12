---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตัวเลือกสำหรับการสกัด HTML จากข้อความ Pptx.
type: docs
weight: 755
url: /th/aspose.slides.export/texttohtmlconversionoptions/
---
## TextToHtmlConversionOptions คลาส

ตัวเลือกสำหรับการสกัด HTML จากข้อความ Pptx.

```cpp
class TextToHtmlConversionOptions : public Aspose::Slides::Export::ITextToHtmlConversionOptions
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C#-style ที่ NaN สองค่า ถูกพิจารณาเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C#-style ที่ NaN สองค่า ถูกพิจารณาเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| **bool** [get_AddClipboardFragmentHeader](./get_addclipboardfragmentheader/)() override | คืนค่า ระบุว่าควรเพิ่มส่วนหัว Clipboard หรือไม่ อ่าน **bool**. |
| [System::String](../../system/string/) [get_EncodingName](./get_encodingname/)() override | คืนชื่อการเข้ารหัส HTML ค่าตัวนี้จะถูกบันทึกลงไฟล์ HTML ที่สร้างขึ้น แต่ขึ้นอยู่กับผู้เรียกเพื่อให้แน่ใจว่าไฟล์จะบันทึกด้วยการเข้ารหัสนี้ อ่าน [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Export::ILinkEmbedController](../ilinkembedcontroller/)\> [get_LinkEmbedController](./get_linkembedcontroller/)() override | คืนอ็อบเจ็กต์ callback ที่ควบคุมวิธีการจัดเก็บอ็อบเจ็กต์ภายนอก อ่าน [Export::ILinkEmbedController](../ilinkembedcontroller/). |
| [Aspose::Slides::Export::TextInheritanceLimit](../textinheritancelimit/) [get_TextInheritanceLimit](./get_textinheritancelimit/)() override | คืนค่าความลึกที่สืบทอดสำหรับคุณสมบัติข้อความ อ่าน [Export::TextInheritanceLimit](../textinheritancelimit/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลเคาน์เตอร์อ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนะล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นอนะล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอนะล็อกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนะล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการอ้างอิง (=). ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_AddClipboardFragmentHeader](./set_addclipboardfragmentheader/)(**bool**) override | ตั้งค่า ระบุว่าควรเพิ่มส่วนหัว Clipboard หรือไม่ เขียน **bool**. |
| void [set_EncodingName](./set_encodingname/)([System::String](../../system/string/)) override | ตั้งชื่อการเข้ารหัส HTML ค่าตัวนี้จะถูกบันทึกลงไฟล์ HTML ที่สร้างขึ้น แต่ขึ้นอยู่กับผู้เรียกเพื่อให้แน่ใจว่าไฟล์จะบันทึกด้วยการเข้ารหัสนี้ เขียน [System::String](../../system/string/). |
| void [set_LinkEmbedController](./set_linkembedcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[Export::ILinkEmbedController](../ilinkembedcontroller/)\>) override | ตั้งอ็อบเจ็กต์ callback ที่ควบคุมวิธีการจัดเก็บอ็อบเจ็กต์ภายนอก เขียน [Export::ILinkEmbedController](../ilinkembedcontroller/). |
| void [set_TextInheritanceLimit](./set_textinheritancelimit/)([Aspose::Slides::Export::TextInheritanceLimit](../textinheritancelimit/)) override | ตั้งค่าความลึกที่สืบทอดสำหรับคุณสมบัติข้อความ เขียน [Export::TextInheritanceLimit](../textinheritancelimit/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
|  [TextToHtmlConversionOptions](./texttohtmlconversionoptions/)() |  |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนะล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ITextToHtmlConversionOptions](../itexttohtmlconversionoptions/)
* เนมสเปส [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)