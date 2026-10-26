---
title: IBlobManagementOptions
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: Binary Large Object (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นเอกเทศหนึ่งหน่วย - คือ BLOB สามารถเป็นไฟล์เสียง, วิดีโอ หรือการนำเสนอเองได้ มีเทคนิคหลายอย่างที่ใช้เพื่อเพิ่มประสิทธิภาพการใช้หน่วยความจำขณะทำงานกับ BLOBs - ซึ่งอาจถูกจัดเก็บไว้แล้วในงานนำเสนอหรือจะถูกเพิ่มเข้ามาในภายหลังโดยโปรแกรม การใช้ IBlobManagementOptions คุณสามารถเปลี่ยนแปลงแง่มุมการทำงานต่าง ๆ ที่เกี่ยวกับการจัดการ BLOBs สำหรับอายุการใช้งานของอินสแตนซ์ IPresentation
type: docs
weight: 1535
url: /th/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions คลาส


BLOB (Binary Large Object) คือข้อมูลไบนารีที่จัดเก็บเป็นเอกเทศหนึ่งหน่วย - คือ BLOB สามารถเป็นไฟล์เสียง, วิดีโอ หรือการนำเสนอเองได้ มีเทคนิคหลายอย่างที่ใช้เพื่อเพิ่มประสิทธิภาพการใช้หน่วยความจำขณะทำงานกับ BLOBs - ซึ่งอาจถูกจัดเก็บไว้แล้วในงานนำเสนอหรือจะถูกเพิ่มเข้ามาในภายหลังโดยโปรแกรม การใช้ [IBlobManagementOptions](./) คุณสามารถเปลี่ยนแปลงแง่มุมการทำงานต่าง ๆ ที่เกี่ยวกับการจัดการ BLOBs สำหรับอายุการใช้งานของอินสแตนซ์ [IPresentation](../ipresentation/)

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ค่า NaN สองค่าถูกพิจารณาเท่าเทียมกัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ค่า NaN สองค่าถูกพิจารณาเท่าเทียมกัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | คุณสมบัตินี้กำหนดว่ามีการสร้างไฟล์ชั่วคราวได้หรือไม่ขณะทำงานกับ BLOBs ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | คุณสมบัตินี้กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOB ทั้งหมดจะโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จะใช้กลไกอื่น (เช่นไฟล์ชั่วคราว) การเก็บ BLOB ในหน่วยความจำทำให้ประสิทธิภาพสูงสุดแต่สามารถทำให้การใช้หน่วยความจำสูง ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส [Presentation](../presentation/) สามารถเป็นเจ้าของแหล่งที่มาของไฟล์หรือสตรีมระหว่างอายุการใช้งานของอินสแตนซ์หรือไม่ หากอินสแตนซ์เป็นเจ้าของจะล็อกแหล่งที่มา ซึ่งช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งที่มา (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ระหว่างอายุการใช้งานของ [Presentation](../presentation/) นี้ ตัวอย่างเช่น: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง [System](../../system/) ไดเรกทอรีชั่วคราวจะถูกใช้เป็นค่าเริ่มต้น กระบวนการโฮสต์ควรมีสิทธิ์สร้างไฟล์และโฟลเดอร์ที่นั่น |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เหมือนคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และอนุญาตให้คัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และอนุญาตให้คัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าเคาน์เตอร์อ้างอิงร่วมโดยค่าที่ระบุ |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | คุณสมบัตินี้กำหนดว่ามีการสร้างไฟล์ชั่วคราวได้หรือไม่ขณะทำงานกับ BLOBs ซึ่งจะลดการใช้หน่วยความจำอย่างมากแต่ต้องการสิทธิ์ในการสร้างไฟล์ |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | คุณสมบัตินี้กำหนดขนาดสูงสุดรวม (เป็นไบต์) ที่ BLOB ทั้งหมดอาจใช้ในหน่วยความจำ โดยค่าเริ่มต้น BLOB ทั้งหมดจะโหลดเข้าสู่หน่วยความจำ; เมื่อถึงขีดจำกัดนี้จะใช้กลไกอื่น (เช่นไฟล์ชั่วคราว) การเก็บ BLOB ในหน่วยความจำทำให้ประสิทธิภาพสูงสุดแต่สามารถทำให้การใช้หน่วยความจำสูง ใช้คุณสมบัตินี้เพื่อปรับพฤติกรรมให้เหมาะกับสภาพแวดล้อมหรือความต้องการของคุณ |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส [Presentation](../presentation/) สามารถเป็นเจ้าของแหล่งที่มาของไฟล์หรือสตรีมระหว่างอายุการใช้งานของอินสแตนซ์หรือไม่ หากอินสแตนซ์เป็นเจ้าของจะล็อกแหล่งที่มา ซึ่งช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งที่มา (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ระหว่างอายุการใช้งานของ [Presentation](../presentation/) นี้ ตัวอย่างเช่น: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | เส้นทางรากที่ไฟล์ชั่วคราวจะถูกสร้าง [System](../../system/) ไดเรกทอรีชั่วคราวจะถูกใช้เป็นค่าเริ่มต้น กระบวนการโฮสต์ควรมีสิทธิ์สร้างไฟล์และโฟลเดอร์ที่นั่น |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนท์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) อนุญาตการสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงร่วม ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าเคาน์เตอร์อ้างอิงร่วม ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือนการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เหมือนคำสั่ง lock() ของ C# ในการปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าเคาน์เตอร์อ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)