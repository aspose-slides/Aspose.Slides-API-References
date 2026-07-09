---
title: IBasePortionFormat
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ. ไม่เหมือน IPortionFormatEffectiveData./iportionformateffectivedata คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 5310
url: /th/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat ส่วนต่อประสาน

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ Unlike [`IPortionFormatEffectiveData`](../iportionformateffectivedata), all properties of this class are writeable.

```csharp
public interface IBasePortionFormat
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาทางเลือก. อ่าน/เขียน String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. Null หมายถึงแบบอักษรไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. Null หมายถึงแบบอักษรไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | คืนค่าคุณสมบัติ EffectFormat ของข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | คืนค่า หรือกำหนดข้อความเป็นตัวยกหรือตัวห้อย. ค่าอยู่ระหว่าง -100% (ตัวห้อย) ถึง 100% (ตัวยก). **float.NaN** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | ระบุว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | คืนค่า หรือกำหนดความสูงของแบบอักษรของส่วน. **float.NaN** หมายถึงความสูงไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | ระบุว่าแบบอักษรเป็นตัวเอียงหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | คืนค่าสีที่ใช้ไฮไลท์ข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | ระบุว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจาก FillFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | ระบุว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจาก LineFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | คืนค่า หรือกำหนดขนาดฟอนต์ขั้นต่ำที่ควรเปิด kerning. **float.NaN** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | ระบุว่าตัวเลขควรละเว้นการจัดเรียงข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาการตรวจสอบ. ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรลาติน. Null หมายถึงแบบอักษรไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | คืนค่าคุณสมบัติ LineFormat สำหรับการเค้าโครงข้อความ. ไม่มีการสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | ระบุว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | ระบุว่าข้อความไม่ควรตรวจสอบหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | คืนค่า หรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. **float.NaN** หมายถึงค่าไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งเป็น false, การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกปิด. เมื่อตั้งเป็น true, การตรวจสอบการสะกดจะได้รับอนุญาต. ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | คืนค่า หรือกำหนดประเภทการขีดเส้นผ่านของข้อความ. ไม่มีการสืบทอด. อ่าน/เขียน [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. Null หมายถึงแบบอักษรไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | คืนค่า หรือกำหนดประเภทการใช้ตัวอักษรตัวพิมพ์ใหญ่/เล็ก. ไม่มีการสืบทอด. อ่าน/เขียน [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของเส้นขีดเส้นใต้. ไม่มีการสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | คืนค่าคุณสมบัติ LineFormat ที่ใช้เค้าโครงเส้นขีดเส้นใต้. ไม่มีการสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |

### หมายเหตุ

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดสำหรับแต่ละส่วน. ซึ่งหมายความว่าไม่มีการสืบทอดเมื่อดึงค่า ดังนั้นในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง “ไม่มีการกำหนด”. เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้เมธอด [`GetEffective`](../iportionformat/geteffective) ซึ่งจะคืนค่าอินสแตนซ์ของ [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->