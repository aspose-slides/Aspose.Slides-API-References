---
title: ChartPortionFormat
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ ไม่เหมือน IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.
type: docs
weight: 1430
url: /th/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat คลาส

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ ไม่เหมือนกับ [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | ส่งคืนหรือกำหนด Id ของภาษาทางเลือก อ่าน/เขียน String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IPresentationComponent พื้นฐาน อ่านอย่างเดียว [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลฟอนต์สคริปต์ซับซ้อน ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลฟอนต์เอเชียตะวันออก ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | ส่งคืนคุณสมบัติ EffectFormat ของข้อความ ไม่ใช้การสืบทอด อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | ส่งคืนหรือกำหนดข้อความยกกำลังบนหรือยกกำลังล่าง ค่าตั้งแต่ -100% (ยกกำลังล่าง) ถึง 100% (ยกกำลังบน) **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | ส่งคืนคุณสมบัติ FillFormat ของข้อความ ไม่ใช้การสืบทอด อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่ ไม่ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | ส่งคืนหรือกำหนดความสูงของแบบอักษรของส่วน **float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่ ไม่ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | ส่งคืนหรือกำหนดประเภทการขีดเส้นใต้ของข้อความ ไม่ใช้การสืบทอด อ่าน/เขียน [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | ส่งคืนสีที่ใช้เน้นข้อความ ไม่ใช้การสืบทอด อ่านอย่างเดียว [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจากคุณสมบัติ FillFormat ของข้อความ อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจากคุณสมบัติ LineFormat ของข้อความ อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | ส่งคืนหรือกำหนดขนาดฟอนต์ขั้นต่ำที่ควรเปิดการเคอร์นิง **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | กำหนดว่าตัวเลขควรละเว้นการจัดวางแนวตั้งแบบภาษาตะวันออกของข้อความหรือไม่ ไม่ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | ส่งคืนหรือกำหนด Id ของภาษาตรวจสอบการพิมพ์ ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์ อ่าน/เขียน String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลฟอนต์ละติน ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | ส่งคืนคุณสมบัติ LineFormat สำหรับการขอบข้อความ ไม่ใช้การสืบทอด อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่ ไม่ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | กำหนดว่าข้อความควรไม่ถูกตรวจสอบหรือไม่ ไม่ใช้การสืบทอด อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | ส่งคืนหรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | รับหรือกำหนดค่าที่บ่งบอกว่าการตรวจสอบการสะกดได้เปิดใช้สำหรับส่วนของข้อความหรือไม่ เมื่อคุณสมบัตินี้ตั้งค่าเป็น false การตรวจสอบการสะกดขององค์ประกอบข้อความจะถูกระงับ เมื่อตั้งค่าเป็น true จะอนุญาตให้ตรวจสอบการสะกด ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | ส่งคืนหรือกำหนดประเภทการขีดเส้นพาดของข้อความ ไม่ใช้การสืบทอด อ่าน/เขียน [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลฟอนต์สัญลักษณ์ ค่าที่เป็น Null หมายถึงฟอนต์ไม่ได้กำหนดและควรสืบทอดจาก Master อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | ส่งคืนหรือกำหนดประเภทของการใช้ตัวพิมพ์ใหญ่ในข้อความ ไม่ใช้การสืบทอด อ่าน/เขียน [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | ส่งคืนคุณสมบัติ FillFormat ของเส้นขีดใต้ ไม่ใช้การสืบทอด อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | ส่งคืนคุณสมบัติ LineFormat ที่ใช้ขอบเส้นขีดใต้ ไม่ใช้การสืบทอด อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | ส่งคืนค่าแฮชโค้ด. |

### หมายเหตุ

คลาสนี้ใช้สำหรับส่งคืนและจัดการคุณสมบัติการจัดรูปแบบส่วนของข้อความที่กำหนดสำหรับส่วนเฉพาะ หมายความว่าไม่มีการสืบทอดเมื่อดึงค่าจึงในกรณีส่วนใหญ่คุณจะได้ค่าแสดงว่า "ไม่ได้กำหนด".

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณต้องใช้เมธอด [`GetEffective`](../../aspose.slides/portionformat/geteffective) ซึ่งส่งคืนอินสแตนซ์ [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### ดูเพิ่มเติม

* คลาส [BasePortionFormat](../../aspose.slides/baseportionformat)
* อินเทอร์เฟซ [IChartPortionFormat](../ichartportionformat)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->