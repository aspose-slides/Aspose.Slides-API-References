---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อินเทอร์เฟซฐานสำหรับอ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงได้ซึ่งประกอบด้วยคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผล
type: docs
weight: 1470
url: /th/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData คลาส

อินเทอร์เฟซฐานสำหรับอ็อบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ที่มีคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผล

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบจุดลอยของ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบจุดลอยของ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | ส่งคืน Id ของภาษาตัวเลือกอื่น. อ่านอย่างเดียว [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | ส่งคืนข้อมูลแบบอักษรสคริปต์ซับซ้อน. อ่านอย่างเดียว [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | ส่งคืนข้อมูลแบบอักษรเอเชียตะวันออก. อ่านอย่างเดียว [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | ส่งคืนคุณสมบัติ [EffectFormat](../effectformat/) ของข้อความ. อ่านอย่างเดียว [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](./get_escapement/)() | ส่งคืนข้อความ superscript หรือ subscript. ค่าอยู่ระหว่าง -100% (subscript) ถึง 100% (superscript). อ่านอย่างเดียว **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | ส่งคืนคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ. อ่านอย่างเดียว [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](./get_fontbold/)() | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **float** [get_FontHeight](./get_fontheight/)() | ส่งคืนความสูงของแบบอักษรของส่วนข้อความ, เป็นหน่วย point. อ่านอย่างเดียว **float**. |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | ส่งคืนประเภทการขีดใต้ของข้อความ. อ่านอย่างเดียว [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | ส่งคืนสีที่ใช้ไฮไลท์ข้อความ. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | กำหนดว่ารูปแบบการขีดใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | กำหนดว่ารูปแบบการขีดใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ. อ่านอย่างเดียว **bool**. |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | ส่งคืนขนาดแบบอักษรขั้นต่ำที่ควรเปิดการ kernning. อ่านอย่างเดียว **float**. |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | กำหนดว่าตัวเลขควรละเว้นการจัดวางแนวตั้งที่เฉพาะเจาะจงตามภาษาเอเชียตะวันออกของข้อความหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | ส่งคืน Id ของภาษาหนึ่ง. อ่านอย่างเดียว [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | ส่งคืนข้อมูลแบบอักษร Latin. อ่านอย่างเดียว [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | ส่งคืนคุณสมบัติ [LineFormat](../lineformat/) สำหรับการขอบข้อความ. อ่านอย่างเดียว [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | กำหนดว่าข้อความไม่ควรตรวจสอบการสะกดหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | กำหนดว่า smart tag ควรทำความสะอาดหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **float** [get_Spacing](./get_spacing/)() | ส่งคืนการเพิ่มช่องว่างระหว่างตัวอักษร, หน่วย point. อ่านอย่างเดียว **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | ส่งคืนประเภทการขีดเส้นกลางของข้อความ. อ่านอย่างเดียว [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | ส่งคืนข้อมูลแบบอักษรสัญลักษณ์. อ่านอย่างเดียว [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | ส่งคืนประเภทของการเปลี่ยนตัวอักษรของข้อความ. อ่านอย่างเดียว [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | ส่งคืนคุณสมบัติ [FillFormat](../fillformat/) ของเส้นขีดใต้. อ่านอย่างเดียว [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | ส่งคืนคุณสมบัติ [LineFormat](../lineformat/) ที่ใช้ขอบเส้นขีดใต้. อ่านอย่างเดียว [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อเนกลักษณ์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการสร้างแฮชของอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. อเนกลักษณ์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. อเนกลักษณ์ของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตาม statement lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อเนกลักษณ์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทแบบกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เฉพาะทางของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เฉพาะทางของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนการเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อเนกลักษณ์ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตาม statement lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยทุกโครงสร้างข้อมูลภายใน. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)