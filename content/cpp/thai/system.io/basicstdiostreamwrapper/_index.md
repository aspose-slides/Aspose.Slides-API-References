---
title: BasicSTDIOStreamWrapper
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เป็นตัวห่อคล้าย System.IO.Stream สำหรับ std::basic_iostream และออบเจ็กต์ที่สืบทอดจากมัน. ออบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr เสมอและใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 1
url: /th/system.io/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper คลาส

เป็นตัวห่อคล้าย [System.IO.Stream](../stream/) สำหรับ std::basic_iostream และออบเจ็กต์ที่สืบทอดจากมัน. ออบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการล้มเหลวของการตรวจสอบความถูกต้อง. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
template<typename T,typename>class BasicSTDIOStreamWrapper : public System::IO::BasicSTDIStreamWrapper<T>,
                                                             public System::IO::BasicSTDOStreamWrapper<T>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(std::basic_iostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/), [STDIOStreamPositionPreference](../stdiostreampositionpreference/)) | สร้างอินสแตนซ์ใหม่ของ [BasicSTDIOStreamWrapper](./). |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(const [BasicSTDIOStreamWrapper](./)\&) | คอนสตรัคเตอร์คัดลอก. ถูกลบ. |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | สร้างอินสแตนซ์ใหม่ของ [BasicSTDIStreamWrapper](../basicstdistreamwrapper/). |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | คอนสตรัคเตอร์คัดลอก. ถูกลบ. |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | สร้างอินสแตนซ์ใหม่ของ [BasicSTDOStreamWrapper](../basicstdostreamwrapper/). |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | คอนสตรัคเตอร์คัดลอก. ถูกลบ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการอ่านแบบอะซิงโครนัส. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส. |
| virtual void [Close](../stream/close/)() | ปิดสตรีม. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | คัดลอกไบต์ไปยังสตรีมที่ระบุ. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | คัดลอกไบต์ไปยังสตรีมที่ระบุโดยใช้ขนาดบัฟเฟอร์ที่ระบุ. |
| void [Dispose](../stream/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ออบเจ็กต์ปัจจุบันใช้และปิดสตรีม. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการดำเนินการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | สิ้นสุดการดำเนินการเขียนแบบอะซิงโครนัส. รอจนกว่าการดำเนินการเขียนแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| void [Flush](./flush/)() override | ล้างบัฟเฟอร์ของสตรีมนี้และเขียนข้อมูลที่บัฟเฟอร์ทั้งหมดไปยังที่เก็บพื้นฐาน. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | ทำความสะอาดบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส, ทำให้ข้อมูลที่บัฟเฟอร์ถูกเขียนไปยังอุปกรณ์พื้นฐานและตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | ทำความสะอาดบัฟเฟอร์ทั้งหมดของสตรีมนี้แบบอะซิงโครนัส, ทำให้ข้อมูลที่บัฟเฟอร์ถูกเขียนไปยังอุปกรณ์พื้นฐานและตรวจสอบคำขอยกเลิก. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | กำหนดว่าสตรีมสนับสนุนการเลื่อนตำแหน่งหรือไม่. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | รับค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | กำหนดว่าสตรีมสนับสนุนการเขียนหรือไม่. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | คืนความยาวของสตรีม. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | คืนตำแหน่งปัจจุบันของสตรีม. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | รับค่าที่เป็นมิลลิวินาทีกำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | รับค่าที่เป็นมิลลิวินาทีกำหนดระยะเวลาที่สตรีมจะพยายามเขียนก่อนหมดเวลา. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อานาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. อานาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType อธิบายหรือไม่. อานาล็อกของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อานาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนา. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [BasicSTDIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIOStreamWrapper](./)\&) | โอเปอเรเตอร์การกำหนดค่าแบบคัดลอก. ถูกลบ. |
| [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\& [operator=](../basicstdistreamwrapper/operator_equal/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | โอเปอเรเตอร์การกำหนดค่าแบบคัดลอก. ถูกลบ. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | โอเปอเรเตอร์การกำหนดค่าแบบคัดลอก. ถูกลบ. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\& [operator=](../basicstdostreamwrapper/operator_equal/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | โอเปอเรเตอร์การกำหนดค่าแบบคัดลอก. ถูกลบ. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | หากโหมดห่อเป็นไบนารี, อ่านจำนวนไบต์ที่ระบุจากสตรีม, หากไม่เป็นไบนารีอ่านจำนวนอักขระที่ระบุและแปลงเป็นประเภท **uint8_t**. เขียนผลลัพธ์ของการอ่านไปยังอาเรย์ไบต์ที่ระบุ. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนไปยังอาเรย์ไบต์ที่ระบุ. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนไปยังอาเรย์ไบต์ที่ระบุ. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | อ่านจำนวนไบต์ที่ระบุจากสตรีมและเขียนไปยังสเปนไบต์ที่ระบุ. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนไปยังตำแหน่งในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | อ่านลำดับไบต์จากสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนไปยังตำแหน่งในสตรีมตามจำนวนไบต์ที่อ่าน, และตรวจสอบคำขอยกเลิก. |
| int [ReadByte](./readbyte/)() override | หากโหมดห่อเป็นไบนารี, อ่านไบต์เดียวจากที่เก็บอักขระที่ถอดรหัสล่าสุด, หากไม่เป็นไบนารีอ่านอักขระเดียวจากสตรีมและแปลงเป็นประเภท **uint8_t**. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | ข้อมูล RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | ตั้งตำแหน่งของสตรีมที่อธิบายโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | ตั้งตำแหน่งของสตรีม. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | ตั้งค่าที่กำหนดว่าสตรีมปัจจุบันสามารถหมดเวลาได้หรือไม่. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | ตั้งค่าที่เป็นมิลลิวินาทีกำหนดระยะเวลาที่สตรีมจะพยายามอ่านก่อนหมดเวลา. |
| void [SetLength](./setlength/)(**int64_t**) override | ตั้งความยาวของสตรีมที่อธิบายโดยอ็อบเจ็กต์ปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). เปิดให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | คอนสตรัคเตอร์คัดลอก. ถูกลบ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อานาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | หากโหมดห่อเป็นไบนารี, เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม, หากไม่เป็นไบนารีแปลงช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์เป็นประเภท char_type แล้วเขียนผลลัพธ์ไปยังสตรีม. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่ระบุไปยังสตรีม. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | เขียนช่วงย่อยของไบต์ที่ระบุจากสเปนไบต์ที่ระบุไปยังสตรีม. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | เขียนลำดับไบต์ไปยังสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนไปยังตำแหน่งปัจจุบันในสตรีมตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | เขียนลำดับไบต์ไปถึงสตรีมปัจจุบันแบบอะซิงโครนัส, เลื่อนไปยังตำแหน่งปัจจุบันในสตรีมตามจำนวนไบต์ที่เขียน, และตรวจสอบคำขอยกเลิก. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | หากโหมดห่อเป็นไบนารี, เขียนค่าจำนวนเต็มบวก 8-bit ที่ระบุไปยังสตรีม, หากไม่เป็นไบนารีแปลงเป็นประเภท char_type แล้วเขียนผลลัพธ์ไปยังสตรีม. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Null](../stream/null/) | สตรีมที่ไม่มีที่เก็บพื้นฐาน. |

## การนิยามประเภท

| Typedef | คำอธิบาย |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [BaseIType](./baseitype/) |  |
| [BaseOType](./baseotype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## ดูเพิ่มเติม

* คลาส [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)
* คลาส [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)