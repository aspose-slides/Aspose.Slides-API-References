---
title: ILayoutPlaceholderManager
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงตัวจัดการที่ให้คุณเพิ่มตัวตำแหน่งแทรกลงในสไลด์เค้าโครง.
type: docs
weight: 2627
url: /th/aspose.slides/ilayoutplaceholdermanager/
---
## ILayoutPlaceholderManager class

Represents manager that allows you to add placeholders to the layout slide.

```cpp
class ILayoutPlaceholderManager : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddChartPlaceholder](./addchartplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บแผนภูมิ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddContentPlaceholder](./addcontentplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ, ตาราง, สื่อ หรือข้อความ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddMediaPlaceholder](./addmediaplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บวัตถุสื่อ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddOnlineImagePlaceholder](./addonlineimageplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บภาพออนไลน์. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddPicturePlaceholder](./addpictureplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บรูปภาพ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddSmartArtPlaceholder](./addsmartartplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บ [SmartArt](../../aspose.slides.smartart/) ไดอะแกรม. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTablePlaceholder](./addtableplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บตาราง. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTextPlaceholder](./addtextplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalContentPlaceholder](./addverticalcontentplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บเนื้อหา เช่น รูปภาพ, ตาราง, สื่อ หรือข้อความในแนวตั้ง. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalTextPlaceholder](./addverticaltextplaceholder/)(**float**, **float**, **float**, **float**) | เพิ่มรูปทรง placeholder ใหม่ไปยังสไลด์เค้าโครงเพื่อเก็บเนื้อหาข้อความในแนวตั้ง. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C#-style ที่ NaN สองค่า ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C#-style ที่ NaN สองค่า ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การมอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะแชร์). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)