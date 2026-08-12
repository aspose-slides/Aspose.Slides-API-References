---
title: BasicSTDOStreamWrapper
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เป็น wrapper แบบคล้าย System.IO.Stream สำหรับ std::basic_ostream และอ็อบเจกต์ที่สืบทอดจากมัน. อ็อบเจกต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาด runtime และ/หรือ assertion faults. ควรห่อคลาสนี้ด้วย pointer System::SmartPtr และใช้ pointer นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 27
url: /th/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper คลาส


Represents a [System.IO.Stream](../stream/)-like wrapper for std::basic_ostream and its derived objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | สร้างอินสแตนซ์ใหม่ของ [BasicSTDOStreamWrapper](./). |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | คอนสตรัคเตอร์คัดลอก. ถูกลบ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการอ่านแบบอะซิงโครนัส. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการเขียนแบบอะซิงโครนัส. |
| virtual void [Close](../stream/close/)() | ปิดสตรีม. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | คัดลอกไบต์ไปยังสตรีมที่ระบุ. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | คัดลอกไบต์ไปยังสตรีมที่ระบุ โดยใช้ขนาดบัฟเฟอร์ที่ระบุ. |
| void [Dispose](../stream/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจกต์ปัจจุบันและปิดสตรีม. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | รอจนกระทั่งการอ่านแบบอะซิงโครนัสที่ระบุเสร็จสิ้น. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | จบการเขียนแบบอะซิงโครนัส. รอจนกระทั่งการเขียนแบบอะซิงโครนัสที่ระบุเสร็จสิ้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบอ้างอิงตามสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบค่า ตามสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| void [Flush](./flush/)() override | ล้างบัฟเฟอร์ของสตรีมนี้และเขียนข้อมูลที่บัฟเฟอร์ทั้งหมดไปยังที่เก็บข้อมูลพื้นฐาน. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | ล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์ใด ๆ ถูกเขียนไปยังอุปกรณ์พื้นฐานและตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | ล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์ใด ๆ ถูกเขียนไปยังอุปกรณ์พื้นฐานและตรวจสอบคำขอยกเลิก. |
| **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | กำหนดว่าสตรีมสนับสนุนการอ่านหรือไม่. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | กำหนดว่าสตรีมสนับสนุนการเลื่อนไปหา (seek) หรือไม่. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | รับค่าเพื่อตัดสินใจว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | คืนความยาวของสตรีม. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | คืนตำแหน่งปัจจุบันของสตรีม. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | รับค่าเป็นมิลลิวินาทีที่กำหนดว่าสตรีมจะพยายามอ่านเป็นระยะเวลานานแค่ไหนก่อนหมดเวลา. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | รับค่าเป็นมิลลิวินาทีที่กำหนดว่าสตรีมจะพยายามเขียนเป็นระยะเวลานานแค่ไหนก่อนหมดเวลา. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อกเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการสร้างแฮชของอ็อกเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อกเจกต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อกเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | จำลองการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อกเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อกเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | ตัวดำเนินการกำหนดค่าแบบคัดลอก. ถูกลบ. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | ตัวดำเนินการกำหนดค่าแบบคัดลอก. ถูกลบ. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อกเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ถ้าโหมดการห่อหุ้มเป็นไบนารี จะอ่านจำนวนไบต์ที่ระบุจากสตรีม มิฉะนั้นจะอ่านจำนวนอักขระที่ระบุและแปลงเป็นประเภท **uint8_t**. เขียนผลลัพธ์การอ่านไปยังอาร์เรย์ไบต์ที่ระบุ. ไม่รองรับ! |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนไปยังอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนไปยังอาร์เรย์ไบต์ที่ระบุ. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนไปยังสปรานไบต์ที่ระบุ. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก. |
| int [ReadByte](./readbyte/)() override | ถ้าโหมดการห่อหุ้มเป็นไบนารี จะอ่านไบต์เดียวจากที่เก็บตัวอักษรที่ถอดรหัสล่าสุด มิฉะนั้นจะอ่านอักขระเดียวจากสตรีมและแปลงเป็นประเภท **uint8_t**. ไม่รองรับ! |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อกเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อกเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อกเจกต์แบบค่า กับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | ข้อมูล RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | ตั้งตำแหน่งของสตรีมที่แสดงโดยอ็อกเจกต์ปัจจุบัน. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | ตั้งตำแหน่งของสตรีม. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | ตั้งค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | ตั้งค่าที่เป็นมิลลิวินาทีเพื่อกำหนดว่าสตรีมจะพยายามอ่านเป็นระยะเวลานานแค่ไหนก่อนหมดเวลา. |
| void [SetLength](./setlength/)(**int64_t**) override | ตั้งความยาวของสตรีมที่แสดงโดยอ็อกเจกต์ปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | คอนสตรัคเตอร์คัดลอก. ถูกลบ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อกเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | จำลองการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | จำลองการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ถ้าโหมดการห่อหุ้มเป็นไบนารี จะเขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม มิฉะนั้นจะแปลงช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์เป็นประเภท char_type แล้วเขียนผลลัพธ์ไปยังสตรีม. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ไปยังสตรีม. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ไปยังสตรีม. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | เขียนช่วงย่อยของไบต์ที่ระบุจากสปรานไบต์ไปยังสตรีม. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | เขียนลำดับไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อตำแหน่งปัจจุบันภายในสตรีมตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนลำดับไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อตำแหน่งปัจจุบันภายในสตรีมตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | ถ้าโหมดการห่อหุ้มเป็นไบนารี จะเขียนค่าจำนวนเต็มบวก 8-bit ที่ระบุไปยังสตรีม มิฉะนั้นจะแปลงเป็นประเภท char_type แล้วเขียนผลลัพธ์ไปยังสตรีม. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อกเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| Field | คำอธิบาย |
| --- | --- |
| static [Null](../stream/null/) | สตรีมที่ไม่มีการจัดเก็บพื้นฐาน. |

## นิยามชนิด

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## ดูเพิ่มเติม

* คลาส [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)