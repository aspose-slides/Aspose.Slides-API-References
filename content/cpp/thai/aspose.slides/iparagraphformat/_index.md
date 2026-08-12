---
title: IParagraphFormat
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบย่อหน้า. แตกต่างจาก IParagraphFormatEffectiveData, คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 3147
url: /th/aspose.slides/iparagraphformat/
---
## IParagraphFormat คลาส


คลาสนี้มีคุณสมบัติการจัดรูปแบบย่อหน้า. แตกต่างจาก [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

```cpp
class IParagraphFormat : public virtual System::Object
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ไวยากรณ์ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point ในสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมทั้ง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point ในสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมทั้ง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | คืนค่าการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด. อ่าน [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | คืนรูปแบบหัวข้อแบบสัญลักษณ์ของย่อหน้า. อ่านอย่างเดียว [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | คืนรูปแบบส่วนเริ่มต้นของย่อหน้า. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | คืนขนาดการย่อหน้าเริ่มต้นโดยไม่มีการสืบทอด. อ่าน **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | คืนความลึกของย่อหน้า. ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด. อ่าน **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | กำหนดว่าใช้การตัดบรรทัดแบบเอเชียตะวันออกในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | คืนการจัดตำแหน่งฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. อ่าน [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | กำหนดว่าใช้การเว้นเครื่องหมายวรรคตอนแบบห้อยในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | คืนการเยื้องบรรทัดแรก/การเยื้องแบบห้อยของย่อหน้าโดยไม่มีการสืบทอด. การเยื้องแบบห้อยสามารถกำหนดด้วยค่าลบได้. อ่าน **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | กำหนดว่าใช้การตัดบรรทัดแบบลาตินในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | คืนระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. อ่าน **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | คืนระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. อ่าน **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | กำหนดว่าใช้การเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | คืนปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์สำหรับช่องว่างสีขาว. ค่าเป็นลบระบุขนาดของช่องว่างเป็นหน่วยจุด. อ่าน **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | คืนปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์สำหรับช่องว่างสีขาว. ค่าเป็นลบระบุขนาดของช่องว่างเป็นหน่วยจุด. อ่าน **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | คืนปริมาณช่องว่างระหว่างบรรทัดฐานในย่อหน้า. ค่าเป็นบวกหมายถึงเปอร์เซ็นต์, ค่าเป็นลบหมายถึงขนาดเป็นจุด. ไม่ได้ใช้การสืบทอด. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | คืนการเยื้องของย่อหน้าที่ตำแหน่งที่ระบุ. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | คืนการเยื้องหลายตำแหน่งของย่อหน้า. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | รับข้อมูลการจัดรูปแบบย่อหน้าที่มีผลพร้อมการสืบทอดที่นำมาใช้. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นตัวอย่างของประเภทที่อธิบายโดย targetType หรือไม่. เทียบเคียงกับออปเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ออปเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าเคาน์เตอร์อ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | ตั้งค่าการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด. เขียน [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | ตั้งค่าขนาดการเยื้องเริ่มต้นโดยไม่มีการสืบทอด. เขียน **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | ตั้งค่าความลึกของย่อหน้า. ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด. เขียน **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | กำหนดว่าใช้การตัดบรรทัดแบบเอเชียตะวันออกในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | ตั้งค่าการจัดตำแหน่งฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. เขียน [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | กำหนดว่าใช้การเว้นเครื่องหมายวรรคตอนแบบห้อยในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | ตั้งค่าการเยื้องบรรทัดแรก/การเยื้องแบบห้อยของย่อหน้าโดยไม่มีการสืบทอด. การเยื้องแบบห้อยสามารถกำหนดด้วยค่าติดลบได้. เขียน **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | กำหนดว่าใช้การตัดบรรทัดแบบลาตินในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | ตั้งค่าขอบซ้ายของย่อหน้าโดยไม่มีการสืบทอด. เขียน **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | ตั้งค่าขอบขวาของย่อหน้าโดยไม่มีการสืบทอด. เขียน **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | กำหนดว่าใช้การเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่. ไม่ได้ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | ตั้งค่าปริมาณช่องว่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์สำหรับช่องว่างสีขาว. ค่าเป็นลบระบุขนาดของช่องว่างเป็นหน่วยจุด. เขียน **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | ตั้งค่าปริมาณช่องว่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์สำหรับช่องว่างสีขาว. ค่าเป็นลบระบุขนาดของช่องว่างเป็นหน่วยจุด. เขียน **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | ตั้งค่าปริมาณช่องว่างระหว่างบรรทัดฐานในย่อหน้า. ค่าเป็นบวกหมายถึงเปอร์เซ็นต์, ค่าเป็นลบหมายถึงขนาดเป็นจุด. ไม่ได้ใช้การสืบทอด. เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าเคาน์เตอร์อ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าเคาน์เตอร์อ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ


คลาสนี้ใช้เพื่อรับและจัดการคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดไว้สำหรับย่อหน้าเฉพาะ. นั่นหมายความว่าไม่มีการสืบทอดถูกนำมาใช้เมื่อดึงค่าต่าง ๆ ดังนั้นในกรณีส่วนใหญ่คุณจะได้ค่าที่หมายถึง "undefined".

เพื่อรับค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้เมธอด [IParagraphFormat::GetEffective](./geteffective/) ที่คืนอ็อบเจ็กต์ [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)