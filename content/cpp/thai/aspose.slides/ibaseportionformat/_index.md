---
title: IBasePortionFormat
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของข้อความ. ไม่เหมือน IPortionFormatEffectiveData, คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 1457
url: /th/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat คลาส


คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของข้อความ. ไม่เหมือนกับ [IPortionFormatEffectiveData](../iportionformateffectivedata/), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | คืนค่า Id ของภาษาทางเลือก. อ่าน [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | คืนข้อมูลฟอนต์สคริปต์ซับซ้อน. ค่าศูนย์ (Null) หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. อ่าน [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | คืนข้อมูลฟอนต์เอเชียตะวันออก. ค่าศูนย์ (Null) หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. อ่าน [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | คืนคุณสมบัติของข้อความ [EffectFormat](../effectformat/). ไม่มีการสืบทอด. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | คืนข้อความเชิงบนหรือเชิงล่าง. ค่าอยู่ในช่วง -100% (เชิงล่าง) ถึง 100% (เชิงบน). **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | คืนคุณสมบัติของข้อความ [FillFormat](../fillformat/). ไม่มีการสืบทอด. อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | กำหนดว่าฟอนต์เป็นตัวหนาหรือไม่. ไม่มีการสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | คืนความสูงของฟอนต์ของส่วน. **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. อ่าน **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | กำหนดว่าฟอนต์เป็นอิตาลิกหรือไม่. ไม่มีการสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | คืนประเภทขีดเส้นใต้ของข้อความ. ไม่มีการสืบทอด. อ่าน [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | คืนสีที่ใช้เน้นข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ. อ่าน [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ. อ่าน [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | คืนขนาดฟอนต์ขั้นต่ำที่ต้องเปิดใช้การเคอร์นิง. **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. อ่าน **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | กำหนดว่าตัวเลขควรละเว้นการจัดวางแนวตั้งตามภาษาตะวันออกของข้อความหรือไม่. ไม่มีการสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | คืนค่า Id ของภาษาตรวจสอบ. ใช้ตรวจสอบการสะกดและไวยากรณ์. อ่าน [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | คืนข้อมูลฟอนต์ละติน. ค่าศูนย์ (Null) หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. อ่าน [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | คืนคุณสมบัติ [LineFormat](../lineformat/) สำหรับการทำโครงร่างข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่มีการสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่. ไม่มีการสืบทอด. อ่าน [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | คืนการเพิ่มระยะห่างระหว่างอักขระ. **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. อ่าน **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | รับค่าที่บ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกปิดใช้งาน. เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะอนุญาต. ค่าตั้งต้นคือ **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | คืนประเภทขีดฆ่าของข้อความ. ไม่มีการสืบทอด. อ่าน [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | คืนข้อมูลฟอนต์สัญลักษณ์. ค่าศูนย์ (Null) หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. อ่าน [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | คืนประเภทของการใช้อักษรตัวพิมพ์ใหญ่ของข้อความ. ไม่มีการสืบทอด. อ่าน [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | คืนคุณสมบัติเส้นขีด [FillFormat](../fillformat/) ของขีดเส้นใต้. ไม่มีการสืบทอด. อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | คืนคุณสมบัติ [LineFormat](../lineformat/) ที่ใช้ทำโครงร่างเส้นขีด. ไม่มีการสืบทอด. อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อนุกรมของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. อนุกรมของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. อนุกรมของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อนุกรมของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับการอ้างอิงร่วมตามค่าที่ระบุ. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | กำหนดค่า Id ของภาษาทางเลือก. เขียน [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | กำหนดข้อมูลฟอนต์สคริปต์ซับซ้อน. ค่าศูนย์ (Null) หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. เขียน [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | กำหนดข้อมูลฟอนต์เอเชียตะวันออก. ค่าศูนย์ (Null) หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. เขียน [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | กำหนดข้อความเชิงบนหรือเชิงล่าง. ค่าอยู่ในช่วง -100% (เชิงล่าง) ถึง 100% (เชิงบน). **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. เขียน **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | กำหนดว่าฟอนต์เป็นตัวหนาหรือไม่. ไม่มีการสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | กำหนดความสูงของฟอนต์ของส่วน. **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. เขียน **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | กำหนดว่าฟอนต์เป็นอิตาลิกหรือไม่. ไม่มีการสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | กำหนดประเภทขีดเส้นใต้ของข้อความ. ไม่มีการสืบทอด. เขียน [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตนเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | กำหนดขนาดฟอนต์ขั้นต่ำที่ต้องเปิดใช้การเคอร์นิง. **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. เขียน **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | กำหนดว่าตัวเลขควรละเว้นการจัดวางแนวตั้งตามภาษาตะวันออกของข้อความหรือไม่. ไม่มีการสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | กำหนดค่า Id ของภาษาตรวจสอบ. ใช้ตรวจสอบการสะกดและไวยากรณ์. เขียน [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | กำหนดข้อมูลฟอนต์ละติน. ค่าศูนย์ (Null) หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. เขียน [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่มีการสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่. ไม่มีการสืบทอด. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | กำหนดการเพิ่มระยะห่างระหว่างอักขระ. **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. เขียน **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | กำหนดค่าที่บ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกปิดใช้งาน. เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะอนุญาต. ค่าตั้งต้นคือ **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | กำหนดประเภทขีดฆ่าของข้อความ. ไม่มีการสืบทอด. เขียน [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | กำหนดข้อมูลฟอนต์สัญลักษณ์. ค่าศูนย์ (Null) หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจากมาสเตอร์. เขียน [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | กำหนดประเภทของการใช้อักษรตัวพิมพ์ใหญ่ของข้อความ. ไม่มีการสืบทอด. เขียน [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อนุกรมของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคำสั่ง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้ [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ


คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนของข้อความที่กำหนดไว้สำหรับส่วนเฉพาะ. นั่นหมายความว่าไม่มีการสืบทอดเมื่อดึงค่าต่าง ๆ ดังนั้นในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง “ไม่ได้กำหนด”.

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้วิธี [IPortionFormat::GetEffective](../iportionformat/geteffective/) ซึ่งคืนค่าอินสแทนซ์ [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)