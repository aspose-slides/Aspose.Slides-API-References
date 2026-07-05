---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: อินเทอร์เฟซพื้นฐานสำหรับอ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผล
type: docs
weight: 5320
url: /th/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData อินเทอร์เฟซ

Base interface for immutable objects which contain effective text portion formatting properties.

```csharp
public interface IBasePortionFormatEffectiveData
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | คืนค่า Id ของภาษาทางเลือก. อ่านอย่างเดียว String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | คืนค่าข้อมูลฟอนต์สำหรับสคริปต์ซับซ้อน. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | คืนค่าข้อมูลฟอนต์เอเชียตะวันออก. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | คืนค่า properties ของ EffectFormat ของข้อความ. อ่านอย่างเดียว [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | คืนค่าข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). อ่านอย่างเดียว Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | คืนค่า properties ของ FillFormat ของข้อความ. อ่านอย่างเดียว [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | ระบุว่าแบบอักษรเป็นตัวหนาหรือไม่. อ่านอย่างเดียว Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | คืนค่าความสูงของแบบอักษรของส่วนข้อความ, หน่วยเป็นจุด. อ่านอย่างเดียว Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | ระบุว่าแบบอักษรเป็นอิตาลิกหรือไม่. อ่านอย่างเดียว Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | คืนค่าประเภทการขีดเส้นใต้ของข้อความ. อ่านอย่างเดียว [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | คืนค่าสีที่ใช้ไฮไลต์ข้อความ. อ่านอย่างเดียว Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | ระบุว่าสไตล์การขีดเส้นใต้มี properties FillFormat ของตนเองหรือสืบทอดจาก properties FillFormat ของข้อความ. อ่านอย่างเดียว Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | ระบุว่าสไตล์การขีดเส้นใต้มี properties LineFormat ของตนเองหรือสืบทอดจาก properties LineFormat ของข้อความ. อ่านอย่างเดียว Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | คืนค่าขนาดแบบอักษรขั้นต่ำที่ต้องเปิดใช้ kerning. อ่านอย่างเดียว Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | ระบุว่าตัวเลขควรละเว้นการจัดวางแนวตั้งของข้อความตามภาษาตะวันออกของข้อความหรือไม่. อ่านอย่างเดียว Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | คืนค่า Id ของภาษาหนึ่ง. อ่านอย่างเดียว String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | คืนค่าข้อมูลฟอนต์ละติน. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | คืนค่า properties ของ LineFormat สำหรับการขอบข้อความ. อ่านอย่างเดียว [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | ระบุว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. อ่านอย่างเดียว Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | ระบุว่าข้อความไม่ควรตรวจสอบการสะกดหรือไม่. อ่านอย่างเดียว Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | ระบุว่าต้องทำความสะอาด smart tag หรือไม่. อ่านอย่างเดียว Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | คืนค่าการเพิ่มระยะห่างระหว่างอักขระ, หน่วยเป็นจุด. อ่านอย่างเดียว Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | คืนค่าประเภทการขีดฆ่าของข้อความ. อ่านอย่างเดียว [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | คืนค่าข้อมูลฟอนต์เชิงสัญลักษณ์. อ่านอย่างเดียว [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | คืนค่าประเภทของการใช้ตัวพิมพ์ใหญ่ในข้อความ. อ่านอย่างเดียว [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | คืนค่า properties ของ FillFormat ของเส้นขีดเส้นใต้. อ่านอย่างเดียว [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | คืนค่า properties ของ LineFormat ที่ใช้ขอบเส้นขีดเส้นใต้. อ่านอย่างเดียว [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->