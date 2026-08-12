---
title: NameValueHeaderValue
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงคู่คีย์/ค่าเพื่อใช้ในส่วนหัว. อ็อบเจ็กต์ของคลาสนี้ควรจะถูกจัดสรรเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการละเมิดการยืนยัน. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 170
url: /th/system.net.http.headers/namevalueheadervalue/
---
## NameValueHeaderValue คลาส

Represents a key/value pair to use in headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NameValueHeaderValue : public virtual System::ICloneable
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าหนึ่งใด ทั้งค่า NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าหนึ่งใด ทั้งค่า NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\> [Find](./find/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>, [String](../../system/string/)) | ค้นหาอินสแตนซ์ NameValueHeaderValue-class ในคอลเลกชันตามชื่อที่ระบุ. |
| [String](../../system/string/) [get_Name](./get_name/)() | ส่งกลับชื่อของอินสแตนซ์ปัจจุบัน. |
| [String](../../system/string/) [get_Value](./get_value/)() | รับค่าของอินสแตนซ์ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| static **int32_t** [GetHashCode](./gethashcode/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>) | ส่งกลับรหัสแฮชของทุกรายการในคอลเลกชัน. |
| static **int32_t** [GetNameValueLength](./getnamevaluelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\&) | แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุให้เป็นอินสแตนซ์ของคลาส [NameValueHeaderValue](./). |
| static **int32_t** [GetNameValueLength](./getnamevaluelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\&) | แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุให้เป็นอินสแตนซ์ของคลาส [NameValueHeaderValue](./). |
| static **int32_t** [GetNameValueListLength](./getnamevaluelistlength/)([String](../../system/string/), **int32_t**, char16_t, [System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>) | แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นคอลเลกชันของอินสแตนซ์ NameValueHeaderValue-class และส่งกลับความยาวของสตริงย่อยที่วิเคราะห์แล้ว. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int32_t** [GetValueLength](./getvaluelength/)([String](../../system/string/), **int32_t**) | ส่งกลับความยาวของค่าจากดัชนีที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนนิ่งประเภทที่กำหนดเองได้. |
|  [NameValueHeaderValue](./namevalueheadervalue/)() | สร้างอินสแตนซ์ใหม่. |
|  [NameValueHeaderValue](./namevalueheadervalue/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่. |
|  [NameValueHeaderValue](./namevalueheadervalue/)([String](../../system/string/), [String](../../system/string/)) | สร้างอินสแตนซ์ใหม่. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และทำให้ซับคลาสสามารถคัดลอกได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และทำให้ซับคลาสสามารถคัดลอกได้. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | แปลงสตริงที่ส่งเข้ามาให้เป็นอินสแตนซ์ของคลาส [NameValueHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดค่าเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดค่าเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Value](./set_value/)([String](../../system/string/)) | ตั้งค่าของอินสแตนซ์ปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนการใช้ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นแบบ weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static void [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>, char16_t, **bool**, [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>) | ส่งกลับการแสดงผลเป็นสตริงของคอลเลกชันของอินสแตนซ์ NameValueHeaderValue-class. |
| static [String](../../system/string/) [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\>\>, char16_t, **bool**) | ส่งกลับการแสดงผลเป็นสตริงของคอลเลกชันของอินสแตนซ์ NameValueHeaderValue-class. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](./)\>\&) | พยายามแปลงสตริงที่ส่งเข้ามาให้เป็นอินสแตนซ์ของคลาส [NameValueHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เทียบเท่า C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ICloneable](../../system/icloneable/)
* เนมสเปซ [System::Net::Http::Headers](../)
* ไลบรารี [Aspose.Slides](../../)