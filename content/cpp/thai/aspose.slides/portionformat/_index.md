---
title: PortionFormat
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบส่วนข้อความ ต่างจาก IPortionFormatEffectiveData คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้
type: docs
weight: 4811
url: /th/aspose.slides/portionformat/
---
## PortionFormat คลาส


คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบส่วนข้อความ ต่างจาก [IPortionFormatEffectiveData](../iportionformateffectivedata/) คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## เมธอด

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนลอยจุดแบบ C# ที่สองค่า NaN ถือเท่ากันแม้ว่าโดยมาตรฐาน IEC 60559:1989 แล้ว NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนลอยจุดแบบ C# ที่สองค่า NaN ถือเท่ากันแม้ว่าโดยมาตรฐาน IEC 60559:1989 แล้ว NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | คืนค่า Id ของภาษาทางเลือก อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | คืนค่าตัวระบุบุ๊กมาร์ค อ่าน [System::String](../../system/string/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | คืนข้อมูลแบบอักษรสคริปต์ซับซ้อน ค่าที่เป็น Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน [IFontData](../ifontdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | คืนข้อมูลแบบอักษรเอเชียตะวันออก ค่าที่เป็น Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน [IFontData](../ifontdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | คืนคุณสมบัติของข้อความ [EffectFormat](../effectformat/) ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | คืนข้อความทั้งหมดหรือยกล่าง ค่าอยู่ระหว่าง -100% (ยกล่าง) ถึง 100% (ยกบน) **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | คืนคุณสมบัติของข้อความ [FillFormat](../fillformat/) ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../nullablebool/) |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | คืนความสูงของแบบอักษรของส่วนหนึ่ง **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน **float** |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../nullablebool/) |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | คืนประเภทการขีดเส้นใต้ของข้อความ ไม่ได้ใช้การสืบทอด อ่าน [TextUnderlineType](../textunderlinetype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | คืนสีที่ใช้ไฮไลท์ข้อความ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [IColorFormat](../icolorformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | ผู้จัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการเลื่อนเมาส์บน อ่าน [IHyperlink](../ihyperlink/) |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ อ่าน [NullableBool](../nullablebool/) |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ อ่าน [NullableBool](../nullablebool/) |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | คืนขนาดแบบอักษรขั้นต่ำที่ควรเปิดการเคอร์นนิง **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน **float** |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | กำหนดว่าตัวเลขควรละเว้นการจัดวางข้อความแนวตั้งที่เป็นลักษณะเฉพาะของภาษาตะวันออกหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../nullablebool/) |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | คืนค่า Id ของภาษาตรวจสอบการพิมพ์ ใช้สำหรับการตรวจสอบการสะกดและไวยากรณ์ อ่าน [System::String](../../system/string/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | คืนข้อมูลแบบอักษรละติน ค่าที่เป็น Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน [IFontData](../ifontdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | คืนคุณสมบัติ [LineFormat](../lineformat/) สำหรับการทำขอบข้อความ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../nullablebool/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | คืนอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว [IDOMObject](../idomobject/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | คืนพาเรนต์ [IPresentationComponent](../ipresentationcomponent/) อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/) |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../nullablebool/) |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | กำหนดว่าตัวแท็กอัจฉริยะควรถูกทำความสะอาดหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน **bool** |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | คืนค่าเพิ่มการเว้นระยะระหว่างตัวอักษร **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน **float** |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | รับค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกละเว้น เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะเปิดให้ทำได้ ค่าเริ่มต้นคือ **false** |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | คืนประเภทการขีดฆ่าของข้อความ ไม่ได้ใช้การสืบทอด อ่าน [TextStrikethroughType](../textstrikethroughtype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | คืนข้อมูลแบบอักษรสัญลักษณ์ ค่าที่เป็น Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน [IFontData](../ifontdata/) |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | คืนประเภทการเปลี่ยนตัวอักษรของข้อความ ไม่ได้ใช้การสืบทอด อ่าน [Slides::TextCapType](../textcaptype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | คืนคุณสมบัติของเส้นขีดเส้นใต้ [FillFormat](../fillformat/) ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | คืนคุณสมบัติ [LineFormat](../lineformat/) ที่ใช้ในการทำขอบเส้นขีดเส้นใต้ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | รับข้อมูลการจัดรูปแบบส่วนที่มีผลรวมการสืบทอด |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | คืนค่ารหัสแฮช |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นการทำงานคล้าย C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นการทำงานคล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นวิธีการคล้าย [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
|  [PortionFormat](./portionformat/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [PortionFormat](./) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | กำหนดค่า Id ของภาษาทางเลือก เขียน [System::String](../../system/string/) |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | กำหนดค่าตัวระบุบุ๊กมาร์ค เขียน [System::String](../../system/string/) |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | กำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน ค่าที่เป็น Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master เขียน [IFontData](../ifontdata/) |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | กำหนดข้อมูลแบบอักษรเอเชียตะวันออก ค่าที่เป็น Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master เขียน [IFontData](../ifontdata/) |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | กำหนดข้อความทั้งหมดหรือยกล่าง ค่าอยู่ระหว่าง -100% (ยกล่าง) ถึง 100% (ยกบน) **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน **float** |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../nullablebool/) |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | กำหนดความสูงของแบบอักษรของส่วนหนึ่ง **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงที่ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน **float** |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../nullablebool/) |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | กำหนดประเภทการขีดเส้นใต้ของข้อความ ไม่ได้ใช้การสืบทอด เขียน [TextUnderlineType](../textunderlinetype/) |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | กำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | กำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการเลื่อนเมาส์บน เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ เขียน [NullableBool](../nullablebool/) |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ เขียน [NullableBool](../nullablebool/) |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | กำหนดขนาดแบบอักษรขั้นต่ำที่ควรเปิดการเคอร์นนิง **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน **float** |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | กำหนดว่าตัวเลขควรละเว้นการจัดวางข้อความแนวตั้งที่เป็นลักษณะเฉพาะของภาษาตะวันออกหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../nullablebool/) |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | กำหนดค่า Id ของภาษาตรวจสอบการพิมพ์ ใช้สำหรับการตรวจสอบการสะกดและไวยากรณ์ เขียน [System::String](../../system/string/) |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | กำหนดข้อมูลแบบอักษรละติน ค่าที่เป็น Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master เขียน [IFontData](../ifontdata/) |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../nullablebool/) |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../nullablebool/) |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | กำหนดว่าตัวแท็กอัจฉริยะควรถูกทำความสะอาดหรือไม่ ไม่ได้ใช้การสืบทอด เขียน **bool** |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | กำหนดค่าเพิ่มการเว้นระยะระหว่างตัวอักษร **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master เขียน **float** |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | กำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกละเว้น เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะเปิดให้ทำได้ ค่าเริ่มต้นคือ **false** |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | กำหนดประเภทการขีดฆ่าของข้อความ ไม่ได้ใช้การสืบทอด เขียน [TextStrikethroughType](../textstrikethroughtype/) |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | กำหนดข้อมูลแบบอักษรสัญลักษณ์ ค่าที่เป็น Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master เขียน [IFontData](../ifontdata/) |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | กำหนดประเภทการเปลี่ยนตัวอักษรของข้อความ ไม่ได้ใช้การสืบทอด เขียน [Slides::TextCapType](../textcaptype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กูเมนต์ที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นวิธีการคล้าย C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง construct ของ C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนของข้อความที่กำหนดสำหรับส่วนที่เฉพาะเจาะจง ซึ่งหมายความว่าเมื่อดึงค่า จะไม่ได้ใช้การสืบทอด ดังนั้นในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง "undefined"

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมการสืบทอด คุณต้องใช้เมธอด [PortionFormat::GetEffective](./geteffective/) ซึ่งคืนอินสแตนซ์ของ [IPortionFormatEffectiveData](../iportionformateffectivedata/)

ตัวอย่างต่อไปนี้จะแสดงวิธีการกำหนดแบบอักษรละตินให้กับส่วนของ [Paragraph](../paragraph/) ใน PowerPoint [Presentation](../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides ใช้ตัวระบุพิเศษเหล่านี้ (คล้ายกับที่ใช้ใน PowerPoint):
// +mn-lt - ฟอนต์ของข้อความหลัก Latin (ฟอนต์ Latin ย่อย)
// +mj-lt -หัวข้อ ฟอนต์ Latin (ฟอนต์ Latin หลัก)
// +mn-ea - ฟอนต์ของข้อความ East Asian (ฟอนต์ East Asian ย่อย)
// +mj-ea - ฟอนต์ของข้อความ East Asian (ฟอนต์ East Asian ย่อย)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## ดูเพิ่มเติม

* คลาส [BasePortionFormat](../baseportionformat/)
* คลาส [IPortionFormat](../iportionformat/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)