---
title: TextInfo
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "กำหนดคุณสมบัติข้อความที่เฉพาะเจาะจงตามโลแคล. การทำงานของ setter จะเปิดใช้งานเฉพาะกับอ็อบเจกต์ที่ไม่เป็นแบบอ่านอย่างเดียว. อ็อบเจกต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ System::SmartPtr เสมอและใช้พอยเตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 365
url: /th/system.globalization/textinfo/
---
## TextInfo คลาส


กำหนดคุณสมบัติข้อความที่เฉพาะเจาะจงตามโลแคล. การทำงานของ setter จะเปิดใช้งานเฉพาะกับอ็อบเจกต์ที่ไม่เป็นแบบอ่านอย่างเดียว. อ็อบเจกต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยเตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class TextInfo : public System::ICloneable
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | สร้างสำเนาของอ็อบเจกต์ปัจจุบันและคืนค่าพอยเตอร์แชร์ไปยังอ็อบเจกต์นั้น. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# โดยที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# โดยที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับใช้ภายในเท่านั้น |
| virtual int [get_ANSICodePage](./get_ansicodepage/)() const | ดึงค่า codepage ของ ANSI |
| [String](../../system/string/) [get_CultureName](./get_culturename/)() const | ดึงชื่อวัฒนธรรม |
| virtual int [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | ดึงค่า codepage ของ EBCDIC |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | ตรวจสอบว่าฟอร์แมตเป็นแบบอ่านอย่างเดียวหรือไม่ |
| **bool** [get_IsRightToLeft](./get_isrighttoleft/)() const | ตรวจสอบว่าข้อความถูกเขียนจากซ้ายไปขวาหรือไม่ |
| int [get_LCID](./get_lcid/)() const | ดึงค่า locale ID |
| virtual [String](../../system/string/) [get_ListSeparator](./get_listseparator/)() const | ดึงตัวคั่นรายการ |
| virtual int [get_MacCodePage](./get_maccodepage/)() const | ดึงค่า codepage ของ Macintosh |
| virtual int [get_OEMCodePage](./get_oemcodepage/)() const | ดึงค่า codepage ของ OEM |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| int [GetHashCode](./gethashcode/)() const override | คล้ายเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C# ทำให้สามารถแฮชอ็อบเจกต์แบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจกต์ คล้ายการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์และกำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงกำหนดค่าอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [TextInfo](./)\& [operator=](./operator_equal/)(const [TextInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงกำหนดค่าอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static [TextInfoPtr](../textinfoptr/) [ReadOnly](./readonly/)(const [TextInfoPtr](../textinfoptr/)\&) | ดึงเวอร์ชันอ่านอย่างเดียวของวัฒนธรรม |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายค่า |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์ลงตามค่าที่ระบุ |
| virtual void [set_ListSeparator](./set_listseparator/)([String](../../system/string/)) | กำหนดตัวคั่นรายการ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared) ทำให้สามารถเปลี่ยนพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบแชร์และคืนค่า ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
|  [TextInfo](./textinfo/)(const [TextInfo](./)\&) | ข้อมูล RTTI |
| virtual char_t [ToLower](./tolower/)(char_t) const | แปลงอักขระเป็นตัวพิมพ์เล็ก |
| virtual [String](../../system/string/) [ToLower](./tolower/)([String](../../system/string/)) const | แปลงสตริงเป็นตัวพิมพ์เล็ก |
| [String](../../system/string/) [ToString](./tostring/)() const override | คล้ายเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# ทำให้สามารถแปลงอ็อบเจกต์แบบกำหนดเองเป็นสตริงได้ |
| [String](../../system/string/) [ToTitleCase](./totitlecase/)([String](../../system/string/)) const | แปลงสตริงเป็นรูปแบบ Title Case (ยกเว้นอักษรย่อที่เป็นตัวพิมพ์ใหญ่แล้ว) |
| virtual char_t [ToUpper](./toupper/)(char_t) const | แปลงอักขระเป็นตัวพิมพ์ใหญ่ |
| virtual [String](../../system/string/) [ToUpper](./toupper/)([String](../../system/string/)) const | แปลงสตริงเป็นตัวพิมพ์ใหญ่ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์และปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [ICloneable](../../system/icloneable/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)