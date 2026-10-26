---
title: IChartPortionFormat
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นตัวแทนของคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ
type: docs
weight: 807
url: /th/aspose.slides.charts/ichartportionformat/
---
## IChartPortionFormat คลาส

แทนค่าคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ

```cpp
class IChartPortionFormat : public virtual Aspose::Slides::IBasePortionFormat
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style ที่ NaN สองค่าเทียบเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style ที่ NaN สองค่าเทียบเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อใช้ภายในเท่านั้น. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/get_alternativelanguageid/)() | คืนค่า Id ของภาษาทดแทน อ่าน [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/ibaseportionformat/get_complexscriptfont/)() | คืนข้อมูลฟอนต์สคริปต์ซับซ้อน ค่า Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ อ่าน [IFontData](../../aspose.slides/ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/ibaseportionformat/get_eastasianfont/)() | คืนข้อมูลฟอนต์เอเชียตะวันออก ค่า Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ อ่าน [IFontData](../../aspose.slides/ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ibaseportionformat/get_effectformat/)() | คืนคุณสมบัติของข้อความ [EffectFormat](../../aspose.slides/effectformat/) ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual **float** [get_Escapement](../../aspose.slides/ibaseportionformat/get_escapement/)() | คืนข้อความซุปเปอร์สคริปต์หรือซับสคริปต์ ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซุปเปอร์สคริปต์) **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ibaseportionformat/get_fillformat/)() | คืนคุณสมบัติของข้อความ [FillFormat](../../aspose.slides/fillformat/) ไม่ได้ใช้การสืบทอดอ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/ibaseportionformat/get_fontbold/)() | กำหนดว่าฟอนต์เป็นตัวหนาหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_FontHeight](../../aspose.slides/ibaseportionformat/get_fontheight/)() | คืนความสูงของฟอนต์ของส่วนหนึ่ง **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ อ่าน **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/ibaseportionformat/get_fontitalic/)() | กำหนดว่าฟอนต์เป็นตัวเอนหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/ibaseportionformat/get_fontunderline/)() | คืนประเภทขีดเส้นใต้ของข้อความ ไม่ได้ใช้การสืบทอด อ่าน [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/ibaseportionformat/get_highlightcolor/)() | คืนสีที่ใช้ทำไฮไลท์ข้อความ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/get_ishardunderlinefill/)() | กำหนดว่าสไตล์ขีดเส้นใต้มีคุณสมบัติ [FillFormat](../../aspose.slides/fillformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../../aspose.slides/fillformat/) ของข้อความ อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/get_ishardunderlineline/)() | กำหนดว่าสไตล์ขีดเส้นใต้มีคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ของข้อความ อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../../aspose.slides/ibaseportionformat/get_kerningminimalsize/)() | คืนขนาดฟอนต์ขั้นต่ำที่ควรเปิดการเคอร์นนิง **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ อ่าน **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/ibaseportionformat/get_kumimoji/)() | กำหนดว่าตัวเลขควรละเว้นการจัดแนวข้อความแบบแนวตั้งตามภาษาตะวันออกหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/ibaseportionformat/get_languageid/)() | คืนค่า Id ของภาษาตรวจสอบการพิมพ์ ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์ อ่าน [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/ibaseportionformat/get_latinfont/)() | คืนข้อมูลฟอนต์ละติน ค่า Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ อ่าน [IFontData](../../aspose.slides/ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ibaseportionformat/get_lineformat/)() | คืนคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) สำหรับการขอบข้อความ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/ibaseportionformat/get_normaliseheight/)() | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/ibaseportionformat/get_proofdisabled/)() | กำหนดว่าข้อความไม่ควรตรวจสอบการพิมพ์หรือไม่ ไม่ได้ใช้การสืบทอดอ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_Spacing](../../aspose.slides/ibaseportionformat/get_spacing/)() | คืนการเพิ่มระยะห่างระหว่างตัวอักษร **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ อ่าน **float**. |
| virtual **bool** [get_SpellCheck](../../aspose.slides/ibaseportionformat/get_spellcheck/)() | รับค่าสบ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกละเว้น เมื่อตั้งเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าเริ่มต้นคือ **false**. |
| virtual [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/ibaseportionformat/get_strikethroughtype/)() | คืนประเภทขีดฆ่าของข้อความ ไม่ได้ใช้การสืบทอด อ่าน [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/ibaseportionformat/get_symbolfont/)() | คืนข้อมูลฟอนต์สัญลักษณ์ ค่า Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ อ่าน [IFontData](../../aspose.slides/ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/ibaseportionformat/get_textcaptype/)() | คืนประเภทของการใช้ตัวอักษรใหญ่-เล็กของข้อความ ไม่ได้ใช้การสืบทอดอ่าน [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/ibaseportionformat/get_underlinefillformat/)() | คืนคุณสมบัติของเส้นขีดเส้นใต้ [FillFormat](../../aspose.slides/fillformat/) ไม่ได้ใช้การสืบทอดอ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/ibaseportionformat/get_underlinelineformat/)() | คืนคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ที่ใช้ขอบเส้นขีดเส้นใต้ ไม่ได้ใช้การสืบทอดอ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแอนะล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นแอนะล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแอนะล็อกของตัวดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำการล็อคตามคำสั่ง C# lock() . เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแอนะล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. กำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่คัดลอกอะไรเลย เพียงกำหนดค่าอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสสามารถคัดลอกได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. ไม่คัดลอกอะไรเลย เพียงกำหนดค่าอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสสามารถคัดลอกได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ความเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ความเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | ตั้งค่า Id ของภาษาทดแทน เขียน [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../../aspose.slides/ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | ตั้งค่าฟอนต์สคริปต์ซับซ้อน ค่า Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ เขียน [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_EastAsianFont](../../aspose.slides/ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | ตั้งค่าฟอนต์เอเชียตะวันออก ค่า Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ เขียน [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_Escapement](../../aspose.slides/ibaseportionformat/set_escapement/)(**float**) | ตั้งค่าข้อความซุปเปอร์สคริปต์หรือซับสคริปต์ ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซุปเปอร์สคริปต์) **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ เขียน **float**. |
| virtual void [set_FontBold](../../aspose.slides/ibaseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) | กำหนดว่าฟอนต์เป็นตัวหนาหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontHeight](../../aspose.slides/ibaseportionformat/set_fontheight/)(**float**) | ตั้งค่าความสูงของฟอนต์ของส่วนหนึ่ง **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ เขียน **float**. |
| virtual void [set_FontItalic](../../aspose.slides/ibaseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) | กำหนดว่าฟอนต์เป็นตัวเอนหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontUnderline](../../aspose.slides/ibaseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) | ตั้งค่าประเภทขีดเส้นใต้ของข้อความ ไม่ได้ใช้การสืบทอด เขียน [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) | กำหนดว่าสไตล์ขีดเส้นใต้มีคุณสมบัติ [FillFormat](../../aspose.slides/fillformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../../aspose.slides/fillformat/) ของข้อความ เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) | กำหนดว่าสไตล์ขีดเส้นใต้มีคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ของข้อความ เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_KerningMinimalSize](../../aspose.slides/ibaseportionformat/set_kerningminimalsize/)(**float**) | ตั้งค่าขนาดฟอนต์ขั้นต่ำที่ควรเปิดการเคอร์นนิง **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ เขียน **float**. |
| virtual void [set_Kumimoji](../../aspose.slides/ibaseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) | กำหนดว่าตัวเลขควรละเว้นการจัดแนวข้อความแบบแนวตั้งตามภาษาตะวันออกหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_LanguageId](../../aspose.slides/ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | ตั้งค่า Id ของภาษาตรวจสอบการพิมพ์ ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์ เขียน [System::String](../../system/string/). |
| virtual void [set_LatinFont](../../aspose.slides/ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | ตั้งค่าฟอนต์ละติน ค่า Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ เขียน [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_NormaliseHeight](../../aspose.slides/ibaseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_ProofDisabled](../../aspose.slides/ibaseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) | กำหนดว่าข้อความไม่ควรตรวจสอบการพิมพ์หรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Spacing](../../aspose.slides/ibaseportionformat/set_spacing/)(**float**) | ตั้งค่าการเพิ่มระยะห่างระหว่างตัวอักษร **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ เขียน **float**. |
| virtual void [set_SpellCheck](../../aspose.slides/ibaseportionformat/set_spellcheck/)(**bool**) | ตั้งค่าค่าที่บ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่ เมื่อกำหนดเป็น false การตรวจสอบการสะกดขององค์ประกอบข้อความจะถูกละเว้น เมื่อกำหนดเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าเริ่มต้นคือ **false**. |
| virtual void [set_StrikethroughType](../../aspose.slides/ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) | ตั้งค่าประเภทขีดฆ่าของข้อความ ไม่ได้ใช้การสืบทอด เขียน [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| virtual void [set_SymbolFont](../../aspose.slides/ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | ตั้งค่าฟอนต์สัญลักษณ์ ค่า Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์ เขียน [IFontData](../../aspose.slides/ifontdata/). |
| virtual void [set_TextCapType](../../aspose.slides/ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) | ตั้งค่าประเภทของการใช้ตัวอักษรใหญ่-เล็กของข้อความ ไม่ได้ใช้การสืบทอด เขียน [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared) ให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแอนะล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้าย typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อคตามคำสั่ง C# lock() . เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IBasePortionFormat](../../aspose.slides/ibaseportionformat/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)