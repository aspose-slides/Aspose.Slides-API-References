---
title: ChartPortionFormat
second_title: เอกสารอ้างอิง API Aspose.Slides สำหรับ C++
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ ต่างจาก IPortionFormatEffectiveData คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้
type: docs
weight: 261
url: /th/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat คลาส


คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ ต่างจาก [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/) คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้

```cpp
class ChartPortionFormat : public Aspose::Slides::BasePortionFormat,
                           public Aspose::Slides::Charts::IChartPortionFormat
```

## เมธอด

| Method | Description |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าลอยตัวแบบ C#-style ที่ที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าลอยตัวแบบ C#-style ที่ที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้ภายในเท่านั้น |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/baseportionformat/get_alternativelanguageid/)() override | คืนค่า Id ของภาษาทางเลือก อ่าน [System::String](../../system/string/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/baseportionformat/get_complexscriptfont/)() override | คืนข้อมูลฟอนต์สคริปต์ซับซ้อน ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ อ่าน [IFontData](../../aspose.slides/ifontdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/baseportionformat/get_eastasianfont/)() override | คืนข้อมูลฟอนต์ตะวันออกเอเชีย ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ อ่าน [IFontData](../../aspose.slides/ifontdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/baseportionformat/get_effectformat/)() override | คืนคุณสมบัติของข้อความ [EffectFormat](../../aspose.slides/effectformat/) ไม่ได้ใช้การสืบทอด อ่าน-อย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/) |
| **float** [get_Escapement](../../aspose.slides/baseportionformat/get_escapement/)() override | คืนข้อความซูเปอร์สคริปต์หรือซับสคริปต์ ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์) **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่านี้ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/baseportionformat/get_fillformat/)() override | คืนคุณสมบัติของข้อความ [FillFormat](../../aspose.slides/fillformat/) ไม่ได้ใช้การสืบทอด อ่าน-อย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/) |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/baseportionformat/get_fontbold/)() override | ตรวจสอบว่าฟอนต์เป็นตัวหนา یاไม่ ไม่ได้ใช้การสืบทอด อ่าน [NullableBool](../../aspose.slides/nullablebool/) |
| **float** [get_FontHeight](../../aspose.slides/baseportionformat/get_fontheight/)() override | คืนความสูงของฟอนต์ของส่วน **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจากแม่แบบ อ่าน **float** |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/baseportionformat/get_fontitalic/)() override | ตรวจสอบว่าฟอนต์เป็นอิตาลิกหรือไม่ ไม่ได้ใช้การสืบทอดอ่าน [NullableBool](../../aspose.slides/nullablebool/) |
| [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/baseportionformat/get_fontunderline/)() override | คืนประเภทการขีดเส้นล่างของข้อความ ไม่ได้ใช้การสืบทอดอ่าน [TextUnderlineType](../../aspose.slides/textunderlinetype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/baseportionformat/get_highlightcolor/)() override | คืนสีที่ใช้ไฮไลท์ข้อความ ไม่ได้ใช้การสืบทอดอ่าน-อย่างเดียว [IColorFormat](../../aspose.slides/icolorformat/) |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/baseportionformat/get_ishardunderlinefill/)() override | ตรวจสอบว่ารูปแบบการขีดเส้นล่างมีคุณสมบัติ [FillFormat](../../aspose.slides/fillformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../../aspose.slides/fillformat/) ของข้อความ อ่าน [NullableBool](../../aspose.slides/nullablebool/) |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/baseportionformat/get_ishardunderlineline/)() override | ตรวจสอบว่ารูปแบบการขีดเส้นล่างมีคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ของข้อความ อ่าน [NullableBool](../../aspose.slides/nullablebool/) |
| **float** [get_KerningMinimalSize](../../aspose.slides/baseportionformat/get_kerningminimalsize/)() override | คืนขนาดฟอนต์ขั้นต่ำที่ควรเปิดการเคอร์นิง **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่านี้ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ อ่าน **float** |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/baseportionformat/get_kumimoji/)() override | ตรวจสอบว่าตัวเลขควรละเว้นการจัดแนวแนวตั้งของข้อความที่เป็นภาษาตะวันออกหรือไม่ ไม่ได้ใช้การสืบทอดอ่าน [NullableBool](../../aspose.slides/nullablebool/) |
| [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/baseportionformat/get_languageid/)() override | คืน Id ของภาษาการตรวจสอบ พูดตรวจการสะกดและไวยากรณ์ ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์ อ่าน [System::String](../../system/string/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/baseportionformat/get_latinfont/)() override | คืนข้อมูลฟอนต์ละติน ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ อ่าน [IFontData](../../aspose.slides/ifontdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/baseportionformat/get_lineformat/)() override | คืนคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) สำหรับการขอบข้อความ ไม่ได้ใช้การสืบทอดอ่าน-อย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/) |
| [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/baseportionformat/get_normaliseheight/)() override | ตรวจสอบว่าความสูงของข้อความควรเป็นมาตรฐานหรือไม่ ไม่ได้ใช้การสืบทอดอ่าน [NullableBool](../../aspose.slides/nullablebool/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | คืนวัตถุ Parent_Immediate อ่าน-อย่างเดียว [IDOMObject](../../aspose.slides/idomobject/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | คืนพาเรนท์ [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) อ่าน-อย่างเดียว [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) |
| [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/baseportionformat/get_proofdisabled/)() override | ตรวจสอบว่าข้อความไม่ควรถูกตรวจสอบ ไม่ได้ใช้การสืบทอดอ่าน [NullableBool](../../aspose.slides/nullablebool/) |
| **float** [get_Spacing](../../aspose.slides/baseportionformat/get_spacing/)() override | คืนการเพิ่มระยะห่างระหว่างอักขระ **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่านี้ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ อ่าน **float** |
| **bool** [get_SpellCheck](../../aspose.slides/baseportionformat/get_spellcheck/)() override | รับค่าที่บ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะอนุญาต ค่าเริ่มต้นคือ **false** |
| [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/baseportionformat/get_strikethroughtype/)() override | คืนประเภทการขีดเส้นบนของข้อความ ไม่ได้ใช้การสืบทอดอ่าน [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/baseportionformat/get_symbolfont/)() override | คืนข้อมูลฟอนต์สัญลักษณ์ ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ อ่าน [IFontData](../../aspose.slides/ifontdata/) |
| [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/baseportionformat/get_textcaptype/)() override | คืนประเภทของการใช้ตัวอักษรพิมพ์ใหญ่ ไม่ได้ใช้การสืบทอดอ่าน [Slides::TextCapType](../../aspose.slides/textcaptype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/baseportionformat/get_underlinefillformat/)() override | คืนคุณสมบัติของเส้นขีดเส้นล่าง [FillFormat](../../aspose.slides/fillformat/) ไม่ได้ใช้การสืบทอดอ่าน-อย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/baseportionformat/get_underlinelineformat/)() override | คืนคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ที่ใช้ขอบเส้นขีดเส้นล่าง ไม่ได้ใช้การสืบทอดอ่าน-อย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | คืนค่าแฮชโค้ด |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เทียบกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เทียบกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแต่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแต่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_AlternativeLanguageId](../../aspose.slides/baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | ตั้งค่า Id ของภาษาทางเลือก เขียน [System::String](../../system/string/) |
| void [set_ComplexScriptFont](../../aspose.slides/baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | ตั้งค่าข้อมูลฟอนต์สคริปต์ซับซ้อน ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ เขียน [IFontData](../../aspose.slides/ifontdata/) |
| void [set_EastAsianFont](../../aspose.slides/baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | ตั้งค่าข้อมูลฟอนต์ตะวันออกเอเชีย ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ เขียน [IFontData](../../aspose.slides/ifontdata/) |
| void [set_Escapement](../../aspose.slides/baseportionformat/set_escapement/)(**float**) override | ตั้งค่าข้อความซูเปอร์สคริปต์หรือซับสคริปต์ ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์) **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่านี้ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ เขียน **float** |
| void [set_FontBold](../../aspose.slides/baseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) override | ตรวจสอบว่าฟอนต์เป็นตัวหนาหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/) |
| void [set_FontHeight](../../aspose.slides/baseportionformat/set_fontheight/)(**float**) override | ตั้งค่าความสูงของฟอนต์ของส่วน **std::numeric_limits<float>::quiet_NaN()** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจากแม่แบบ เขียน **float** |
| void [set_FontItalic](../../aspose.slides/baseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) override | ตรวจสอบว่าฟอนต์เป็นอิตาลิกหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/) |
| void [set_FontUnderline](../../aspose.slides/baseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) override | ตั้งค่าประเภทการขีดเส้นล่างของข้อความ ไม่ได้ใช้การสืบทอด เขียน [TextUnderlineType](../../aspose.slides/textunderlinetype/) |
| void [set_IsHardUnderlineFill](../../aspose.slides/baseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) override | ตรวจสอบว่ารูปแบบการขีดเส้นล่างมีคุณสมบัติ [FillFormat](../../aspose.slides/fillformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../../aspose.slides/fillformat/) ของข้อความ เขียน [NullableBool](../../aspose.slides/nullablebool/) |
| void [set_IsHardUnderlineLine](../../aspose.slides/baseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) override | ตรวจสอบว่ารูปแบบการขีดเส้นล่างมีคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../../aspose.slides/lineformat/) ของข้อความ เขียน [NullableBool](../../aspose.slides/nullablebool/) |
| void [set_KerningMinimalSize](../../aspose.slides/baseportionformat/set_kerningminimalsize/)(**float**) override | ตั้งค่าขนาดฟอนต์ขั้นต่ำที่ควรเปิดการเคอร์นิง **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่านี้ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ เขียน **float** |
| void [set_Kumimoji](../../aspose.slides/baseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) override | ตรวจสอบว่าตัวเลขควรละเว้นการจัดแนวแนวตั้งของข้อความที่เป็นภาษาตะวันออกหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/) |
| void [set_LanguageId](../../aspose.slides/baseportionformat/set_languageid/)([System::String](../../system/string/)) override | ตั้งค่า Id ของภาษาการตรวจสอบ ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์ เขียน [System::String](../../system/string/) |
| void [set_LatinFont](../../aspose.slides/baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | ตั้งค่าข้อมูลฟอนต์ละติน ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ เขียน [IFontData](../../aspose.slides/ifontdata/) |
| void [set_NormaliseHeight](../../aspose.slides/baseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) override | ตรวจสอบว่าความสูงของข้อความควรเป็นมาตรฐานหรือไม่ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/) |
| void [set_ProofDisabled](../../aspose.slides/baseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) override | ตรวจสอบว่าข้อความไม่ควรถูกตรวจสอบ ไม่ได้ใช้การสืบทอด เขียน [NullableBool](../../aspose.slides/nullablebool/) |
| void [set_Spacing](../../aspose.slides/baseportionformat/set_spacing/)(**float**) override | ตั้งค่าการเพิ่มระยะห่างระหว่างอักขระ **std::numeric_limits<float>::quiet_NaN()** หมายถึงค่านี้ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ เขียน **float** |
| void [set_SpellCheck](../../aspose.slides/baseportionformat/set_spellcheck/)(**bool**) override | ตั้งค่าค่าที่บ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกระงับ เมื่อตั้งเป็น true การตรวจสอบการสะกดจะอนุญาต ค่าเริ่มต้นคือ **false** |
| void [set_StrikethroughType](../../aspose.slides/baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) override | ตั้งค่าประเภทการขีดเส้นบนของข้อความ ไม่ได้ใช้การสืบทอด เขียน [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) |
| void [set_SymbolFont](../../aspose.slides/baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | ตั้งค่าข้อมูลฟอนต์สัญลักษณ์ ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจากแม่แบบ เขียน [IFontData](../../aspose.slides/ifontdata/) |
| void [set_TextCapType](../../aspose.slides/baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) override | ตั้งค่าประเภทของการใช้ตัวอักษรพิมพ์ใหญ่ ไม่ได้ใช้การสืบทอด เขียน [Slides::TextCapType](../../aspose.slides/textcaptype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตการสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้แปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยข้อมูลภายในทั้งหมด |
## หมายเหตุ


คลาสนี้ใช้เพื่อคืนและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดสำหรับส่วนเฉพาะ หมายความว่าไม่มีการสืบทอดเมื่อดึงค่าจึงส่วนใหญ่คุณจะได้ค่า "undefined"

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอดคุณต้องใช้เมธอด [PortionFormat::GetEffective](../../aspose.slides/portionformat/geteffective/) ที่คืนอินสแตนซ์ของ [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/)

## ดูเพิ่มเติม

* คลาส [BasePortionFormat](../../aspose.slides/baseportionformat/)
* คลาส [IChartPortionFormat](../ichartportionformat/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)