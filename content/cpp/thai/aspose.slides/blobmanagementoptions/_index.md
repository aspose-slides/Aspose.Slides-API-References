---
title: BlobManagementOptions
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เป็นตัวเลือกที่ใช้จัดการกฎการจัดการ BLOB และการตั้งค่า BLOB อื่น ๆ
type: docs
weight: 196
url: /th/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions คลาส

Represents options which can be used to manage BLOB handling rules and other BLOB settings.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | สร้างตัวเลือกการจัดการ BLOB เริ่มต้นใหม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิด C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style โดยที่ NaN สองค่าถือเป็นเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าต่อใดๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style โดยที่ NaN สองค่าถือเป็นเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าต่อใดๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | คุณสมบัตินี้กำหนดว่ามีการสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOBs หรือไม่ ซึ่งช่วยลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOBs ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOBs ทั้งหมดจะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จะใช้กลไกสำรอง (เช่นไฟล์ชั่วคราว) การเก็บ BLOBs ในหน่วยความจำช่วยเพิ่มประสิทธิภาพสูงสุดแต่สามารถทำให้ใช้หน่วยความจำมากเกินไป ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส [Presentation](../presentation/) สามารถเป็นเจ้าของแหล่งที่มา - ไฟล์หรือสตรีม ตลอดอายุของตัวอย่างได้หรือไม่ หากเป็นเจ้าของจะล็อกแหล่งที่มา สิ่งนี้ช่วยปรับการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งที่มา (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ตลอดอายุของตัวอย่าง [Presentation](../presentation/) |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง [System](../../system/) temporary directory จะถูกใช้เป็นค่าเริ่มต้น กระบวนการโฮสต์ควรมีสิทธิ์สร้างไฟล์และโฟลเดอร์ที่นั่น |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเหมือนเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นเหมือนการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นตัวอย่างของประเภทที่อธิบายโดย targetType หรือไม่. เป็นเหมือนออปเจกต์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เหมือนการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคัดลอกประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์การกำหนดค่า. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงออบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | คุณสมบัตินี้กำหนดว่ามีการสร้างไฟล์ชั่วคราวขณะทำงานกับ BLOBs หรือไม่ ซึ่งช่วยลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOBs ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOBs ทั้งหมดจะถูกโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จะใช้กลไกสำรอง (เช่นไฟล์ชั่วคราว) การเก็บ BLOBs ในหน่วยความจำช่วยเพิ่มประสิทธิภาพสูงสุดแต่สามารถทำให้ใช้หน่วยความจำมากเกินไป ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส [Presentation](../presentation/) สามารถเป็นเจ้าของแหล่งที่มา - ไฟล์หรือสตรีม ตลอดอายุของตัวอย่างได้หรือไม่ หากเป็นเจ้าของจะล็อกแหล่งที่มา สิ่งนี้ช่วยปรับการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งที่มา (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ตลอดอายุของตัวอย่าง [Presentation](../presentation/) |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง [System](../../system/) temporary directory จะถูกใช้เป็นค่าเริ่มต้น กระบวนการโฮสต์ควรมีสิทธิ์สร้างไฟล์และโฟลเดอร์ที่นั่น |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอากิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือนการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เหมือนการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IBlobManagementOptions](../iblobmanagementoptions/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)