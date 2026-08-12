---
title: UnmanagedMemoryStream
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ให้การเข้าถึงหน่วยความจำที่ไม่ได้จัดการ วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการละเมิดการยืนยันค่า เสมอห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 456
url: /th/system.io/unmanagedmemorystream/
---
## คลาส UnmanagedMemoryStream

ให้การเข้าถึงหน่วยความจำที่ไม่ได้จัดการได้ วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการละเมิดการยืนยันค่า เสมอห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการอ่านแบบอะซิงโครนัส. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส. |
| virtual void [Close](../stream/close/)() | ปิดสตรีม. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | คัดลอกไบต์ไปยังสตรีมที่ระบุ. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | คัดลอกไบต์ไปยังสตรีมที่ระบุโดยใช้ขนาดบัฟเฟอร์ที่กำหนด. |
| void [Dispose](../stream/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่วัตถุปัจจุบันใช้งานและปิดสตรีม. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการดำเนินการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | จบการดำเนินการเขียนแบบอะซิงโครนัส รอจนกว่าการดำเนินการเขียนแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าได้รับการถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าได้รับการถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อใช้ภายในเท่านั้น. |
| void [Flush](./flush/)() override | ไม่ทำอะไร. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | ทำความสะอาดบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์อยู่ถูกเขียนไปยังอุปกรณ์พื้นฐาน และตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | ทำความสะอาดบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์อยู่ถูกเขียนไปยังอุปกรณ์พื้นฐาน และตรวจสอบคำขอยกเลิก. |
| **bool** [get_CanRead](./get_canread/)() const override | กำหนดว่าสตรีมสามารถอ่านได้หรือไม่. |
| **bool** [get_CanSeek](./get_canseek/)() const override | กำหนดว่าสตรีมสนับสนุนการเลื่อนตำแหน่งหรือไม่. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | รับค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | กำหนดว่าสตรีมสามารถเขียนได้หรือไม่. |
| virtual **int64_t** [get_Capacity](./get_capacity/)() const | ส่งคืนความจุปัจจุบันของบัฟเฟอร์หน่วยความจำพื้นฐาน. |
| **int64_t** [get_Length](./get_length/)() const override | ส่งคืนความยาวของสตรีมเป็นไบต์. |
| **int64_t** [get_Position](./get_position/)() const override | ส่งคืนตำแหน่งปัจจุบันของสตรีม. |
| **uint8_t** * [get_PositionPointer](./get_positionpointer/)() | ไม่ได้ดำเนินการ. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | รับค่าเป็นมิลลิวินาทีที่กำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | รับค่าเป็นมิลลิวินาทีที่กำหนดระยะเวลาที่สตรีมจะพยายามเขียนก่อนหมดเวลา. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบเดียวกับเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C# ทำให้สามารถทำแฮชวัตถุที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ เป็นแบบเดียวกับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นแบบเดียวกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบเดียวกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ทำให้สามารถทำสำเนาชนิดที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์สำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์สำหรับคลาสย่อย. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่กำหนด. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่กำหนด. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่กำหนด. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในสแปนไบต์ที่กำหนด. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งในสตรีมตามจำนวนไบต์ที่อ่าน และตรวจสอบคำขอยกเลิก. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งในสตรีมตามจำนวนไบต์ที่อ่าน และตรวจสอบคำขอยกเลิก. |
| virtual int [ReadByte](../stream/readbyte/)() | อ่านไบต์เดียวจากสตรีมและส่งคืนค่าจำนวนเต็ม 32 บิตที่เทียบเท่าค่าของไบต์ที่อ่าน. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงแบบแชร์โดยค่าที่ระบุ. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | ตั้งค่าตำแหน่งของสตรีมที่วัตถุปัจจุบันแทน. |
| void [set_Position](./set_position/)(**int64_t**) override | ตั้งค่าตำแหน่งของสตรีม. |
| void [set_PositionPointer](./set_positionpointer/)(**uint8_t** *) | ไม่ได้ดำเนินการ. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | ตั้งค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | ตั้งค่าเป็นมิลลิวินาทีที่กำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| void [SetLength](./setlength/)(**int64_t**) override | ไม่ได้ดำเนินการ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็นพอยน์เตอร์แบบ weak (แทนที่ shared) ช่วยให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนจำนวนอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบเดียวกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# ทำให้แปลงวัตถุกำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**) | สร้างอินสแตนซ์ใหม่ของ [UnmanagedMemoryStream](./). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**, **int64_t**, [FileAccess](../fileaccess/)) | สร้างอินสแตนซ์ใหม่ของ [UnmanagedMemoryStream](./). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ไม่ได้ดำเนินการ. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | ไม่ได้ดำเนินการ. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์จากอาเรย์ไบต์ที่ระบุลงในสตรีม. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | เขียนช่วงย่อยของไบต์จากสแปนไบต์ที่ระบุลงในสตรีม. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | เขียนลำดับไบต์ลงในสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งปัจจุบันในสตรีมตามจำนวนไบต์ที่เขียน และตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนลำดับไบต์ลงในสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งปัจจุบันในสตรีมตามจำนวนไบต์ที่เขียน และตรวจสอบคำขอยกเลิก. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | เขียนค่าจำนวนเต็มบวก 8 บิตที่ระบุลงในสตรีม. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Null](../stream/null/) | สตรีมที่ไม่มีหน่วยความจำพื้นฐาน. |

## ดูเพิ่มเติม

* คลาส [Stream](../stream/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)