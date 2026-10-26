---
title: ChartPortionFormat
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ. แตกต่างจาก IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata ทุกคุณสมบัติของคลาสนี้สามารถเขียนได้.
type: docs
weight: 1430
url: /th/aspose.slides.charts/chartportionformat/
---
## คลาส ChartPortionFormat

คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบส่วนของแผนภูมิที่ใช้ในแผนภูมิ. แตกต่างจาก [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), ทุกคุณสมบัติของคลาสนี้สามารถเขียนได้.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | ส่งคืนหรือกำหนด Id ของภาษาทางเลือก. อ่าน/เขียน String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IPresentationComponent พื้นฐาน. อ่านอย่างเดียว [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลแบบอักษร East Asian. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | ส่งคืนคุณสมบัติ EffectFormat ของข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | ส่งคืนหรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | ส่งคืนคุณสมบัติ FillFormat ของข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | ส่งคืนหรือกำหนดความสูงของแบบอักษรของส่วน. **float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | กำหนดว่าแบบอักษรเป็น Italic หรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | ส่งคืนหรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | ส่งคืนสีที่ใช้เน้นข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ FillFormat ของตนเองหรือสืบทอดจาก FillFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | กำหนดว่ารูปแบบขีดเส้นใต้มีคุณสมบัติ LineFormat ของตนเองหรือสืบทอดจาก LineFormat ของข้อความ. อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | ส่งคืนหรือกำหนดขนาดแบบอักษรขั้นต่ำที่ควรเปิดการเคอร์นิง. **float.NaN** หมายถึงค่ไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | กำหนดว่าตัวเลขควรมองข้ามการจัดวางข้อความแนวตั้งที่เฉพาะสำหรับภาษาตะวันออกของข้อความหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | ส่งคืนหรือกำหนด Id ของภาษาการพิสูจน์. ใช้สำหรับตรวจสอบการสะกดและไวยากรณ์. อ่าน/เขียน String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลแบบอักษร Latin. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | ส่งคืนคุณสมบัติ LineFormat สำหรับการออกกรอบข้อความ. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | กำหนดว่าข้อความไม่ควรได้รับการพิสูจน์หรือไม่. ไม่ใช้การสืบทอด. อ่าน/เขียน [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | ส่งคืนหรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. **float.NaN** หมายถึงค่าไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | รับหรือกำหนดค่าที่บ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. เมื่อคุณสมบัตินี้ตั้งค่าเป็น false, การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกปิด. เมื่อตั้งค่าเป็น true, การตรวจสอบการสะกดจะได้รับอนุญาต. ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | ส่งคืนหรือกำหนดประเภทการขีดฆ่าของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | ส่งคืนหรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. อ่าน/เขียน [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | ส่งคืนหรือกำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ. ไม่ใช้การสืบทอด. อ่าน/เขียน [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | ส่งคืนคุณสมบัติ FillFormat ของเส้นขีดเส้นใต้อ้างอิง. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | ส่งคืนคุณสมบัติ LineFormat ที่ใช้ในการวางกรอบเส้นขีดเส้นใต้. ไม่ใช้การสืบทอด. อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับวัตถุที่ระบุ. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | ส่งคืนรหัสแฮช. |

### หมายเหตุ

คลาสนี้ใช้เพื่อส่งคืนและจัดการคุณสมบัติการจัดรูปแบบส่วนของข้อความที่กำหนดสำหรับส่วนเฉพาะ. สิ่งนี้หมายความว่าการสืบทอดไม่ได้ถูกนำมาใช้เมื่อดึงค่าต่าง ๆ ดังนั้นในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง "undefined".

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงค่าที่สืบทอด คุณต้องใช้วิธี [`GetEffective`](../../aspose.slides/portionformat/geteffective) ซึ่งส่งคืนอินสแตนซ์ [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### ดูเพิ่มเติม

* คลาส [BasePortionFormat](../../aspose.slides/baseportionformat)
* อินเทอร์เฟซ [IChartPortionFormat](../ichartportionformat)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->