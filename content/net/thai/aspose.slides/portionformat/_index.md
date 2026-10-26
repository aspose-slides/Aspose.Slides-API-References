---
title: PortionFormat
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของข้อความ. แตกต่างจาก IPortionFormatEffectiveData./iportionformateffectivedata คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 9490
url: /th/aspose.slides/portionformat/
---
## PortionFormat คลาส

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](../iportionformateffectivedata), all properties of this class are writeable.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [PortionFormat](portionformat)() | สร้างอินสแตนซ์ใหม่ของคลาส [`PortionFormat`](../portionformat). |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | คืนค่า หรือ ตั้งค่า Id ของภาษาทางเลือก. อ่าน/เขียน String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IPresentationComponent พื้นฐาน. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | คืนค่า หรือ ตั้งค่า identifier ของ bookmark. อ่าน/เขียน String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | คืนค่า หรือ ตั้งค่าข้อมูลแบบอักษรสคริปต์ซับซ้อน. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | คืนค่า หรือ ตั้งค่าข้อมูลแบบอักษร East Asian. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | คืนค่าคุณสมบัติ EffectFormat ของข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | คืนค่า หรือ ตั้งค่าข้อความซุปเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซุปเปอร์สคริปต์). **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | คืนค่า หรือ ตั้งค่าความสูงของแบบอักษรของส่วน. **float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | กำหนดว่าแบบอักษรเป็นอิตาลิกหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | คืนค่า หรือ ตั้งค่าชนิดการขีดเส้นใต้ของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | คืนค่าสีที่ใช้ไฮไลต์ข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | คืนค่า หรือ ตั้งค่าลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | ผู้จัดการลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | คืนค่า หรือ ตั้งค่าลิงก์ที่กำหนดสำหรับเมาส์อยู่เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | คืนค่า หรือ ตั้งค่าขนาดแบบอักษรขั้นต่ำที่ควรเปิดใช้งาน kerning. **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | กำหนดว่าตัวเลขควรละเลยการจัดเรียงข้อความแนวตั้งเฉพาะภาษาตะวันออกของข้อความหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | คืนค่า หรือ ตั้งค่า Id ของภาษาตรวจสอบ. ใช้สำหรับการตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | คืนค่า หรือ ตั้งค่าข้อมูลแบบอักษร Latin. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | คืนค่าคุณสมบัติ LineFormat สำหรับการรอบขอบข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | กำหนดว่าความสูงของข้อความควรได้รับการปรับให้เป็นมาตรฐานหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | กำหนดว่า smart tag ควรถูกทำความสะอาดหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | คืนค่า หรือ ตั้งค่าเพิ่มค่าระยะห่างระหว่างอักขระ. **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | รับหรือ ตั้งค่าค่าที่บ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกปิดใช้งาน. เมื่อตั้งเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต. ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | คืนค่า หรือ ตั้งค่าชนิดการขีดฆ่าของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | คืนค่า หรือ ตั้งค่าข้อมูลแบบอักษรสัญลักษณ์. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | คืนค่า หรือ ตั้งค่าชนิดของการใช้ตัวพิมพ์ใหญ่ในข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของเส้นขีดเส้นใต้. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | คืนค่าคุณสมบัติ LineFormat ที่ใช้รอบเส้นขีดเส้นใต้. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับอ็อบเจกต์ที่ระบุ. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | รับข้อมูลการจัดรูปแบบส่วนที่มีผลจริงพร้อมการสืบทอดที่นำมาใช้. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | คืนค่า hash code. |

### หมายเหตุ

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนของข้อความที่กำหนดสำหรับส่วนเฉพาะ. นั่นหมายความว่าไม่มีการสืบทอดเมื่อดึงค่าจึงในกรณีส่วนใหญ่คุณจะได้ค่าที่หมายถึง "undefined".

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลจริงรวมถึงที่สืบทอดคุณต้องใช้เมธอด [`GetEffective`](./geteffective) ซึ่งจะคืนค่าอินสแตนซ์ [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการกำหนดแบบอักษร Latin ให้กับส่วนของ Paragraph ใน PowerPoint Presentation.

```csharp
[C#]
//สร้างอ็อบเจกต์ Presentation ที่เป็นตัวแทนของไฟล์การนำเสนอ
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides ใช้ตัวระบุพิเศษเหล่านี้ (คล้ายกับที่ใช้ใน PowerPoint):
// +mn-lt - แบบอักษรเนื้อความ Latin (แบบอักษร Latin ย่อย)
// +mj-lt - แบบอักษรหัวเรื่อง Latin (แบบอักษร Latin หลัก)
// +mn-ea - แบบอักษรเนื้อความ East Asian (แบบอักษร East Asian ย่อย)
// +mj-ea - แบบอักษรเนื้อความ East Asian (แบบอักษร East Asian ย่อย)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### ดูเพิ่มเติม

* คลาส [BasePortionFormat](../baseportionformat)
* อินเทอร์เฟซ [IPortionFormat](../iportionformat)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->