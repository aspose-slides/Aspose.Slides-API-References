---
title: Stream
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "คลาสฐานสำหรับการใช้งานสตรีมหลายรูปแบบ การสร้างออบเจ็กต์ของคลาสนี้ต้องทำผ่านฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดในระหว่างรันไทม์หรือการตรวจสอบข้อผิดพลาด ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 365
url: /th/system.io/stream/
---
## คลาส Stream

A base class for a variety of stream implementations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Stream : public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการอ่านแบบอะซิงโครนัส |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการเขียนแบบอะซิงโครนัส |
| virtual void [Close](./close/)() | ปิดสตรีม |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&) | คัดลอกไบต์ไปยังสตรีมที่ระบุ |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&, **int32_t**) | คัดลอกไบต์ไปยังสตรีมที่ระบุ โดยใช้ขนาดบัฟเฟอร์ที่ระบุ |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยออบเจ็กต์ปัจจุบันและปิดสตรีม |
| virtual int [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการอ่านแบบอะซิงโครนัสที่ระบุตัวจะเสร็จสิ้น |
| virtual void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | จบการเขียนแบบอะซิงโครนัส รอจนกว่าการเขียนแบบอะซิงโครนัสที่ระบุตัวจะเสร็จสิ้น |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้เซมนติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual void [Flush](./flush/)() | ล้างบัฟเฟอร์ของสตรีมนี้และเขียนข้อมูลที่บัฟเฟอร์ทั้งหมดไปยังที่เก็บข้อมูลพื้นฐาน |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | ล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์ใด ๆ ถูกเขียนไปยังอุปกรณ์พื้นฐาน และตรวจสอบคำขอยกเลิก |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)() | ล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์ใด ๆ ถูกเขียนไปยังอุปกรณ์พื้นฐาน และตรวจสอบคำขอยกเลิก |
| virtual **bool** [get_CanRead](./get_canread/)() const | กำหนดว่าสตรีมสามารถอ่านได้หรือไม่ |
| virtual **bool** [get_CanSeek](./get_canseek/)() const | กำหนดว่าสตรีมสนับสนุนการเลื่อนตำแหน่งหรือไม่ |
| virtual **bool** [get_CanTimeout](./get_cantimeout/)() const | รับค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่ |
| virtual **bool** [get_CanWrite](./get_canwrite/)() const | กำหนดว่าสตรีมสามารถเขียนได้หรือไม่ |
| virtual **int64_t** [get_Length](./get_length/)() const | คืนความยาวของสตรีมเป็นไบต์ |
| virtual **int64_t** [get_Position](./get_position/)() const | คืนตำแหน่งปัจจุบันของสตรีม |
| virtual int [get_ReadTimeout](./get_readtimeout/)() const | รับค่าที่หน่วยเป็นมิลลิวินาที ซึ่งกำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา |
| virtual int [get_WriteTimeout](./get_writetimeout/)() const | รับค่าที่หน่วยเป็นมิลลิวินาที ซึ่งกำหนดระยะเวลาที่สตรีมจะพยายามเขียนก่อนหมดเวลา |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C# ทำให้สามารถแฮชออบเจ็กต์แบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ คล้ายการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายการใช้โอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ทำให้สามารถสำเนาชนิดที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้ทำการคัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดให้คอนสตรัคเตอร์คัดลอกของซับคลาสทำงาน |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้ทำการคัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดให้คอนสตรัคเตอร์คัดลอกของซับคลาสทำงาน |
| virtual **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ |
| virtual **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ |
| **int32_t** [Read](./read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ |
| virtual **int32_t** [Read](./read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในสแปนไบต์ที่ระบุ |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | อ่านลำดับของไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนไปข้างหน้าในสตรีมตามจำนวนไบต์ที่อ่านได้ และตรวจสอบคำขอยกเลิก |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านลำดับของไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนไปข้างหน้าในสตรีมตามจำนวนไบต์ที่อ่านได้ และตรวจสอบคำขอยกเลิก |
| virtual int [ReadByte](./readbyte/)() | อ่านไบต์เดียวจากสตรีมและคืนค่าเต็ม 32 บิตที่เทียบค่าเดียวกับไบต์ที่อ่าน |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่ากับ nullptr ตามอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำสเปเชียลไลซ์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำสเปเชียลไลซ์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์โดยค่าที่ระบุ |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) | ตั้งตำแหน่งของสตรีมที่แทนโดยออบเจ็กต์ปัจจุบัน |
| virtual void [set_Position](./set_position/)(**int64_t**) | ตั้งตำแหน่งของสตรีม |
| virtual void [set_ReadTimeout](./set_readtimeout/)(int) | ตั้งค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่ |
| virtual void [set_WriteTimeout](./set_writetimeout/)(int) | ตั้งค่าที่หน่วยมิลลิวินาที เพื่อกำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา |
| virtual void [SetLength](./setlength/)(**int64_t**) | ตั้งความยาวของสตรีมที่แทนโดยออบเจ็กต์ปัจจุบัน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบแชร์และคืนค่า ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทนการเรียกโดยตรง |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# ทำให้สามารถแปลงออบเจ็กต์แบบกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือนการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยต์เตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม |
| void [Write](./write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | เขียนช่วงย่อยของไบต์ที่ระบุจากสแปนไบต์ที่ระบุไปยังสตรีม |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | เขียนลำดับของไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนไปข้างหน้าในสตรีมตามจำนวนไบต์ที่เขียนและตรวจสอบคำขอยกเลิก |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนลำดับของไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนไปข้างหน้าในสตรีมตามจำนวนไบต์ที่เขียนและตรวจสอบคำขอยกเลิก |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | เขียนค่าจำนวนเต็มบวก 8-bit ที่ระบุไปยังสตรีม |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์และคืนหน่วยความจำของโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Null](./null/) | สตรีมที่ไม่มีที่จัดเก็บข้อมูลพื้นฐาน |

## นิยามประเภท

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังคลาสนี้ |

## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)