---
title: ParagraphFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คลาสนี้บรรจุคุณสมบัติการจัดรูปแบบย่อหน้า ไม่เหมือน IParagraphFormatEffectiveData คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 4668
url: /th/aspose.slides/paragraphformat/
---
## ParagraphFormat คลาส


คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบย่อหน้าต่างๆ. ไม่เหมือนกับ [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## เมธอด

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | คืนค่าการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด. อ่าน [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | คืนขนาดการตั้งแท็บเริ่มต้นโดยไม่มีการสืบทอด. อ่าน **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | กำหนดว่าใช้การตัดบรรทัดแบบเอเชียตะวันออกในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | คืนค่าการจัดตำแหน่งฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. อ่าน [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | กำหนดว่าการใส่เครื่องหมายวรรคตอนห้อยใช้ในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | คืนค่าการเยื้องบรรทัดแรก/เยื้องห้อยของย่อหน้าด้วยการไม่สืบทอด. สามารถกำหนดค่าติดลบได้. อ่าน **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | กำหนดว่าใช้การตัดบรรทัดละตินในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | คืนค่าขอบซ้ายในย่อหน้าด้วยการไม่สืบทอด. อ่าน **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | คืนค่าขอบขวาในย่อหน้าด้วยการไม่สืบทอด. อ่าน **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | คืนอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | คืนผู้ปกครอง [IPresentationComponent](../ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | กำหนดว่าการเขียนจากขวาไปซ้ายใช้ในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | คืนค่าปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. ค่าบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ช่องว่างควรเป็น. ค่าลบระบุขนาดของช่องว่างเป็นจุด. อ่าน **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | คืนค่าปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. ค่าบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ช่องว่างควรเป็น. ค่าลบระบุขนาดของช่องว่างเป็นจุด. อ่าน **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | คืนค่าปริมาณช่องว่างระหว่างบรรทัดฐานในย่อหน้า. ค่าบวกหมายถึงเปอร์เซ็นต์, ค่าลบหมายถึงขนาดเป็นจุด. ไม่ใช้การสืบทอด. อ่าน **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | คืนค่าการตั้งแท็บของย่อหน้าที่ตำแหน่งที่ระบุ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | คืนค่าการตั้งแท็บของย่อหน้า. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | รับข้อมูลการจัดรูปแบบย่อหน้าที่มีผลโดยมีการสืบทอดที่นำมาใช้. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | คืนค่าแฮชโค้ด. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอครายการใด ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่คัดลอครายการใด ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
|  [ParagraphFormat](./paragraphformat/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงออบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | ตั้งค่าการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด. เขียน [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | ตั้งค่าขนาดการตั้งแท็บเริ่มต้นโดยไม่มีการสืบทอด. เขียน **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | กำหนดว่าใช้การตัดบรรทัดแบบเอเชียตะวันออกในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | ตั้งค่าการจัดตำแหน่งฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. เขียน [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | กำหนดว่าการใส่เครื่องหมายวรรคตอนห้อยใช้ในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | ตั้งค่าการเยื้องบรรทัดแรก/เยื้องห้อยของย่อหน้าด้วยการไม่สืบทอด. สามารถกำหนดค่าติดลบได้. เขียน **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | กำหนดว่าใช้การตัดบรรทัดละตินในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | ตั้งค่าขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. เขียน **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | ตั้งค่าขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. เขียน **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | กำหนดว่าการเขียนจากขวาไปซ้ายใช้ในย่อหน้าหรือไม่. ไม่ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | ตั้งค่าปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. ค่าบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ช่องว่างควรเป็น. ค่าลบระบุขนาดของช่องว่างเป็นจุด. เขียน **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | ตั้งค่าปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. ค่าบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ช่องว่างควรเป็น. ค่าลบระบุขนาดของช่องว่างเป็นจุด. เขียน **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | ตั้งค่าปริมาณช่องว่างระหว่างบรรทัดฐานในย่อหน้า. ค่าบวกหมายถึงเปอร์เซ็นต์, ค่าลบหมายถึงขนาดเป็นจุด. ไม่ใช้การสืบทอด. เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่สอดคล้องกับ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ


คลาสนี้ใช้เพื่อรับและจัดการคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดสำหรับย่อหน้าต่างๆ. นั่นหมายความว่าไม่มีการสืบทอดเมื่อดึงค่าจึงในหลายกรณีคุณจะได้รับค่าที่หมายถึง "ไม่ได้กำหนด".

เพื่อรับค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้เมธอด [ParagraphFormat::GetEffective](./geteffective/) ซึ่งคืนค่าอินสแตนซ์ของ [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject/)
* คลาส [IParagraphFormat](../iparagraphformat/)
* คลาส [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)