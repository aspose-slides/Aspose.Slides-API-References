---
title: IBasePortionFormat
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ. แตกต่างจาก IPortionFormatEffectiveData./iportionformateffectivedata คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 5330
url: /th/aspose.slides/ibaseportionformat/
---
## อินเทอร์เฟซ IBasePortionFormat

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ. แตกต่างจาก [`IPortionFormatEffectiveData`](../iportionformateffectivedata), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

```csharp
public interface IBasePortionFormat
```

## คุณสมบัติ

| ชื่อ | รายละเอียด |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | ส่งคืนหรือกำหนด Id ของภาษาทางเลือก. อ่าน/เขียน String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. ค่า Null หมายถึงแบบอักษรไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. ค่า Null หมายถึงแบบอักษรไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | ส่งคืนคุณสมบัติ EffectFormat ของข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | ส่งคืนหรือกำหนดข้อความตัวบนหรือตัวล่าง. ค่าอยู่ระหว่าง -100% (ตัวล่าง) ถึง 100% (ตัวบน). **float.NaN** หมายถึงค่าที่ไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | ส่งคืนคุณสมบัติ FillFormat ของข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | ระบุว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | ส่งคืนหรือกำหนดความสูงของแบบอักษรของส่วน. **float.NaN** หมายถึงความสูงที่ไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | ระบุว่าแบบอักษรเป็นตัวเอียงหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | ส่งคืนหรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | ส่งคืนสีที่ใช้ไฮไลท์ข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | ระบุว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | ระบุว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | ส่งคืนหรือกำหนดขนาดแบบอักษรขั้นต่ำที่ควรเปิดการปรับระยะห่างของตัวอักษร. **float.NaN** หมายถึงค่าที่ไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | ระบุว่าตัวเลขควรละเลยการจัดวางข้อความแนวตั้งตามภาษาตะวันออกหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | ส่งคืนหรือกำหนด Id ของภาษาตรวจสอบ. ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลแบบอักษรละติน. ค่า Null หมายถึงแบบอักษรไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | ส่งคืนคุณสมบัติ LineFormat สำหรับการขอบข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | ระบุว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | ระบุว่าข้อความไม่ควรตรวจสอบหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | ส่งคืนหรือกำหนดค่าการเพิ่มระยะห่างระหว่างตัวอักษร. **float.NaN** หมายถึงค่าที่ไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | ส่งคืนหรือกำหนดค่าที่ระบุว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกละเว้น. เมื่อตั้งเป็น true การตรวจสอบการสะกดจะถูกเปิดใช้งาน. ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | ส่งคืนหรือกำหนดประเภทการขีดฆ่าของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. ค่า Null หมายถึงแบบอักษรไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | ส่งคืนหรือกำหนดประเภทของการใช้ตัวพิมพ์ใหญ่ในข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | ส่งคืนคุณสมบัติ FillFormat ของเส้นขีดเส้นใต้. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | ส่งคืนคุณสมบัติ LineFormat ที่ใช้วาดขอบเส้นขีดเส้นใต้. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |

### หมายเหตุ

คลาสนี้ใช้เพื่อส่งคืนและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดสำหรับส่วนที่ระบุ. นี้หมายความว่าไม่มีการสืบทอดเมื่อดึงค่าจึงในหลายกรณีคุณจะได้ค่าที่หมายถึง "undefined". เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมทั้งที่สืบทอดคุณต้องใช้เมธอด [`GetEffective`](../iportionformat/geteffective) ซึ่งจะคืนค่าอินสแตนซ์ [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### ดูเพิ่มเติม

* เนมสเปส [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->