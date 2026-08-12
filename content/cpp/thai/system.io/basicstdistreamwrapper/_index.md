---
title: BasicSTDIStreamWrapper
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แสดงถึง wrapper แบบ System.IO.Stream สำหรับ std::basic_istream และอ็อบเจกต์ที่สืบทอดจากมัน. อ็อบเจกต์ของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบเงื่อนไข. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 14
url: /th/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper คลาส


แสดงถึง wrapper แบบ [System.IO.Stream](../stream/) สำหรับ std::basic_istream และอ็อบเจกต์ที่สืบทอดจากมัน. วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบเงื่อนไข. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | สร้างอินสแตนซ์ใหม่ของ [BasicSTDIStreamWrapper](./). |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | คอนสตรัคเตอร์สำเนา. ถูกลบ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการอ่านแบบอะซิงโครนัส. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส. |
| virtual void [Close](../stream/close/)() | ปิดสตรีม. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | คัดลอกไบต์ไปยังสตรีมที่ระบุ. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | คัดลอกไบต์ไปยังสตรีมที่ระบุ โดยใช้ขนาดบัฟเฟอร์ที่ระบุ. |
| [Dispose](../stream/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจกต์ปัจจุบันและปิดสตรีม. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | จบการเขียนแบบอะซิงโครนัส. รอจนกว่าการเขียนแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| void [Flush](./flush/)() override | ล้างบัฟเฟอร์ของสตรีมนี้และเขียนข้อมูลที่บัฟเฟอร์ทั้งหมดไปยังที่เก็บพื้นฐาน. ไม่รองรับ! |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | ทำความสะอาดบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส, ทำให้ข้อมูลที่บัฟเฟอร์ถูกเขียนไปยังอุปกรณ์พื้นฐานและตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | ทำความสะอาดบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส, ทำให้ข้อมูลที่บัฟเฟอร์ถูกเขียนไปยังอุปกรณ์พื้นฐานและตรวจสอบคำขอยกเลิก. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | กำหนดว่าสตรีมรองรับการเลื่อนตำแหน่งหรือไม่. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | รับค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาหรือไม่. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | กำหนดว่าสตรีมรองรับการเขียนหรือไม่. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | ส่งคืนความยาวของสตรีม. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | ส่งคืนตำแหน่งปัจจุบันของสตรีม. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | รับค่าเป็นมิลลิวินาทีที่กำหนดเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | รับค่าเป็นมิลลิวินาทีที่กำหนดเวลาที่สตรีมจะพยายามเขียนก่อนหมดเวลา. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เทียบเท่าการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เทียบเท่าตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกของซับคลาส. |
| [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | ตัวดำเนินการกำหนดค่าแบบคัดลอก. ถูกลบ. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | ตัวดำเนินการกำหนดค่าแบบคัดลอก. ถูกลบ. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกของซับคลาส. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ถ้าโหมดห่อเป็นไบนารี จะอ่านจำนวนไบต์ที่ระบุจากสตรีม มิฉะนั้นจะอ่านจำนวนอักขระที่ระบุแล้วแปลงเป็นประเภท **uint8_t**. เขียนผลการอ่านไปยังอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในสเปนไบต์ที่ระบุ. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก. |
| int [ReadByte](./readbyte/)() override | ถ้าโหมดห่อเป็นไบนารี จะอ่านไบต์เดียวจากที่เก็บอักขระที่ถอดรหัสล่าสุด มิฉะนั้นจะอ่านอักขระเดียวจากสตรีมและแปลงเป็นประเภท **uint8_t**. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr ตามการอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำ specialize ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำ specialize ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงร่วมตามค่าที่ระบุ. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | ข้อมูล RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | ตั้งตำแหน่งของสตรีมที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | ตั้งตำแหน่งของสตรีม. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | ตั้งค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | ตั้งค่าที่เป็นมิลลิวินาทีกำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| void [SetLength](./setlength/)(**int64_t**) override | ตั้งความยาวของสตรีมที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน. ไม่รองรับ! |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). ให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | คอนสตรัคเตอร์สำเนา. ถูกลบ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่านับการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่านับการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ถ้าโหมดห่อเป็นไบนารี จะเขียนช่วงย่อยของไบต์จากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม มิฉะนั้นจะแปลงช่วงย่อยของไบต์จากอาร์เรย์ที่ระบุเป็นประเภท char_type แล้วเขียนผลลัพธ์ไปยังสตรีม. ไม่รองรับ! |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | เขียนช่วงย่อยของไบต์จากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์จากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | เขียนช่วงย่อยของไบต์จากสเปนไบต์ที่ระบุไปยังสตรีม. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | เขียนลำดับไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งปัจจุบันในสตรีมตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนลำดับไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งปัจจุบันในสตรีมตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | ถ้าโหมดห่อเป็นไบนารี จะเขียนค่าตัวเลข 8-bit ไม่เป็นลบที่ระบุไปยังสตรีม มิฉะนั้นจะแปลงเป็นประเภท char_type แล้วเขียนผลลัพธ์ไปยังสตรีม. ไม่รองรับ! |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Null](../stream/null/) | สตรีมที่ไม่มีการจัดเก็บพื้นฐาน. |

## นิยามประเภท

| นิยามประเภท | คำอธิบาย |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## ดูเพิ่ม

* คลาส [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)