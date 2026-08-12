---
title: BasePortionFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คุณสมบัติการจัดรูปแบบส่วนของข้อความทั่วไป.
type: docs
weight: 144
url: /th/aspose.slides/baseportionformat/
---
## BasePortionFormat คลาส


คุณสมบัติการจัดรูปแบบส่วนของข้อความทั่วไป.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ในที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ในที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | คืนค่า Id ของภาษาทางเลือก อ่าน [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | คืนข้อมูลฟอนต์สคริปต์ซับซ้อน ค่า Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | คืนข้อมูลฟอนต์ East Asian ค่า Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | คืนคุณสมบัติ [EffectFormat](../effectformat/) ของข้อความ ไม่ได้สืบทอดใด ๆ อ่านอย่างเดียว [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | คืนข้อความเชิงบนหรือเชิงล่าง ค่าจาก -100% (เชิงล่าง) ถึง 100% (เชิงบน) **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | คืนคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ ไม่ได้สืบทอดใด ๆ อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่ ไม่ได้สืบทอดใด ๆ อ่าน [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | คืนความสูงของแบบอักษรของส่วน **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | กำหนดว่าแบบอักษรเป็นอิตาลิกหรือไม่ ไม่ได้สืบทอดใด ๆ อ่าน [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | คืนประเภทการขีดเส้นใต้ของข้อความ ไม่ได้สืบทอดใด ๆ อ่าน [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | คืนสีที่ใช้ไฮไลท์ข้อความ ไม่ได้สืบทอดใด ๆ อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | กำหนดว่าแบบการขีดเส้นใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ อ่าน [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | กำหนดว่าแบบการขีดเส้นใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ อ่าน [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | คืนขนาดฟอนต์ขั้นต่ำที่ควรเปิดการเคอร์นิง **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | กำหนดว่าตัวเลขควรละเว้นการจัดวางแนวตั้งของข้อความตามภาษาตะวันออกหรือไม่ ไม่ได้สืบทอดใด ๆ อ่าน [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | คืนค่า Id ของภาษาการตรวจสอบ ใช้เพื่อตรวจสอบการสะกดและไวยากรณ์ อ่าน [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | คืนข้อมูลฟอนต์ Latin ค่า Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | คืนคุณสมบัติ [LineFormat](../lineformat/) สำหรับการร่างเส้นรอบข้อความ ไม่ได้สืบทอดใด ๆ อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ได้สืบทอดใด ๆ อ่าน [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | คืนอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | คืน [IPresentationComponent](../ipresentationcomponent/) พาเรนต์ อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่ ไม่ได้สืบทอดใด ๆ อ่าน [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | คืนการเพิ่มระยะห่างระหว่างอักขระ **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | รับค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่... ค่าเริ่มต้นคือ **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | คืนประเภทการขีดฆ่าสำหรับข้อความ ไม่ได้สืบทอดใด ๆ อ่าน [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | คืนข้อมูลฟอนต์สัญลักษณ์ ค่า Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | คืนประเภทการพิมพ์ใหญ่/เล็กของข้อความ ไม่ได้สืบทอดใด ๆ อ่าน [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | คืนคุณสมบัติเส้นขีดเส้นใต้ [FillFormat](../fillformat/) ไม่ได้สืบทอดใด ๆ อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | คืนคุณสมบัติ [LineFormat](../lineformat/) ที่ใช้ร่างเส้นขีดเส้นใต้ ไม่ได้สืบทอดใด ๆ อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมต่อกับอ็อบเจ็กต์. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | คืนค่าแฮชโค้ด. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เทียบเท่าการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเท่าตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานของคำสั่ง lock() ของ C# เพื่อล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท้ากับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | ตั้งค่า Id ของภาษาทางเลือก เขียน [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | ตั้งค่าข้อมูลฟอนต์สคริปต์ซับซ้อน ค่า Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | ตั้งค่าข้อมูลฟอนต์ East Asian ค่า Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | ตั้งค่าข้อความเชิงบนหรือเชิงล่าง ค่าอยู่ระหว่าง -100% (เชิงล่าง) ถึง 100% (เชิงบน) **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | กำหนดว่าฟอนต์เป็นตัวหนาหรือไม่ ไม่ได้สืบทอดใด ๆ เขียน [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | ตั้งค่าความสูงของฟอนต์ของส่วน **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงที่ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | กำหนดว่าแบบอักษรเป็นอิตาลิกหรือไม่ ไม่ได้สืบทอดใด ๆ เขียน [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | ตั้งค่าประเภทการขีดเส้นใต้ของข้อความ ไม่ได้สืบทอดใด ๆ เขียน [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | กำหนดว่าแบบการขีดเส้นใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ เขียน [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | กำหนดว่าแบบการขีดเส้นใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ เขียน [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | ตั้งค่าขนาดฟอนต์ขั้นต่ำที่ควรเปิดการเคอร์นิง **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | กำหนดว่าตัวเลขควรละเว้นการจัดวางแนวตั้งของข้อความตามภาษาตะวันออกหรือไม่ ไม่ได้สืบทอดใด ๆ เขียน [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | ตั้งค่า Id ของภาษาการตรวจสอบ ใช้เพื่อตรวจสอบการสะกดและไวยากรณ์ เขียน [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | ตั้งค่าข้อมูลฟอนต์ Latin ค่า Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ได้สืบทอดใด ๆ เขียน [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่ ไม่ได้สืบทอดใด ๆ เขียน [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | ตั้งค่าการเพิ่มระยะห่างระหว่างอักขระ **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | ตั้งค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งเป็น false การตรวจสอบการสะกดขององค์ประกอบข้อความจะถูกระงับ เมื่อตั้งเป็น true การตรวจสอบการสะกดจะเปิดให้ทำได้ ค่าเริ่มต้นคือ **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | ตั้งค่าประเภทการขีดฆ่าสำหรับข้อความ ไม่ได้สืบทอดใด ๆ เขียน [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | ตั้งค่าข้อมูลฟอนต์สัญลักษณ์ ค่า Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | ตั้งค่าประเภทการพิมพ์ใหญ่/เล็กของข้อความ ไม่ได้สืบทอดใด ๆ เขียน [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอากิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) ให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานของการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานของคำสั่ง lock() ของ C# การปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference ควรไม่เรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference ควรไม่เรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject/)
* คลาส [IBasePortionFormat](../ibaseportionformat/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)