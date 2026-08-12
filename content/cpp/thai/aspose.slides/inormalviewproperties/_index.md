---
title: INormalViewProperties
second_title: "อ้างอิง API ของ Aspose.Slides สำหรับ C++"
description: "แสดงคุณสมบัติของมุมมองปกติ มุมมองปกติประกอบด้วยพื้นที่เนื้อหา 3 ส่วน: สไลด์เอง, พื้นที่เนื้อหารายข้าง, และพื้นที่เนื้อหาที่ด้านล่าง."
type: docs
weight: 2978
url: /th/aspose.slides/inormalviewproperties/
---
## INormalViewProperties คลาส


Represents normal view properties. The normal view consists of three content regions: the slide itself, a side content region, and a bottom content region.

```cpp
class INormalViewProperties : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaNด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการภายในเท่านั้น. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() | กำหนดสถานะที่แถบแบ่งแนวนอนควรแสดงอยู่ แถบแบ่งแนวนอนจะแยกสไลด์ออกจากบริเวณเนื้อหาที่อยู่ด้านล่างสไลด์. |
| virtual **bool** [get_PreferSingleView](./get_prefersingleview/)() | กำหนดว่าผู้ใช้ต้องการดูบริเวณเนื้อหาเดี่ยวเต็มหน้าต่างหรือไม่ แทนมุมมองปกติแบบมาตรฐานที่มีสามบริเวณเนื้อหา หากเปิดใช้งาน แอปพลิเคชันอาจเลือกแสดงหนึ่งในบริเวณเนื้อหาในหน้าต่างทั้งหมด อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() | องค์ประกอบนี้กำหนดขนาดของบริเวณเนื้อหารายข้างของมุมมองปกติ เมื่อบริเวณนั้นอยู่ในขนาดที่ฟื้นฟูได้ (ไม่ถูกย่อหรือขยาย) อ่านอย่างเดียว [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() | องค์ประกอบนี้กำหนดขนาดของบริเวณสไลด์ด้านบนของมุมมองปกติ เมื่อบริเวณนั้นอยู่ในขนาดที่ฟื้นฟูได้ (ไม่ถูกย่อหรือขยาย) อ่านอย่างเดียว [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() | กำหนดว่าแอปพลิเคชันควรแสดงไอคอนหรือไม่ หากแสดงเนื้อหาโครงร่างในบริเวณเนื้อหาใด ๆ ของโหมดมุมมองปกติ อ่าน **bool**. |
| virtual **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() | กำหนดว่าตัวแยกแนวตั้งควรดึงไปสู่สถานะย่อเมื่อตำแหน่งด้านข้างมีขนาดเล็กพอ อ่าน **bool**. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() | กำหนดสถานะที่แถบแบ่งแนวตั้งควรแสดงอยู่ แถบแบ่งแนวตั้งจะแยกสไลด์ออกจากบริเวณเนื้อหารายข้าง. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนุกรมของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชวัตถุกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงชนิดจริงของวัตถุ เป็นอนุกรมของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่ เป็นอนุกรมของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนุกรมของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และอนุญาตให้คอนสตรัคเตอร์ย่อยทำสำเนา. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และอนุญาตให้คอนสตรัคเตอร์ย่อยทำสำเนา. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | กำหนดสถานะที่แถบแบ่งแนวนอนควรแสดงอยู่ แถบแบ่งแนวนอนจะแยกสไลด์ออกจากบริเวณเนื้อหาที่อยู่ด้านล่างสไลด์. |
| virtual void [set_PreferSingleView](./set_prefersingleview/)(**bool**) | กำหนดว่าผู้ใช้ต้องการดูบริเวณเนื้อหาเดี่ยวเต็มหน้าต่างหรือไม่ แทนมุมมองปกติแบบมาตรฐานที่มีสามบริเวณเนื้อหา หากเปิดใช้งาน แอปพลิเคชันอาจเลือกแสดงหนึ่งในบริเวณเนื้อหาในหน้าต่างทั้งหมด เขียน **bool**. |
| virtual void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) | กำหนดว่าแอปพลิเคชันควรแสดงไอคอนหรือไม่ หากแสดงเนื้อหาโครงร่างในบริเวณเนื้อหาใด ๆ ของโหมดมุมมองปกติ เขียน **bool**. |
| virtual void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) | กำหนดว่าตัวแยกแนวตั้งควรดึงไปสู่สถานะย่อเมื่อตำแหน่งด้านข้างมีขนาดเล็กพอ เขียน **bool**. |
| virtual void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | กำหนดสถานะที่แถบแบ่งแนวตั้งควรแสดงอยู่ แถบแบ่งแนวตั้งจะแยกสไลด์ออกจากบริเวณเนื้อหารายข้าง. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่เป็น shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการนับอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนุกรมของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงวัตถุกำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)