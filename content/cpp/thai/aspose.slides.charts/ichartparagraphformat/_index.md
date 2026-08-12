---
title: IChartParagraphFormat
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงคุณสมบัติการจัดรูปแบบย่อหน้าของแผนภูมิ
type: docs
weight: 781
url: /th/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat คลาส


Represents a paragraph formatting properties of a chart.

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | ส่งคืนการจัดแนวข้อความในย่อหน้า อ่าน [TextAlignment](../../aspose.slides/textalignment/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | ส่งคืนขนาดแท็บเริ่มต้น อ่าน **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | ตรวจสอบว่าใช้การตัดบรรทัดแบบเอเชียตะวันออกในย่อหน้าหรือไม่ อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | ส่งคืนการจัดแนวฟอนต์ในย่อหน้า อ่าน [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | ตรวจสอบว่าใช้เครื่องหมายวรรคตอนแบบห้อยในย่อหน้าหรือไม่ อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | ส่งคืนการเยื้องบรรทัดแรก/เยื้องห้อยของย่อหน้า การเยื้องห้อยสามารถกำหนดเป็นค่าลบได้ อ่าน **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | ตรวจสอบว่าใช้การตัดบรรทัดแบบละตินในย่อหน้าหรือไม่ อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | ส่งคืนระยะขอบซ้ายในย่อหน้า อ่าน **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | ส่งคืนระยะขอบขวาในย่อหน้า อ่าน **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | ตรวจสอบว่าใช้การเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่ อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | ส่งคืนปริมาณพื้นที่หลังบรรทัดสุดท้ายในย่อหน้า อ่าน **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | ส่งคืนปริมาณพื้นที่ก่อนบรรทัดแรกในย่อหน้า อ่าน **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | ส่งคืนปริมาณพื้นที่ระหว่างบรรทัดฐานในย่อหน้า อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | ส่งคืนการเยื้องของย่อหน้าที่ตำแหน่งกำหนด อ่านอย่างเดียว [Aspose::Slides::ITab](../../aspose.slides/itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | ส่งคืนการเยื้องของย่อหน้า อ่านอย่างเดียว [ITabCollection](../../aspose.slides/itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ช่วยให้ทำแฮชอ็อบเจกต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับการล็อค เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ช่วยให้ทำการโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงร่วมลงตามค่าที่ระบุ |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | ตั้งค่าการจัดแนวข้อความในย่อนหน้า เขียน [TextAlignment](../../aspose.slides/textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | ตั้งค่าขนาดแท็บเริ่มต้น เขียน **float**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | ตรวจสอบว่าใช้การตัดบรรทัดแบบเอเชียตะวันออกในย่อหน้าหรือ não? เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | ตั้งค่าการจัดแนวฟอนต์ในย่อหน้า เขียน [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | ตรวจสอบว่าใช้เครื่องหมายวรรคตอนแบบห้อยในย่อหน้าหรือไม่ เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | ตั้งค่าการเยื้องบรรทัดแรก/เยื้องห้อยของย่อหน้า การเยื้องห้อยสามารถกำหนดเป็นค่าลบได้ เขียน **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | ตรวจสอบว่าใช้การตัดบรรทัดแบบละตินในย่อหน้าหรือไม่ เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | ตั้งค่าระยะขอบซ้ายในย่อหน้า เขียน **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | ตั้งค่าระยะขอบขวาในย่อหน้า เขียน **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | ตรวจสอบว่าใช้การเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่ เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | ตั้งค่าปริมาณพื้นที่หลังบรรทัดสุดท้ายในย่อหน้า เขียน **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | ตั้งค่าปริมาณพื้นที่ก่อนบรรทัดแรกในย่อหน้า เขียน **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | ตั้งค่าปริมาณพื้นที่ระหว่างบรรทัดฐานในย่อหน้า เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ช่วยให้แปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับการปลดล็อค เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)