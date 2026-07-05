---
title: PortionFormat
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ. แตกต่างจาก IPortionFormatEffectiveData./iportionformateffectivedata คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 9490
url: /th/aspose.slides/portionformat/
---
## PortionFormat คลาส

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ. ต่างจาก [`IPortionFormatEffectiveData`](../iportionformateffectivedata), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [PortionFormat](portionformat)() | เริ่มต้นอินสแตนซ์ใหม่ของ [`PortionFormat`](../portionformat) คลาส. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาทดแทน. อ่าน-เขียน String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อำนญาตให้รับอินเทอร์เฟซ IPPresentationComponent พื้นฐาน. อ่าน-อย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | คืนค่า หรือกำหนดตัวระบุบุ๊คมาร์ก. อ่าน-เขียน String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลฟอนต์สคริปต์ซับซ้อน. Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน-เขียน [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลฟอนต์เอเชียตะวันออก. Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน-เขียน [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | คืนค่าคุณสมบัติ EffectFormat ของข้อความ. ไม่มีการสืบทอด. อ่าน-อย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | คืนค่า หรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน-เขียน Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของข้อความ. ไม่มีการสืบทอด. อ่าน-อย่างเดียว [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | กำหนดว่าฟอนต์เป็นตัวหนา หรือไม่. ไม่มีการสืบทอด. อ่าน-เขียน [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | คืนค่า หรือกำหนดความสูงฟอนต์ของส่วน. **float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน-เขียน Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | กำหนดว่าฟอนต์เป็นอิตาลิก หรือไม่. ไม่มีการสืบทอด. อ่าน-เขียน [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่มีการสืบทอด. อ่าน-เขียน [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | คืนค่าสีที่ใช้ในการไฮไลท์ข้อความ. ไม่มีการสืบทอด. อ่าน-อย่างเดียว [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน-เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | ผู้จัดการไฮเปอร์ลิงก์. อ่าน-อย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการชี้เมาส์. อ่าน-เขียน [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ. อ่าน-เขียน [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ. อ่าน-เขียน [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | คืนค่า หรือกำหนดขนาดฟอนต์ขั้นต่ำที่ควรเปิด kerning. **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน-เขียน Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | กำหนดว่าตัวเลขควรละเว้นการจัดวางข้อความแนวตั้งตามภาษาตะวันออกของข้อความหรือไม่. ไม่มีการสืบทอด. อ่าน-เขียน [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาตรวจสอบ. ใช้สำหรับการตรวจสอบการสะกดและไวยากรณ์. อ่าน-เขียน String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลฟอนต์ละติน. Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน-เขียน [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | คืนค่าคุณสมบัติ LineFormat สำหรับการรอบขอบข้อความ. ไม่มีการสืบทอด. อ่าน-อย่างเดียว [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่มีการสืบทอด. อ่าน-เขียน [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่. ไม่มีการสืบทอด. อ่าน-เขียน [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | กำหนดว่าตารางอัจฉริยะควรถูกทำความสะอาดหรือไม่. ไม่มีการสืบทอด. อ่าน-เขียน Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | คืนค่า หรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน-เขียน Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | รับหรือกำหนดค่าที่บ่งชี้ว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกปิด. เมื่อตั้งเป็น true จะอนุญาตการตรวจสอบการสะกด. ค่าปริยายคือ `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | คืนค่า หรือกำหนดประเภทการขีดเส้นผ่านของข้อความ. ไม่มีการสืบทอด. อ่าน-เขียน [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลฟอนต์สัญลักษณ์. Null หมายถึงฟอนต์ไม่มีการกำหนดและควรสืบทอดจาก Master. อ่าน-เขียน [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | คืนค่า หรือกำหนดประเภทการขึ้น capital ของข้อความ. ไม่มีการสืบทอด. อ่าน-เขียน [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | คืนค่าคุณสมบัติ FillFormat ของเส้นขีดเส้นใต้. ไม่มีการสืบทอด. อ่าน-อย่างเดียว [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | คืนค่าคุณสมบัติ LineFormat ที่ใช้รอบขอบเส้นขีดเส้นใต้. ไม่มีการสืบทอด. อ่าน-อย่างเดียว [`ILineFormat`](../ilineformat). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | รับข้อมูลการจัดรูปแบบส่วนที่มีผลรวมถึงการสืบทอดที่ใช้. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | คืนค่า hash code. |

### หมายเหตุ

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดสำหรับส่วนเฉพาะ. นั่นหมายความว่าไม่มีการสืบทอดเมื่อรับค่า ดังนั้นในกรณีส่วนใหญ่คุณจะได้ค่าที่หมายถึง “ไม่มีการกำหนด”.

เพื่อรับค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงการสืบทอด คุณต้องใช้เมธอด [`GetEffective`](./geteffective) ซึ่งคืนค่าอินสแตนซ์ของ [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการกำหนดฟอนต์ละตินให้กับส่วนของ Paragraph ใน PowerPoint Presentation.

```csharp
[C#]
//สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์การนำเสนอ
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides ใช้ตัวระบุพิเศษเหล่านี้ (คล้ายกับที่ใช้ใน PowerPoint):
// +mn-lt - ฟอนต์ลาตินของส่วนเนื้อหา (ฟอนต์ละตินย่อย)
// +mj-lt - ฟอนต์หัวเรื่องละติน (ฟอนต์ละตินหลัก)
// +mn-ea - ฟอนต์เอเชียตะวันออกของส่วนเนื้อหา (ฟอนต์เอเชียตะวันออกย่อย)
// +mj-ea - ฟอนต์เอเชียตะวันออกของส่วนเนื้อหา (ฟอนต์เอเชียตะวันออกย่อย)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### ดูเพิ่มเติม

* คลาส [BasePortionFormat](../baseportionformat)
* อินเทอร์เฟซ [IPortionFormat](../iportionformat)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->