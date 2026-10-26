---
title: RNGCryptoServiceProvider
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "ตัวสร้างตัวเลขสุ่มที่สอดคล้องกับแนวคิด CSP. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอากรูเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 443
url: /th/system.security.cryptography/rngcryptoserviceprovider/
---
## RNGCryptoServiceProvider คลาส


ตัวสร้างตัวเลขสุ่มที่สอดคล้องกับแนวคิด CSP. วัตถุของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแต็คหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดช่วงเวลาการทำงานและ/หรือการตรวจสอบความถูกต้อง. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอากรูเมนต์ให้กับฟังก์ชัน.

```cpp
class RNGCryptoServiceProvider : public System::Security::Cryptography::RandomNumberGenerator
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [System::SharedPtr](../../system/sharedptr/)\<[RandomNumberGenerator](../randomnumbergenerator/)\> [Create](../randomnumbergenerator/create/)() | สร้างอินสแตนซ์ของการทำงานเริ่มต้นของตัวสร้างตัวเลขสุ่มเชิงเข้ารหัสที่สามารถใช้เพื่อสร้างข้อมูลสุ่มได้. ยังไม่ได้ทำการดำเนินการ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงแบบสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าแบบสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขแบบจุดลอยของ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบจุดลอยของ C# สำหรับ double ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| void [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | เติมองค์ประกอบของอาเรย์ที่มีอยู่ด้วยไบต์สุ่ม. |
| void [GetBytes](./getbytes/)(System::Details::ArrayView\<**uint8_t**\>) override | เติมองค์ประกอบของวิวอาเรย์ที่มีอยู่ด้วยไบต์สุ่ม. |
| virtual void [GetBytes](../randomnumbergenerator/getbytes/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | เติมส่วนของอาเรย์ที่มีอยู่ด้วยไบต์สุ่ม. |
| virtual void [GetBytes](../randomnumbergenerator/getbytes/)(System::Details::ArrayView\<**uint8_t**\>, int, int) | เติมส่วนของวิวอาเรย์ที่มีอยู่ด้วยไบต์สุ่ม. |
| void [GetBytes](../randomnumbergenerator/getbytes/)(System::Details::StackArray\<**uint8_t**, N\>\&) | เติมองค์ประกอบของสแตกอาเรย์ที่มีอยู่ด้วยไบต์สุ่ม. |
| void [GetBytes](../randomnumbergenerator/getbytes/)(System::Details::StackArray\<**uint8_t**, N\>\&, int, int) | เติมส่วนของสแตกอาเรย์ที่มีอยู่ด้วยไบต์สุ่ม. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่สัมพันธ์กับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานแบบเดียวกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ช่วยให้ทำแฮชของวัตถุที่กำหนดเองได้. |
| void [GetNonZeroBytes](./getnonzerobytes/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | เติมองค์ประกอบของอาเรย์ที่มีอยู่ด้วยไบต์สุ่มที่ไม่เป็นศูนย์. |
| void [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<**uint8_t**\>) override | เติมองค์ประกอบของวิวอาเรย์ที่มีอยู่ด้วยไบต์สุ่มที่ไม่เป็นศูนย์. |
| void [GetNonZeroBytes](../randomnumbergenerator/getnonzerobytes/)(System::Details::StackArray\<**uint8_t**, N\>\&) | เติมองค์ประกอบของสแตกอาเรย์ที่มีอยู่ด้วยไบต์สุ่มที่ไม่เป็นศูนย์. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นการทำงานแบบเดียวกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานแบบเดียวกับโอเปอเรเตอร์ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการทำงานแบบเดียวกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ช่วยให้ทำการโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกสิ่งใดเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดการสร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกสิ่งใดเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดการสร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์โดยค่าที่ระบุ. |
|  [RNGCryptoServiceProvider](./rngcryptoserviceprovider/)() | คอนสตรัคเตอร์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าจำนวนการอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการทำงานแบบเดียวกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ช่วยให้แปลงวัตถุที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
| virtual  [~RNGCryptoServiceProvider](./~rngcryptoserviceprovider/)() | ดีสตรักเตอร์. |
## ดูเพิ่มเติม

* คลาส [RandomNumberGenerator](../randomnumbergenerator/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)