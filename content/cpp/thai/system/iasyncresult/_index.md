---
title: IAsyncResult
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงสถานะของการทำงานแบบอะซิงโครนัส อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject() มิฉะนั้นห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ให้ห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 898
url: /th/system/iasyncresult/
---
## IAsyncResult คลาส

แสดงสถานะของการทำงานแบบอะซิงโครนัส อ็อบเจ็กต์ของคลาสนี้ควรจะจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/) ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class IAsyncResult : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขจำนวนจริงสไตล์ C# ซึ่ง NaN สองค่าถือว่ามีค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าหรือ NaN ใด ๆ |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขจำนวนเต็มทศนิยมสไตล์ C# ซึ่ง NaN สองค่าถือว่ามีค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าหรือ NaN ใด ๆ |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual [SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [get_AsyncState](./get_asyncstate/)() | คืนค่าอ็อบเจ็กต์ที่บรรจุข้อมูลเกี่ยวกับการทำงานแบบอะซิงโครนัส |
| virtual [SharedPtr](../sharedptr/)\<[System::Threading::WaitHandle](../../system.threading/waithandle/)\> [get_AsyncWaitHandle](./get_asyncwaithandle/)() | คืนค่าอินสแตนซ์ของ WaitHandle ที่สามารถใช้รอการทำงานของการทำงานแบบอะซิงโครนัสให้สำเร็จ |
| virtual **bool** [get_CompletedSynchronously](./get_completedsynchronously/)() | คืนค่าที่ระบุว่าการทำงานแบบอะซิงโครนัสเสร็จสิ้นแบบซิงโครนัสหรือไม่ |
| virtual **bool** [get_IsCompleted](./get_iscompleted/)() | คืนค่าที่ระบุว่าการทำงานแบบอะซิงโครนัสได้เสร็จสิ้นหรือยัง |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เทียบเคียงกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเคียงกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../lockcontext/) sentinel |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็นพอยน์เตอร์แบบอ่อน (weak) แทนที่แชร์ ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อนได้ |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../string/) [ToString](../object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริง |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ดำเนินการสร้าง typeof([System.Object](../object/)) ของ C# |
| void [Unlock](../object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../lockcontext/) sentinel |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงที่อ่อน ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนการอ้างอิงที่อ่อน ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual  [~IAsyncResult](./~iasyncresult/)() | ตัวทำลาย |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## การพิมพ์ใหม่

| การพิมพ์ใหม่ | คำอธิบาย |
| --- | --- |
| [smart_ptr](./smart_ptr/) | พอยน์เตอร์แบบแชร์ไปยัง [IAsyncResult](./). |

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)