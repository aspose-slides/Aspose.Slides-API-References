---
title: FileStream
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แทนสตรีมไฟล์ที่รองรับการอ่านและเขียนแบบ synchronous และ asynchronous. วัตถุของคลาสนี้ควรจะจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บน stack หรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือ assertion fault. ควรห่อคลาสนี้ในพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้ส่งต่อให้ฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 287
url: /th/system.io/filestream/
---
## FileStream คลาส

เป็นตัวแทนของสตรีมไฟล์ที่รองรับการอ่านและเขียนแบบ synchronous และ asynchronous. วัตถุของคลาสนี้ควรจะสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บน stack หรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือ assertion fault. ควรห่อคลาสนี้ในตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อให้ฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
class FileStream : public System::IO::Stream
```
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการอ่านแบบอะซิงโครนัส. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส. |
| void [Close](./close/)() override | ปิดอ็อบเจ็กต์ [FileStream](./) ปัจจุบัน. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | คัดลอกไบต์ไปยังสตรีมที่ระบุ. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | คัดลอกไบต์ไปยังสตรีมที่ระบุโดยใช้ขนาดบัฟเฟอร์ที่ระบุ. |
| void [Dispose](../stream/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจ็กต์ปัจจุบันและปิดสตรีม. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการดำเนินการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | สิ้นสุดการดำเนินการเขียนแบบอะซิงโครนัส. รอจนกว่าการดำเนินการเขียนแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ในกรณีที่ NaN สองค่าได้รับการพิจารณาเป็นเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ในกรณีที่ NaN สองค่าได้รับการพิจารณาเป็นเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | สร้างอินสแตนซ์ใหม่ของคลาส [FileStream](./) และเริ่มต้นด้วยพารามิเตอร์ที่ระบุ. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | สร้างอินสแตนซ์ใหม่ของคลาส [FileStream](./) และเริ่มต้นด้วยพารามิเตอร์ที่ระบุ. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | สร้างอินสแตนซ์ใหม่ของคลาส [FileStream](./) และเริ่มต้นด้วยพารามิเตอร์ที่ระบุ. |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | ล้างบัฟเฟอร์ของสตรีมนี้และเขียนข้อมูลที่บัฟเฟอร์ทั้งหมดไปยังไฟล์พื้นฐาน. |
| void [Flush](./flush/)(**bool**) | ล้างบัฟเฟอร์ของสตรีมนี้และเขียนข้อมูลที่บัฟเฟอร์ทั้งหมดไปยังไฟล์พื้นฐาน. คำพ้องของเมธอด [Flush()](./flush/). |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | ล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส, ทำให้ข้อมูลที่บัฟเฟอร์ใด ๆ ถูกเขียนไปยังอุปกรณ์พื้นฐาน, และตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | ล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส, ทำให้ข้อมูลที่บัฟเฟอร์ใด ๆ ถูกเขียนไปยังอุปกรณ์พื้นฐาน, และตรวจสอบคำขอยกเลิก. |
| **bool** [get_CanRead](./get_canread/)() const override | กำหนดว่าสตรีมสามารถอ่านได้หรือไม่. |
| **bool** [get_CanSeek](./get_canseek/)() const override | กำหนดว่าสตรีมสนับสนุนการเลื่อนตำแหน่งหรือไม่. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | รับค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | กำหนดว่าสตรีมสามารถเขียนได้หรือไม่. |
| **int64_t** [get_Length](./get_length/)() const override | ส่งคืนความยาวของสตรีมเป็นไบต์. |
| [String](../../system/string/) [get_Name](./get_name/)() const | ส่งคืนชื่อของไฟล์ที่ถูกห่อหุ้มโดยอ็อบเจ็กต์ [FileStream](./) ปัจจุบัน. |
| **int64_t** [get_Position](./get_position/)() const override | ส่งคืนตำแหน่งปัจจุบันของสตรีม. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | รับค่าหน่วยมิลลิวินาทีที่กำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | รับค่าหน่วยมิลลิวินาทีที่กำหนดระยะเวลาที่สตรีมจะพยายามเขียนก่อนหมดเวลา. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกอนของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกอนของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอเนกอนของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกอนของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในสแปนไบต์ที่ระบุ. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | อ่านลำดับของไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านลำดับของไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก. |
| **int32_t** [ReadByte](./readbyte/)() override | อ่านไบต์เดียวจากสตรีมและส่งคืนค่าเต็มจำนวน 32 บิตที่เทียบเท่ากับค่าของไบต์ที่อ่าน. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมตามค่าที่ระบุ. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | ตั้งตำแหน่งของสตรีมที่แทนด้วยอ็อบเจ็กต์ปัจจุบัน. |
| void [set_Position](./set_position/)(**int64_t**) override | ล้างบัฟเฟอร์ของสตรีมและจากนั้นตั้งตำแหน่งของสตรีม. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | ตั้งค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | ตั้งค่าหน่วยมิลลิวินาทีที่กำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| void [SetLength](./setlength/)(**int64_t**) override | ตั้งความยาวของสตรีมที่แทนด้วยอ็อบเจ็กต์ปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนจำนวนอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกอนของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิง weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิง weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | เขียนช่วงย่อยของไบต์ที่ระบุจากสแปนไบต์ที่ระบุไปยังสตรีม. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | เขียนลำดับของไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งปัจจุบันภายในสตรีมนี้ตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนลำดับของไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนตำแหน่งปัจจุบันภายในสตรีมนี้ตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | เขียนค่าจำนวนเต็มบวก 8 บิตที่ระบุลงในสตรีม. |
|  [~FileStream](./~filestream/)() | ตัวทำลาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | ค่าตั้งต้นของจำนวนไบต์ที่บัฟเฟอร์ระหว่างการอ่านและเขียน. |
| static [Null](../stream/null/) | สตรีมที่ไม่มีที่เก็บข้อมูลพื้นฐาน. |
## ดูเพิ่มเติม

* คลาส [Stream](../stream/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)