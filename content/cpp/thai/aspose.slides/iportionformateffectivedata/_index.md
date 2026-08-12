---
title: IPortionFormatEffectiveData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีประสิทธิภาพ.
type: docs
weight: 3342
url: /th/aspose.slides/iportionformateffectivedata/
---
## คลาส IPortionFormatEffectiveData

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีประสิทธิภาพ

```cpp
class IPortionFormatEffectiveData : public virtual Aspose::Slides::IBasePortionFormatEffectiveData
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงตามสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่า ตามสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformateffectivedata/get_alternativelanguageid/)() | คืนค่า Id ของภาษาทางเลือก. อ่านอย่างเดียว [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | คืนค่าตัวระบุของที่คั่นหน้า. อ่านอย่างเดียว [System::String](../../system/string/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformateffectivedata/get_complexscriptfont/)() | คืนข้อมูลแบบอักษรสคริปต์ซับซ้อน. อ่านอย่างเดียว [IFontData](../ifontdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformateffectivedata/get_eastasianfont/)() | คืนข้อมูลแบบอักษรเอเชียตะวันออก. อ่านอย่างเดียว [IFontData](../ifontdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](../ibaseportionformateffectivedata/get_effectformat/)() | คืนคุณสมบัติของข้อความ [EffectFormat](../effectformat/). อ่านอย่างเดียว [IEffectFormatEffectiveData](../ieffectformateffectivedata/) |
| virtual **float** [get_Escapement](../ibaseportionformateffectivedata/get_escapement/)() | คืนข้อความตัวเหนือหรือตัวล่าง. ค่าอยู่ระหว่าง -100% (ตัวล่าง) ถึง 100% (ตัวเหนือ). อ่านอย่างเดียว **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](../ibaseportionformateffectivedata/get_fillformat/)() | คืนคุณสมบัติของข้อความ [FillFormat](../fillformat/). อ่านอย่างเดียว [IFillFormatEffectiveData](../ifillformateffectivedata/) |
| virtual **bool** [get_FontBold](../ibaseportionformateffectivedata/get_fontbold/)() | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. อ่านอย่างเดียว **bool** |
| virtual **float** [get_FontHeight](../ibaseportionformateffectivedata/get_fontheight/)() | คืนความสูงของแบบอักษรของส่วนข้อความ หน่วยเป็นพอยท์. อ่านอย่างเดียว **float** |
| virtual **bool** [get_FontItalic](../ibaseportionformateffectivedata/get_fontitalic/)() | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่. อ่านอย่างเดียว **bool** |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformateffectivedata/get_fontunderline/)() | คืนประเภทการขีดเส้นใต้ของข้อความ. อ่านอย่างเดียว [TextUnderlineType](../textunderlinetype/) |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](../ibaseportionformateffectivedata/get_highlightcolor/)() | คืนสีที่ใช้ไฮไลท์ข้อความ. อ่านอย่างเดียว [System::Drawing::Color](../../system.drawing/color/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่านอย่างเดียว [IHyperlink](../ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่านอย่างเดียว [IHyperlink](../ihyperlink/) |
| virtual **bool** [get_IsHardUnderlineFill](../ibaseportionformateffectivedata/get_ishardunderlinefill/)() | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ [FillFormat](../fillformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [FillFormat](../fillformat/) ของข้อความ. อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsHardUnderlineLine](../ibaseportionformateffectivedata/get_ishardunderlineline/)() | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ [LineFormat](../lineformat/) ของตัวเองหรือสืบทอดจากคุณสมบัติ [LineFormat](../lineformat/) ของข้อความ. อ่านอย่างเดียว **bool** |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformateffectivedata/get_kerningminimalsize/)() | คืนขนาดแบบอักษรขั้นต่ำที่ควรเปิดการทำ kerning. อ่านอย่างเดียว **float** |
| virtual **bool** [get_Kumimoji](../ibaseportionformateffectivedata/get_kumimoji/)() | กำหนดว่าตัวเลขควรละเว้นการจัดวางข้อความในแนวตั้งตามภาษาตะวันออกของข้อความหรือไม่. อ่านอย่างเดียว **bool** |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformateffectivedata/get_languageid/)() | คืนค่า Id ของภาษา. อ่านอย่างเดียว [System::String](../../system/string/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformateffectivedata/get_latinfont/)() | คืนข้อมูลแบบอักษรละติน. อ่านอย่างเดียว [IFontData](../ifontdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](../ibaseportionformateffectivedata/get_lineformat/)() | คืนคุณสมบัติ [LineFormat](../lineformat/) สำหรับการรอบขอบข้อความ. อ่านอย่างเดียว [ILineFormatEffectiveData](../ilineformateffectivedata/) |
| virtual **bool** [get_NormaliseHeight](../ibaseportionformateffectivedata/get_normaliseheight/)() | กำหนดว่าความสูงของข้อความควรทำให้เป็นค่ามาตรฐานหรือไม่. อ่านอย่างเดียว **bool** |
| virtual **bool** [get_ProofDisabled](../ibaseportionformateffectivedata/get_proofdisabled/)() | กำหนดว่าข้อความไม่ควรตรวจทานหรือไม่. อ่านอย่างเดียว **bool** |
| virtual **bool** [get_SmartTagClean](../ibaseportionformateffectivedata/get_smarttagclean/)() | กำหนดว่า smart tag ควรถูกทำความสะอาดหรือไม่. อ่านอย่างเดียว **bool** |
| virtual **float** [get_Spacing](../ibaseportionformateffectivedata/get_spacing/)() | คืนการเพิ่มระยะห่างระหว่างอักขระ หน่วยเป็นพอยท์. อ่านอย่างเดียว **float** |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformateffectivedata/get_strikethroughtype/)() | คืนประเภทการขีดฆ่าของข้อความ. อ่านอย่างเดียว [TextStrikethroughType](../textstrikethroughtype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformateffectivedata/get_symbolfont/)() | คืนข้อมูลแบบอักษรสัญลักษณ์. อ่านอย่างเดียว [IFontData](../ifontdata/) |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformateffectivedata/get_textcaptype/)() | คืนประเภทของการทำตัวอักษรเป็นตัวใหญ่ของข้อความ. อ่านอย่างเดียว [Slides::TextCapType](../textcaptype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](../ibaseportionformateffectivedata/get_underlinefillformat/)() | คืนคุณสมบัติของเส้นขีดเส้นใต้ [FillFormat](../fillformat/). อ่านอย่างเดียว [IFillFormatEffectiveData](../ifillformateffectivedata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](../ibaseportionformateffectivedata/get_underlinelineformat/)() | คืนคุณสมบัติ [LineFormat](../lineformat/) ที่ใช้รอบขอบเส้นขีดเส้นใต้. อ่านอย่างเดียว [ILineFormatEffectiveData](../ilineformateffectivedata/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับแต่งของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับแต่งของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยทรัพยากรโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IPortionFormat](../iportionformat/) เพื่อคืนค่าการจัดรูปแบบที่มีผลพร้อมกับการสืบทอดที่นำมาใช้

## ดูเพิ่มเติม

* คลาส [IBasePortionFormatEffectiveData](../ibaseportionformateffectivedata/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)