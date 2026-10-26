---
title: IPresentationHeaderFooterManager
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงผู้จัดการที่ถือพฤติกรรมของตัวแทนส่วนท้าย, วัน-เวลา และตัวเลขหน้าทั้งหมดของการนำเสนอ.
type: docs
weight: 3407
url: /th/aspose.slides/ipresentationheaderfootermanager/
---
## IPresentationHeaderFooterManager คลาส

แสดงถึงผู้จัดการที่ถือพฤติกรรมของตัวแทนส่วนท้าย, วัน-เวลา และตัวเลขหน้าทั้งหมดของการนำเสนอ.

```cpp
class IPresentationHeaderFooterManager : public virtual Aspose::Slides::IBaseHeaderFooterManager
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดทศนิยมแบบ C#-style ที่ NaN สองค่า ถูกพิจารณาเท่าเทียมกัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าทุกค่า รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดทศนิยมแบบ C#-style ที่ NaN สองค่า ถูกพิจารณาเท่าเทียมกัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าทุกค่า รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชวัตถุที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของวัตถุ. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และอำนวยความสะดวกในการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์การกำหนดค่า. ไม่คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และอำนวยความสะดวกในการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงระหว่างวัตถุประเภทค่าและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) | ตั้งค่าข้อความให้กับตัวแทนวัน-เวลา ทั้งหมด รวมถึงสไลด์มาสเตอร์ สไลด์จัดวาง และสไลด์. |
| virtual void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนวัน-เวลา ทั้งหมด รวมถึงสไลด์มาสเตอร์ สไลด์จัดวาง และสไลด์. |
| virtual void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) | ตั้งค่าข้อความให้กับตัวแทนส่วนท้าย ทั้งหมด รวมถึงสไลด์มาสเตอร์ สไลด์จัดวาง และสไลด์. |
| virtual void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนส่วนท้าย ทั้งหมด รวมถึงสไลด์มาสเตอร์ สไลด์จัดวาง และสไลด์. |
| virtual void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) | ตั้งค่าข้อความให้กับตัวแทนส่วนหัว ทั้งหมด รวมถึงโน้ตมาสเตอร์ โน้ตสไลด์ และมือแจกมาสเตอร์. |
| virtual void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนส่วนหัว ทั้งหมด รวมถึงโน้ตมาสเตอร์ โน้ตสไลด์ และมือแจกมาสเตอร์. |
| virtual void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนเลขหน้า ทั้งหมด รวมถึงสไลด์มาสเตอร์ สไลด์จัดวาง และสไลด์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| virtual void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) | เปลี่ยนการมองเห็นของตัวแทนส่วนท้าย, วัน-เวลา, และเลขหน้า สำหรับสไลด์หัวเรื่องทั้งหมดและสไลด์จัดวางแรก. สไลด์หัวเรื่อง \\u2013 สไลด์ที่อิงจากสไลด์จัดวางแรก (โดยไม่คำนึงถึงประเภทของการจัดวางแรกนี้). |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงที่แชร์และส่งคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงวัตถุที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IBaseHeaderFooterManager](../ibaseheaderfootermanager/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)