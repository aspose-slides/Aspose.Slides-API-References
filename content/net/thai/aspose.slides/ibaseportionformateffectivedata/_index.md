---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes สำหรับอ้างอิง API ของ .NET
description: อินเทอร์เฟซพื้นฐานสำหรับอ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงได้ซึ่งประกอบด้วยคุณลักษณะการจัดรูปแบบส่วนข้อความที่มีผล
type: docs
weight: 5320
url: /th/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData อินเทอร์เฟซ

อินเทอร์เฟซพื้นฐานสำหรับอ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงได้ซึ่งมีคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผล

```csharp
public interface IBasePortionFormatEffectiveData
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | คืนค่า Id ของภาษาทางเลือก. อ่านอย่างเดียว String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | คืนข้อมูลฟอนต์สคริปต์ซับซ้อน. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | คืนข้อมูลฟอนต์เอเชียตะวันออก. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | คืนคุณสมบัติ EffectFormat ของข้อความ. อ่านอย่างเดียว [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | คืนข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าตั้งแต่ -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). อ่านอย่างเดียว Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | คืนคุณสมบัติ FillFormat ของข้อความ. อ่านอย่างเดียว [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. อ่านอย่างเดียว Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | คืนความสูงของแบบอักษรในส่วนข้อความ หน่วยเป็นพอยต์. อ่านอย่างเดียว Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | กำหนดว่าแบบอักษรเป็นอิตาลิกหรือไม่. อ่านอย่างเดียว Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | คืนประเภทการขีดเส้นใต้ของข้อความ. อ่านอย่างเดียว [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | คืนสีที่ใช้ไฮไลต์ข้อความ. อ่านอย่างเดียว Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ. อ่านอย่างเดียว Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ. อ่านอย่างเดียว Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | คืนขนาดฟอนต์ขั้นต่ำที่ควรเปิดการเคอร์นิง. อ่านอย่างเดียว Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | กำหนดว่าตัวเลขควรละเลยการจัดแนวข้อความตั้งฉากที่เฉพาะเจาะจงต่อภาษาในเอเชียตะวันออกหรือไม่. อ่านอย่างเดียว Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | คืนค่า Id ของภาษา. อ่านอย่างเดียว String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | คืนข้อมูลฟอนต์ละติน. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | คืนคุณสมบัติ LineFormat สำหรับการทำ outlines ของข้อความ. อ่านอย่างเดียว [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | กำหนดว่าความสูงของข้อความควรถูกทำให้เป็นมาตรฐานหรือไม่. อ่านอย่างเดียว Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | กำหนดว่าข้อความไม่ควรตรวจสอบการสะกดหรือไม่. อ่านอย่างเดียว Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | กำหนดว่า smart tag ควรถูกล้างหรือไม่. อ่านอย่างเดียว Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | คืนการเพิ่มระยะห่างระหว่างอักขระ หน่วยเป็นพอยต์. อ่านอย่างเดียว Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | คืนประเภทการขีดฆ่าในข้อความ. อ่านอย่างเดียว [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | คืนข้อมูลฟอนต์สัญลักษณ์. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | คืนประเภทการใช้ตัวพิมพ์ใหญ่ในข้อความ. อ่านอย่างเดียว [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | คืนคุณสมบัติ FillFormat ของเส้นขีดเส้นใต้. อ่านอย่างเดียว [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | คืนคุณสมบัติ LineFormat ที่ใช้ในการทำ outlines ของเส้นขีดเส้นใต้. อ่านอย่างเดียว [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### ดูเพิ่มเติม

* ชื่อเนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->