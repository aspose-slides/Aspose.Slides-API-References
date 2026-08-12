---
title: CryptoStream
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "การดำเนินการของ Stream ที่ห่อหุ้ม Stream ที่มีอยู่ด้วยฟังก์ชันการเข้ารหัส วัตถุของคลาสนี้ควรจะจัดสรรด้วยฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันหรือข้อผิดพลาดการตรวจสอบเสมอ ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน"
type: docs
weight: 53
url: /th/system.security.cryptography/cryptostream/
---
## CryptoStream คลาส


Stream implementation that wraps existing stream with a cryptographic function. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CryptoStream : public System::IO::Stream
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการอ่านแบบอะซิงโครนัส. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส. |
| void [Close](./close/)() override | ปิดการเชื่อมต่อ. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | คัดลอกไบต์ไปยังสตรีมที่ระบุ. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | คัดลอกไบต์ไปยังสตรีมที่ระบุโดยใช้ขนาดบัฟเฟอร์ที่ระบุ. |
|  [CryptoStream](./cryptostream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\>\&, [CryptoStreamMode](../cryptostreammode/)) | คอนสตรัคเตอร์. |
| void [Dispose](../../system.io/stream/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่อ็อบเจ็กต์ปัจจุบันใช้และปิดสตรีม. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการดำเนินการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | จบการดำเนินการเขียนแบบอะซิงโครนัส รอจนกว่าการดำเนินการเขียนแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าที่ใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าที่ใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| void [Flush](./flush/)() override | ล้างบัฟเฟอร์เข้าสู่สตรีมที่ห่อหุ้ม ไม่ทำอะไรเนื่องจากอัลกอริทึมแปลงอาจยังคงรอข้อมูลเพิ่มเติม. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | ล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์อยู่ถูกเขียนไปยังอุปกรณ์ฐานและตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | ล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์อยู่ถูกเขียนไปยังอุปกรณ์ฐานและตรวจสอบคำขอยกเลิก. |
| void [FlushFinalBlock](./flushfinalblock/)() | เขียนข้อมูลที่ยังคงอยู่ในบัฟเฟอร์ไปยังสตรีม. |
| **bool** [get_CanRead](./get_canread/)() const override | ตรวจสอบว่าสตรีมสามารถอ่านได้หรือไม่. |
| **bool** [get_CanSeek](./get_canseek/)() const override | ตรวจสอบว่าสตรีมสามารถเลื่อนตำแหน่งได้หรือไม่. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | รับค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | ตรวจสอบว่าสตรีมสามารถเขียนได้หรือไม่. |
| **int64_t** [get_Length](./get_length/)() const override | รับความยาวของสตรีม ไม่รองรับ. |
| **int64_t** [get_Position](./get_position/)() const override | รับตำแหน่งปัจจุบันในสตรีม ไม่รองรับ. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | รับค่าเป็นมิลลิวินาทีที่กำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | รับค่าเป็นมิลลิวินาทีที่กำหนดระยะเวลาที่สตรีมจะพยายามเขียนก่อนหมดเวลา. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอานะล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นอานะล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอานะล็อกของออเปอร์เตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกใช้โดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอานะล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอ้งอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาในคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เตอร์การกำหนดค่า ไม่ได้คัดลอ้งอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาในคลาสย่อย. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | อ่านข้อมูลจากสตรีม. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | อ่านข้อมูลจากสตรีม. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในสแปนไบต์ที่ระบุ. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่านและตรวจสอบคำขอยกเลิก. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่านและตรวจสอบคำขอยกเลิก. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | อ่านไบต์เดียวจากสตรีมและส่งคืนค่าเต็ม 32 บิตที่เทียบเท่ากับค่าของไบต์ที่อ่าน. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เวอร์ชันพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เวอร์ชันพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | เลื่อนตำแหน่งในสตรีม ไม่รองรับ. |
| void [set_Position](./set_position/)(**int64_t**) override | เลื่อนตำแหน่งในสตรีม ไม่รองรับ. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | ตั้งค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | ตั้งค่าเป็นมิลลิวินาทีที่กำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| void [SetLength](./setlength/)(**int64_t**) override | เลื่อนขนาดของสตรีม ไม่รองรับ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (ไม่ใช่ shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง ; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และส่งคืน ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอานะล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | เขียนข้อมูลไปยังสตรีม. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override |เขียนข้อมูลไปยังสตรีม. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาร์เรย์ไบต์ที่ระบุไปยังสตรีม. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | เขียนช่วงย่อยของไบต์ที่ระบุจากสแปนไบต์ที่ระบุไปยังสตรีม. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | เขียนลำดับไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งปัจจุบันในสตรีมตามจำนวนไบต์ที่เขียนและตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนลำดับไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งปัจจุบันในสตรีมตามจำนวนไบต์ที่เขียนและตรวจสอบคำขอยกเลิก. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | เขียนค่าจำนวนเต็มบวก 8-bit ที่ระบุไปยังสตรีม. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Null](../../system.io/stream/null/) | สตรีมที่ไม่มีที่เก็บข้อมูลพื้นฐาน. |

## ดูเพิ่มเติม

* Class [Stream](../../system.io/stream/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)