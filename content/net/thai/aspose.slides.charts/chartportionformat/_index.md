---
title: ChartPortionFormat
second_title: Aspose.Sildes สำหรับ .NET API อ้างอิง
description: คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ ต่างจาก IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata ทุกคุณสมบัติของคลาสนี้สามารถเขียนได้
type: docs
weight: 1440
url: /th/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat คลาส

คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ ต่างจาก [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) ทุกคุณสมบัติของคลาสนี้สามารถเขียนได้

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาทางเลือก อ่าน/เขียน String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IPresentationComponent พื้นฐาน อ่านอย่างเดียว [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | คืนค่า คุณสมบัติ EffectFormat ของข้อความ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | คืนค่า หรือกำหนดข้อความตัวเอี้ยวล่างหรือบน ค่าอยู่ระหว่าง -100% (ตัวเอี้ยวล่าง) ถึง 100% (ตัวเอี้ยวบน) **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | คืนค่า คุณสมบัติ FillFormat ของข้อความ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | กำหนดว่าฟอนต์เป็นตัวหนาหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | คืนค่า หรือกำหนดความสูงฟอนต์ของส่วน **float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | กำหนดว่าฟอนต์เป็นตัวเอียงหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | คืนค่าสีที่ใช้ไฮไลท์ข้อความ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | กำหนดว่ารูปแบบการขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | คืนค่า หรือกำหนดขนาดฟอนต์ต่ำสุดที่ควรเปิดใช้งานการเคอร์นิ่ง **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | กำหนดว่าตัวเลขควรละเว้นการจัดวางข้อความตามภาษาตะวันออกของข้อความหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาการตรวจสอบการสะกด ใช้สำหรับตรวจการสะกดและไวยากรณ์ อ่าน/เขียน String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรละติน Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | คืนค่า คุณสมบัติ LineFormat สำหรับการวางขอบข้อความ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | กำหนดว่าข้อความไม่ควรถูกตรวจสอบหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | คืนค่า หรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | รับหรือกำหนดค่าสบ่งว่าตรวจการสะกดถูกเปิดใช้งานสำหรับส่วนข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกยกเลิก เมื่อตั้งค่าเป็น true การตรวจสอบการสะกดจะได้รับอนุญาต ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | คืนค่า หรือกำหนดประเภทการขีดเส้นผ่านของข้อความ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรสัญลักษณ์ Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | คืนค่า หรือกำหนดประเภทการพิมพ์ใหญ่ของข้อความ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | คืนค่า คุณสมบัติ FillFormat ของเส้นขีดใต้วางเส้น ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | คืนค่า คุณสมบัติ LineFormat ที่ใช้เพื่อวางขอบเส้นขีดใต้ ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับออบเจ็กต์ที่กำหนด |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | คืนค่า hash code |

### หมายเหตุ

คลาสนี้ใช้ในการคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนของข้อความที่กำหนดสำหรับส่วนเฉพาะหมายความว่าไม่ใช้การสืบทอดเมื่อรับค่า ดังนั้นในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง "undefined"

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงค่าที่สืบทอด คุณต้องใช้เมธอด [`GetEffective`](../../aspose.slides/portionformat/geteffective) ซึ่งคืนค่าอินสแตนซ์ของ [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)

### ดูเพิ่มเติม

* คลาส [BasePortionFormat](../../aspose.slides/baseportionformat)
* อินเทอร์เฟซ [IChartPortionFormat](../ichartportionformat)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->