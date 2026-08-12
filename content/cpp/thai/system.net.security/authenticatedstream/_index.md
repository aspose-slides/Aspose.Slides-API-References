---
title: AuthenticatedStream
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "มีเมธอดสำหรับส่งข้อมูลรับรองผ่านสตรีม วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ เสมอห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 1
url: /th/system.net.security/authenticatedstream/
---
## AuthenticatedStream คลาส

มีเมธอดสำหรับส่งข้อมูลรับรองผ่านสตรีม วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ การห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการอ่านแบบอะซิงโครนัส |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส |
| virtual void [Close](../../system.io/stream/close/)() | ปิดสตรีม |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | คัดลอกไบต์ไปยังสตรีมที่ระบุ |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | คัดลอกไบต์ไปยังสตรีมที่ระบุโดยใช้ขนาดบัฟเฟอร์ที่กำหนด |
| void [Dispose](../../system.io/stream/dispose/)() override | ปลดปล่อยทรัพยากรทั้งหมดที่วัตถุปัจจุบันใช้และปิดสตรีม |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการดำเนินการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | สิ้นสุดการดำเนินการเขียนแบบอะซิงโครนัส รอจนกว่าการดำเนินการเขียนแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทค่าตามสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual void [Flush](../../system.io/stream/flush/)() | ล้างบัฟเฟอร์ของสตรีมนี้และเขียนข้อมูลที่บัฟเฟอร์ทั้งหมดไปยังที่เก็บข้อมูลพื้นฐาน |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | ทำการล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์ใด ๆ ถูกเขียนไปยังอุปกรณ์พื้นฐาน และตรวจสอบคำขอยกเลิก |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | ทำการล้างบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส ทำให้ข้อมูลที่บัฟเฟอร์ใด ๆ ถูกเขียนไปยังอุปกรณ์พื้นฐาน และตรวจสอบคำขอยกเลิก |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | ตรวจสอบว่าสตรีมสามารถอ่านได้หรือไม่ |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | ตรวจสอบว่าสตรีมรองรับการเลื่อนตำแหน่งหรือไม่ |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | รับค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่ |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | ตรวจสอบว่าสตรีมสามารถเขียนได้หรือไม่ |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | ส่งคืนค่าที่บ่งบอกว่าการตรวจสอบความถูกต้องสำเร็จหรือไม่ |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | ส่งคืนค่าที่บ่งบอกว่าข้อมูลที่ส่งผ่านสตรีมนี้ถูกเข้ารหัสหรือไม่ |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | ส่งคืนค่าที่บ่งบอกว่าเซิร์ฟเวอร์และไคลเอนต์ได้รับการตรวจสอบหรือไม่ |
| virtual **bool** [get_IsServer](./get_isserver/)() const | ส่งคืนค่าที่บ่งบอกว่าข้างฝั่งของการเชื่อมต่อที่เป็นเครื่องในเป็นเซิร์ฟเวอร์หรือไม่ |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | ส่งคืนค่าที่บ่งบอกว่าข้อมูลที่ส่งผ่านสตรีมนี้มีลายเซ็นหรือไม่ |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | ส่งคืนสตรีมที่ใช้โดยออปเจกต์ของคลาสนี้สำหรับการส่งและรับข้อมูล |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | ส่งคืนความยาวของสตรีมเป็นไบต์ |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | ส่งคืนตำแหน่งปัจจุบันของสตรีม |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | รับค่าที่กำหนดเป็นมิลลิวินาที ซึ่งบ่งบอกระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | รับค่าที่กำหนดเป็นมิลลิวินาที ซึ่งบ่งบอกระยะเวลาที่สตรีมจะพยายามเขียนก่อนหมดเวลา |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลของตัวนับการอ้างอิงที่เกี่ยวข้องกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายด้วย targetType หรือไม่. เป็นแบบจำลองของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในอาเรย์ไบต์ที่ระบุ |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนลงในสเปนไบต์ที่ระบุ |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่านและตรวจสอบคำขอยกเลิก |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่านและตรวจสอบคำขอยกเลิก |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | อ่านไบต์เดียวจากสตรีมและส่งคืนค่าเต็มจำนวน 32-bit ที่เทียบเท่ากับค่าของไบต์ที่อ่าน |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | ตั้งตำแหน่งของสตรีมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | ตั้งตำแหน่งของสตรีม |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | ตั้งค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่ |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | ตั้งค่าที่กำหนดเป็นมิลลิวินาที ซึ่งบ่งบอกระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | ตั้งความยาวของสตรีมที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และส่งคืน ไม่ควรเรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | เขียนช่วงย่อยของไบต์ที่ระบุจากสเปนไบต์ที่ระบุไปยังสตรีม |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | เขียนลำดับไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งปัจจุบันภายในสตรีมตามจำนวนไบต์ที่เขียนและตรวจสอบคำขอยกเลิก |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนลำดับไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส เลื่อนตำแหน่งปัจจุบันภายในสตรีมตามจำนวนไบต์ที่เขียนและตรวจสอบคำขอยกเลิก |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | เขียนค่า unsigned 8-bit integer ที่ระบุไปยังสตรีม |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Null](../../system.io/stream/null/) | สตรีมที่ไม่มีที่เก็บข้อมูลพื้นฐาน |

## ดูเพิ่มเติม

* คลาส [Stream](../../system.io/stream/)
* เนมสเปซ [System::Net::Security](../)
* ไลบรารี [Aspose.Slides](../../)