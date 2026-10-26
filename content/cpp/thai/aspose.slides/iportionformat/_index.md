---
title: IPortionFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของข้อความทั้งหมด. แตกต่างจาก IPortionFormatEffectiveData, คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 3329
url: /th/aspose.slides/iportionformat/
---
## IPortionFormat คลาส


คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของข้อความทั้งหมด. แตกต่างจาก [IPortionFormatEffectiveData](../iportionformateffectivedata/), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | เลียนแบบการเปรียบเทียบค่าลอยตัวแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | เลียนแบบการเปรียบเทียบค่าลอยตัวแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | คืนค่า Id ของภาษาทางเลือก. อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | คืนค่าตัวระบุบุ๊กมาร์ก. อ่าน [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | คืนข้อมูลแบบอักษรสคริปต์ซับซ้อน. ค่า Null หมายความว่าแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | คืนข้อมูลแบบอักษร East Asian. ค่า Null หมายความว่าแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | คืนคุณสมบัติ [EffectFormat](../effectformat/) ของข้อความ. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | คืนข้อความซุปเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซุปเปอร์สคริปต์). **std::numeric_limits<float>::quiet_NaN()** หมายความว่าค่าไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | คืนคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | คืนความสูงของแบบอักษรของส่วน. **std::numeric_limits<float>::quiet_NaN()** หมายความว่าความสูงไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | คืนประเภทการขีดเส้นใต้ของข้อความ. ไม่ได้ใช้การสืบทอด. อ่าน [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | คืนสีที่ใช้ไฮไลท์ข้อความ. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ตัวจัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์อยู่เหนือ. อ่าน [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ. อ่าน [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ. อ่าน [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | คืนขนาดแบบอักษรขั้นต่ำที่ควรเปิด kerning. **std::numeric_limits<float>::quiet_NaN()** หมายความว่าค่าไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | กำหนดว่าต้องละเลยการจัดเลย์เอาต์แนวตั้งของข้อความภาษาตะวันออกหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | คืน Id ของภาษาตรวจสอบ. ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์. อ่าน [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | คืนข้อมูลแบบอักษร Latin. ค่า Null หมายความว่าแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | คืนคุณสมบัติ [LineFormat](../lineformat/) สำหรับการรอบร่างข้อความ. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | กำหนดว่าข้อความไม่ควรผ่านการตรวจสอบหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | กำหนดว่าต้องทำความสะอาด smart tag หรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | คืนการเพิ่มระยะห่างระหว่างอักขระ. **std::numeric_limits<float>::quiet_NaN()** หมายความว่าค่าไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | รับค่าบ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. เมื่อกำหนดเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกยับยั้ง. เมื่อกำหนดเป็น true การตรวจสอบการสะกดจะอนุญาต. ค่าเริ่มต้นคือ **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | คืนประเภทการขีดเส้นผ่านของข้อความ. ไม่ได้ใช้การสืบทอด. อ่าน [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | คืนข้อมูลแบบอักษรสัญลักษณ์. ค่า Null หมายความว่าแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | คืนประเภทของการพิมพ์ใหญ่/เล็กของข้อความ. ไม่ได้ใช้การสืบทอด. อ่าน [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | คืนคุณสมบัติของเส้นขีดใต้ [FillFormat](../fillformat/). ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | คืนคุณสมบัติ [LineFormat](../lineformat/) ที่ใช้รอบร่างเส้นขีดใต้. ไม่ได้ใช้การสืบทอด. อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | รับข้อมูลการจัดรูปแบบส่วนที่มีผลรวมกับการสืบทอด. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกคณิตของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกคณิตของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอเนกคณิตของโอเปอเรเตอร์ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกคณิตของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่ทำร่วมกันตามค่าที่ระบุ. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | ตั้งค่า Id ของภาษาทางเลือก. เขียน [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | ตั้งค่าตัวระบุบุ๊กมาร์ก. เขียน [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ตั้งค่าข้อมูลแบบอักษรสคริปต์ซับซ้อน. ค่า Null หมายความว่าแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. เขียน [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ตั้งค่าข้อมูลแบบอักษร East Asian. ค่า Null หมายความว่าแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. เขียน [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | ตั้งค่าข้อความซุปเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซุปเปอร์สคริปต์). **std::numeric_limits<float>::quiet_NaN()** หมายความว่าค่าไม่มีการกำหนดและควรสืบทอดจาก Master. เขียน **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่ได้ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | ตั้งค่าความสูงของแบบอักษรส่วน. **std::numeric_limits<float>::quiet_NaN()** หมายความว่าความสูงไม่มีการกำหนดและควรสืบทอดจาก Master. เขียน **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่. ไม่ได้ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | ตั้งค่าประเภทการขีดเส้นใต้ของข้อความ. ไม่ได้ใช้การสืบทอด. เขียน [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่าฮัยเปอร์ลิงก์ที่กำหนดสำหรับคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่าฮัยเปอร์ลิงก์ที่กำหนดสำหรับเมาส์อยู่เหนือ. เขียน [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | ตั้งค่าขนาดแบบอักษรขั้นต่ำที่ควรเปิด kerning. **std::numeric_limits<float>::quiet_NaN()** หมายความว่าค่าไม่มีการกำหนดและควรสืบทอดจาก Master. เขียน **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | กำหนดว่าตัวเลขควรละเลยการจัดเลย์เอาต์แนวตั้งของข้อความภาษาตะวันออกหรือไม่. ไม่ได้ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | ตั้งค่า Id ของภาษาตรวจสอบ. ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์. เขียน [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ตั้งค่าข้อมูลแบบอักษร Latin. ค่า Null หมายความว่าแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. เขียน [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่ได้ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | กำหนดว่าข้อความไม่ควรผ่านการตรวจสอบหรือไม่. ไม่ได้ใช้การสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | กำหนดว่าต้องทำความสะอาด smart tag หรือไม่. ไม่ได้ใช้การสืบทอด. เขียน **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | ตั้งค่าการเพิ่มระยะห่างระหว่างอักขระ. **std::numeric_limits<float>::quiet_NaN()** หมายความว่าค่าไม่มีการกำหนดและควรสืบทอดจาก Master. เขียน **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | ตั้งค่าค่าที่บ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. เมื่อกำหนดเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกยับยั้ง. เมื่อกำหนดเป็น true การตรวจสอบการสะกดจะอนุญาต. ค่าเริ่มต้นคือ **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | ตั้งค่าประเภทการขีดเส้นผ่านของข้อความ. ไม่ได้ใช้การสืบทอด. เขียน [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ตั้งค่าข้อมูลแบบอักษรสัญลักษณ์. ค่า Null หมายความว่าแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. เขียน [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | ตั้งค่าประเภทของการพิมพ์ใหญ่/เล็กของข้อความ. ไม่ได้ใช้การสืบทอด. เขียน [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ทำร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่ทำร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ทำร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกคณิตของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## หมายเหตุ


คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนของข้อความที่กำหนดสำหรับส่วนเฉพาะ. ซึ่งหมายความว่าไม่มีการสืบทอดค่าเมื่อดึงค่า ดังนั้นในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง "undefined".

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้เมธอด [IPortionFormat::GetEffective](./geteffective/) ซึ่งจะคืนค่าอินสแตนซ์ของ [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## ดูเพิ่มเติม

* คลาส [IBasePortionFormat](../ibaseportionformat/)
* คลาส [IHyperlinkContainer](../ihyperlinkcontainer/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)