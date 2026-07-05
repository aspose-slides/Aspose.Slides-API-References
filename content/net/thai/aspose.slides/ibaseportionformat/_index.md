---
title: IBasePortionFormat
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบข้อความส่วนย่อย. ไม่เหมือน IPortionFormatEffectiveData./iportionformateffectivedata คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 5310
url: /th/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat อินเทอร์เฟซ

คลาสนี้มีคุณสมบัติการจัดรูปแบบข้อความส่วนย่อย. ไม่เหมือนกับ [`IPortionFormatEffectiveData`](../iportionformateffectivedata) คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

```csharp
public interface IBasePortionFormat
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | คืนค่า หรือ กำหนด Id ของภาษาทางเลือก. อ่าน/เขียน String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | คืนค่า หรือ กำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | คืนค่า หรือ กำหนดข้อมูลแบบอักษรเอเชียตะวันออก. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | คืนค่าคุณสมบัติ EffectFormat ของข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | คืนค่า หรือ กำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | กำหนดว่าแบบอักษรเป็นหนา หรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | คืนค่า หรือ กำหนดความสูงของแบบอักษรของส่วน. **float.NaN** หมายถึงความสูงที่ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | กำหนดว่าแบบอักษรเป็นเอียง หรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | คืนค่า หรือ กำหนดประเภทขีดเส้นใต้ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | คืนค่าสีที่ใช้เน้นข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจาก FillFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจาก LineFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | คืนค่า หรือ กำหนดขนาดแบบอักษรต่ำสุดที่ควรเปิดการจัดระยะตัวอักษร (kerning). **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | กำหนดว่าตัวเลขควรละเว้นการจัดวางข้อความแนวตั้งเฉพาะภาษาตะวันออกของข้อความหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | คืนค่า หรือ กำหนด Id ของภาษาการพิสูจน์. ใช้ในการตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | คืนค่า หรือ กำหนดข้อมูลแบบอักษรละติน. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | คืนค่าคุณสมบัติ LineFormat สำหรับการเว้นขอบข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | กำหนดว่าข้อความไม่ควรถูกพิสูจน์หรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | คืนค่า หรือ กำหนดการเพิ่มช่องว่างระหว่างอักขระ. **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | รับหรือกำหนดค่าที่ระบุว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกยกเลิก. เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต. ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | คืนค่า หรือ กำหนดประเภทขีดทับของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | คืนค่า หรือ กำหนดข้อมูลแบบอักษรเชิงสัญลักษณ์. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | คืนค่า หรือ กำหนดประเภทการพิมพ์ใหญ่ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของเส้นขีดเส้นใต้. ไม่มีการสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | คืนค่าคุณสมบัติ LineFormat ที่ใช้ในการเว้นขอบเส้นขีดเส้นใต้. ไม่มีการสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |

### หมายเหตุ

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบข้อความส่วนย่อยที่กำหนดสำหรับส่วนเฉพาะ. นั่นหมายความว่าไม่มีการสืบทอดเมื่อดึงค่า ดังนั้นในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง “undefined”.

เพื่อรับค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณจำเป็นต้องใช้เมธอด [`GetEffective`](../iportionformat/geteffective) ซึ่งคืนค่าอินสแตนซ์ [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->