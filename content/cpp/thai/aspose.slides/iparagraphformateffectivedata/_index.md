---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: อ็อบเจ็กต์ไม่เปลี่ยนแปลงซึ่งประกอบด้วยคุณสมบัติการจัดรูปแบบย่อหน้าอย่างมีประสิทธิภาพ.
type: docs
weight: 3160
url: /th/aspose.slides/iparagraphformateffectivedata/
---
## IParagraphFormatEffectiveData คลาส

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งประกอบด้วยคุณสมบัติการจัดรูปแบบย่อหน้าอย่างมีประสิทธิภาพ.

```cpp
class IParagraphFormatEffectiveData : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบ floating point แบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบ floating point แบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | ส่งคืนการจัดตำแหน่งข้อความในย่อหน้า. อ่านอย่างเดียว [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [get_Bullet](./get_bullet/)() | ส่งคืนรูปแบบ bullet ของย่อหน้า. อ่านอย่างเดียว [IBulletFormatEffectiveData](../ibulletformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | ส่งคืนรูปแบบส่วนเริ่มต้นของย่อหน้า. อ่านอย่างเดียว [IPortionFormatEffectiveData](../iportionformateffectivedata/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | ส่งคืนขนาดแท็บค่าเริ่มต้น. อ่านอย่างเดียว **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | ส่งคืนความลึกของย่อหน้า. อ่านอย่างเดียว **int16_t**. |
| virtual **bool** [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | กำหนดว่ามีการใช้การตัดบรรทัดเอเชียตะวันออกในย่อหน้าหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | ส่งคืนการจัดตำแหน่งฟอนต์ในย่อหน้า. อ่านอย่างเดียว [Slides::FontAlignment](../fontalignment/). |
| virtual **bool** [get_HangingPunctuation](./get_hangingpunctuation/)() | กำหนดว่ามีการใช้เครื่องหมายวรรคตอนแบบ hanging ในย่อหน้าหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **float** [get_Indent](./get_indent/)() | ส่งคืนการเยื้องบรรทัดแรก/เยื้องแบบ hanging ของย่อหน้า. สามารถกำหนดเยื้องแบบ hanging ด้วยค่าลบ. อ่านอย่างเดียว **float**. |
| virtual **bool** [get_LatinLineBreak](./get_latinlinebreak/)() | กำหนดว่ามีการใช้การตัดบรรทัดละตินในย่อหน้าหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | ส่งคืนระยะขอบซ้ายของย่อหน้า. อ่านอย่างเดียว **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | ส่งคืนระยะขอบขวาของย่อหน้า. อ่านอย่างเดียว **float**. |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | กำหนดว่ามีการใช้การเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | ส่งคืนปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้า. อ่านอย่างเดียว **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | ส่งคืนปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้า. อ่านอย่างเดียว **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | ส่งคืนปริมาณช่องว่างระหว่างบรรทัดฐานในย่อหน้า. อ่านอย่างเดียว **float**. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITabEffectiveData](../itabeffectivedata/)\>\> [get_Tabs](./get_tabs/)() | ส่งคืนการแท็บของย่อหน้า. อ่านอย่างเดียว [ITabEffectiveData](../itabeffectivedata/)[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นสอดคล้องกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ช่วยให้ทำแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นสอดคล้องกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นสอดคล้องกับโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นสอดคล้องกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ช่วยให้ทำการโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่จะแชร์). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นสอดคล้องกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ช่วยให้แปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IParagraphFormat](../iparagraphformat/) เพื่อส่งค่าการจัดรูปแบบที่มีประสิทธิภาพพร้อมการสืบทอดที่ใช้.

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)