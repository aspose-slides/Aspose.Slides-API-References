---
title: WebHeaderCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แทนที่การแสดงถึงคอลเลกชันของหัวข้อโปรโตคอล วัตถุของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้งานและ/หรือการตรวจสอบค่าสถานะผิดพลาด เสมอให้นำคลาสนี้หุ้มด้วยตัวชี้ System::SmartPtr แล้วใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 482
url: /th/system.net/webheadercollection/
---
## WebHeaderCollection คลาส

Represents the collection of the protocol headers. Objects of this คลาส should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this คลาส into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebHeaderCollection : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| void [Add](./add/)([String](../../system/string/), [String](../../system/string/)) | เพิ่มคู่ที่ระบุของชื่อหัวเรื่องและค่าหัวเรื่องลงในคอลเลกชัน |
| void [Add](./add/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | เพิ่มคู่ที่ระบุของหัวเรื่องและค่าหัวเรื่องลงในคอลเลกชัน |
| void [Add](./add/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | เพิ่มคู่ที่ระบุของหัวเรื่องและค่าหัวเรื่องลงในคอลเลกชัน |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [AllKeys](./allkeys/)() | คืนคอลเลกชันของชื่อหัวเรื่องที่เก็บไว้ในคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลบทศนิยมแบบ C#-style ที่ NaN สองค่าเป็นค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าจำนวนใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลบทศนิยมแบบ C#-style ที่ NaN สองค่าเป็นค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าจำนวนใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับวัตถุประสงค์ภายในเท่านั้น |
| **int32_t** [get_Count](./get_count/)() const | คืนจำนวนของสมาชิกในคอลเลกชัน |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_Keys](./get_keys/)() | คืนคอลเลกชันของชื่อหัวเรื่องที่เก็บไว้ในคอลเลกชัน |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| [String](../../system/string/) [GetKey](./getkey/)(int) | คืนคีย์ที่ตำแหน่งที่กำหนด |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจกต์ คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [GetValues](./getvalues/)([String](../../system/string/)) | คืนคอลเลกชันของค่าหัวเรื่อง |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpRequestHeader](../httprequestheader/)) | รับค่าหัวเรื่องโดยใช้หัวเรื่องของคำขอที่ระบุ |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpResponseHeader](../httpresponseheader/)) | รับค่าหัวเรื่องโดยใช้หัวเรื่องของการตอบกลับที่ระบุ |
| [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | รับค่าหัวเรื่องโดยใช้ชื่อหัวเรื่องที่ระบุ |
| void [idx_set](./idx_set/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | ตั้งค่าค่าหัวเรื่องของหัวเรื่องที่ระบุ |
| void [idx_set](./idx_set/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | ตั้งค่าค่าหัวเรื่องโดยใช้หัวเรื่องของการตอบกลับที่ระบุ |
| void [idx_set](./idx_set/)([String](../../system/string/), [String](../../system/string/)) | ตั้งค่าค่าหัวเรื่องโดยใช้ชื่อหัวเรื่องที่ระบุ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C# |
| static **bool** [IsRestricted](./isrestricted/)(const [String](../../system/string/)\&) | ตรวจสอบว่าหัวเรื่อง HTTP ที่ระบุสามารถตั้งค่าสำหรับคำขอได้หรือไม่ |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนของชนิดที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คัดลอกคอนสตรักเตอร์ ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| void [Remove](./remove/)([String](../../system/string/)) | ลบหัวเรื่องตามชื่อหัวเรื่องที่ระบุ |
| void [Remove](./remove/)([HttpResponseHeader](../httpresponseheader/)) | ลบหัวเรื่องของการตอบกลับที่ระบุ |
| void [Remove](./remove/)([HttpRequestHeader](../httprequestheader/)) | ลบหัวเรื่องของคำขอที่ระบุ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับการอ้างอิงร่วมโดยค่าที่ระบุ |
| void [Set](./set/)([String](../../system/string/), [String](../../system/string/)) | ตั้งค่าของหัวเรื่องที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนการเป็น shared) อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| [String](../../system/string/) [ToString](./tostring/)() const override | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิง weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิง weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
|  [WebHeaderCollection](./webheadercollection/)() | สร้างอินสแตนซ์ใหม่ |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)