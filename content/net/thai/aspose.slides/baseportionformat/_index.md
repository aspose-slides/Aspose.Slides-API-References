---
title: BasePortionFormat
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: คุณสมบัติการจัดรูปแบบส่วนข้อความทั่วไป.
type: docs
weight: 970
url: /th/aspose.slides/baseportionformat/
---
## คลาส BasePortionFormat

คุณสมบัติการจัดรูปแบบส่วนข้อความทั่วไป

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## คุณลักษณะ

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาทางเลือก. อ่าน/เขียน String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้เข้าถึงอินเทอร์เฟซ base IPresentationComponent. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลฟอนต์สำหรับสคริปต์ซับซ้อน. Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลฟอนต์ East Asian. Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | คืนค่าคุณสมบัติ EffectFormat ของข้อความ. ไม่ได้สืบทอด. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | คืนค่า หรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของข้อความ. ไม่ได้สืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่ได้สืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | คืนค่า หรือกำหนดความสูงของแบบอักษรในส่วน. **float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | กำหนดว่าแบบอักษรเป็นอิตาลิกหรือไม่. ไม่ได้สืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่ได้สืบทอด. อ่าน/เขียน [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | คืนค่าสีที่ใช้ไฮไลท์ข้อความ. ไม่ได้สืบทอด. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจาก FillFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจาก LineFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | คืนค่า หรือกำหนดขนาดฟอนต์ขั้นต่ำที่ต้องเปิดใช้ kerning. **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | กำหนดว่าตัวเลขควรละเว้นการจัดวางข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. ไม่ได้สืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาการตรวจสอบ. ใช้สำหรับการตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลฟอนต์ละติน. Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | คืนค่าคุณสมบัติ LineFormat สำหรับการรอบขอบข้อความ. ไม่ได้สืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่ได้สืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่. ไม่ได้สืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | คืนค่า หรือกำหนดการเพิ่มระยะห่างระหว่างตัวอักษร. **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งเป็น false, การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกปิด. เมื่อตั้งเป็น true, จะเปิดให้ตรวจสอบการสะกด. ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | คืนค่า หรือกำหนดประเภทการตีผ่านของข้อความ. ไม่ได้สืบทอด. อ่าน/เขียน [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลฟอนต์สัญลักษณ์. Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | คืนค่า หรือกำหนดประเภทของการพิมพ์ใหญ่/เล็กของข้อความ. ไม่ได้สืบทอด. อ่าน/เขียน [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของเส้นขีดเส้นใต้. ไม่ได้สืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | คืนค่าคุณสมบัติ LineFormat ที่ใช้รอบเส้นขีดเส้นใต้. ไม่ได้สืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |

## วิธีการ

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | คืนค่า hash code. |

### ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject)
* อินเทอร์เฟซ [IBasePortionFormat](../ibaseportionformat)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->