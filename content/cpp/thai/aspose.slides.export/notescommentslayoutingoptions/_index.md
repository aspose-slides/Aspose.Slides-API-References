---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ให้ตัวเลือกที่ควบคุมลักษณะการจัดรูปแบบของบันทึกย่อและความคิดเห็นในเอกสารที่ส่งออก
type: docs
weight: 560
url: /th/aspose.slides.export/notescommentslayoutingoptions/
---
## NotesCommentsLayoutingOptions คลาส

ให้ตัวเลือกที่ควบคุมลักษณะการจัดรูปแบบของบันทึกย่อและความคิดเห็นในเอกสารที่ส่งออก

```cpp
class NotesCommentsLayoutingOptions : public Aspose::Slides::Export::ISlidesLayoutOptions
```


## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดทศนิยมสไตล์ C# ที่โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใดเลย รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดทศนิยมสไตล์ C# ที่โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใดเลย รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [System::Drawing::Color](../../system.drawing/color/) [get_CommentsAreaColor](./get_commentsareacolor/)() | รับสีของพื้นที่ความคิดเห็น (ใช้ได้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา). |
| **int32_t** [get_CommentsAreaWidth](./get_commentsareawidth/)() | รับความกว้างของพื้นที่แสดงผลความคิดเห็นเป็นพิกเซล (ใช้ได้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา). |
| [CommentsPositions](../commentspositions/) [get_CommentsPosition](./get_commentsposition/)() | รับตำแหน่งของความคิดเห็นบนหน้า. |
| [NotesPositions](../notespositions/) [get_NotesPosition](./get_notesposition/)() | รับตำแหน่งของบันทึกย่อบนหน้า. |
| **bool** [get_ShowCommentsByNoAuthor](./get_showcommentsbynoauthor/)() | รับการมองเห็นของความคิดเห็นที่ไม่มีผู้เขียน หากเป็น true จะทำให้ความคิดเห็นแสดงผล (ใช้ได้เฉพาะเมื่อความคิดเห็นแสดง). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง. |
|  [NotesCommentsLayoutingOptions](./notescommentslayoutingoptions/)() | คอนสตรัคเตอร์เริ่มต้น. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมายค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจกต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมตามค่าที่ระบุ. |
| void [set_CommentsAreaColor](./set_commentsareacolor/)([System::Drawing::Color](../../system.drawing/color/)) | ตั้งสีของพื้นที่ความคิดเห็น (ใช้ได้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา). |
| void [set_CommentsAreaWidth](./set_commentsareawidth/)(**int32_t**) | ตั้งความกว้างของพื้นที่แสดงผลความคิดเห็นเป็นพิกเซล (ใช้ได้เฉพาะเมื่อความคิดเห็นแสดงทางด้านขวา). |
| void [set_CommentsPosition](./set_commentsposition/)([CommentsPositions](../commentspositions/)) | ตั้งตำแหน่งของความคิดเห็นบนหน้า. |
| void [set_NotesPosition](./set_notesposition/)([NotesPositions](../notespositions/)) | ตั้งตำแหน่งของบันทึกย่อบนหน้า. |
| void [set_ShowCommentsByNoAuthor](./set_showcommentsbynoauthor/)(**bool**) | ตั้งการมองเห็นของความคิดเห็นที่ไม่มีผู้เขียน หากเป็น true จะทำให้ความคิดเห็นแสดงผล (ใช้ได้เฉพาะเมื่อความคิดเห็นแสดง). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) ซึ่งช่วยสลับ pointer ในคอนเทนเนอร์ให้เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ISlidesLayoutOptions](../islideslayoutoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* แพคเกจ [Aspose.Slides](../../)