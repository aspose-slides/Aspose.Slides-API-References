---
title: PortionFormat
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ. แตกต่างจาก IPortionFormatEffectiveData./iportionformateffectivedata คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 9510
url: /th/aspose.slides/portionformat/
---
## PortionFormat คลาส

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ. แตกต่างจาก [`IPortionFormatEffectiveData`](../iportionformateffectivedata), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## คอนสตรัคเตอร์

| ชื่อ | คำอธิบาย |
| --- | --- |
| [PortionFormat](portionformat)() | สร้างอินสแตนซ์ใหม่ของคลาส [`PortionFormat`](../portionformat). |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | คืนค่า หรือ ตั้งค่า Id ของภาษาทางเลือก. อ่าน/เขียน String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้ดึงอินเทอร์เฟซ IPresentationComponent พื้นฐาน. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | คืนค่า หรือ ตั้งค่าตัวระบุบุ๊กมาร์ก. อ่าน/เขียน String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | คืนค่า หรือ ตั้งค่าข้อมูลฟอนต์สคริปต์ซับซ้อน. Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | คืนค่า หรือ ตั้งค่าข้อมูลฟอนต์เอเชียตะวันออก. Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | คืนคุณสมบัติ EffectFormat ของข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | คืนค่า หรือ ตั้งค่าข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | คืนคุณสมบัติ FillFormat ของข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | กำหนดว่าฟอนต์เป็นแบบหนาบหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | คืนค่า หรือ ตั้งค่าความสูงฟอนต์ของส่วน. **float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | กำหนดว่าฟอนต์เป็นแบบเอียงหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | คืนค่า หรือ ตั้งค่าชนิดการขีดเส้นใต้ของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | คืนสีที่ใช้เน้นข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | คืนค่า หรือ ตั้งค่าลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | ตัวจัดการลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | คืนค่า หรือ ตั้งค่าลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจาก FillFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจาก LineFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | คืนค่า หรือ ตั้งค่าขนาดฟอนต์ต่ำสุดที่ควรเปิดการเคอร์นิง. **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | กำหนดว่าตัวเลขควรละเว้นการจัดวางแนวตั้งตามภาษาตะวันออกของข้อความหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | คืนค่า หรือ ตั้งค่า Id ของภาษาการพิสูจน์. ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | คืนค่า หรือ ตั้งค่าข้อมูลฟอนต์ละติน. Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | คืนคุณสมบัติ LineFormat สำหรับการร่างขอบข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | กำหนดว่าข้อความไม่ควรถูกตรวจสอบการพิสูจน์หรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | กำหนดว่าต้องทำความสะอาดสมาร์ทแท็กหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | คืนค่า หรือ ตั้งค่าการเพิ่มระยะห่างระหว่างตัวอักษร. **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | รับหรือกำหนดค่าที่บ่งบอกว่าการตรวจสอบการสะกดถูกเปิดใช้งานสำหรับส่วนข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งค่าเป็น false, การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกยกเลิก. เมื่อตั้งค่าเป็น true, การตรวจสอบการสะกดจะได้รับอนุญาต. ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | คืนค่า หรือ ตั้งค่าชนิดการขีดเส้นผ่านของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | คืนค่า หรือ ตั้งค่าข้อมูลฟอนต์สัญลักษณ์. Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | คืนค่า หรือ ตั้งค่าชนิดการแปลงตัวอักษรใหญ่/เล็กของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | คืนคุณสมบัติ FillFormat ของเส้นขีดเส้นใต้. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | คืนคุณสมบัติ LineFormat ที่ใช้ร่างเส้นขีดเส้นใต้. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | รับข้อมูลการจัดรูปแบบส่วนที่มีผลโดยคำนึงถึงการสืบทอด. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | คืนค่า hash code. |

### หมายเหตุ

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดสำหรับส่วนเฉพาะ. นั่นหมายความว่าเมื่อดึงค่าจะไม่มีการสืบทอดจึงส่วนใหญ่จะได้ค่า “undefined”.

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้เมธอด [`GetEffective`](./geteffective) ซึ่งคืนค่าอินสแตนซ์ [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการกำหนดฟอนต์ละตินให้กับส่วนของ Paragraph ใน PowerPoint Presentation.

```csharp
[C#]
//สร้างอ็อบเจ็กต์ Presentation ที่แทนไฟล์การนำเสนอ
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides ใช้ตัวระบุพิเศษเหล่านี้ (คล้ายกับที่ใช้ใน PowerPoint):
// +mn-lt - ฟอนต์ Body Latin (ฟอนต์ Latin รอง)
// +mj-lt - ฟอนต์ Heading Latin (ฟอนต์ Latin หลัก)
// +mn-ea - ฟอนต์ Body East Asian (ฟอนต์ East Asian รอง)
// +mj-ea - ฟอนต์ Body East Asian (ฟอนต์ East Asian รอง)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### ดูเพิ่มเติม

* คลาส [BasePortionFormat](../baseportionformat)
* อินเทอร์เฟซ [IPortionFormat](../iportionformat)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->