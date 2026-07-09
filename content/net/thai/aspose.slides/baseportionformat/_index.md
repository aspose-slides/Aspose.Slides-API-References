---
title: BasePortionFormat
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: คุณสมบัติการจัดรูปแบบส่วนข้อความทั่วไป.
type: docs
weight: 970
url: /th/aspose.slides/baseportionformat/
---
## BasePortionFormat คลาส

Common text portion formatting properties.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาทางเลือก. Read/write String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IPresentationComponent พื้นฐาน. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรสคริปต์ซับซ้อน. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. Read/write [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรเอเชียตะวันออก. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. Read/write [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | คืนค่า properties ของ EffectFormat ของข้อความ. ไม่ได้ใช้การสืบทอด. Read-only [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | คืนค่า หรือกำหนดข้อความซูเปอร์สคริปต์หรือซับสคริปต์. ค่าอยู่ระหว่าง -100% (ซับสคริปต์) ถึง 100% (ซูเปอร์สคริปต์). **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master. Read/write Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | คืนค่า properties ของ FillFormat ของข้อความ. ไม่ได้ใช้การสืบทอด. Read-only [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | กำหนดว่าแบบอักษรเป็นตัวหนาหรือไม่. ไม่ได้ใช้การสืบทอด. Read/write [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | คืนค่า หรือกำหนดความสูงของแบบอักษรของส่วน. **float.NaN** หมายถึงความสูงไม่ได้กำหนดและควรสืบทอดจาก Master. Read/write Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | กำหนดว่าแบบอักษรเป็นตัวเอียงหรือไม่. ไม่ได้ใช้การสืบทอด. Read/write [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | คืนค่า หรือกำหนดประเภทการขีดเส้นใต้ของข้อความ. ไม่ได้ใช้การสืบทอด. Read/write [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | คืนค่าสีที่ใช้เน้นข้อความ. ไม่ได้ใช้การสืบทอด. Read-only [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | กำหนดว่ารูปแบบการขีดเส้นใต้มี properties ของ FillFormat ของตนเองหรือสืบทอดจาก properties ของ FillFormat ของข้อความ. Read/write [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | กำหนดว่ารูปแบบการขีดเส้นใต้มี properties ของ LineFormat ของตนเองหรือสืบทอดจาก properties ของ LineFormat ของข้อความ. Read/write [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | คืนค่า หรือกำหนดขนาดแบบอักษรขั้นต่ำที่ควรเปิดใช้งาน kerning. **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master. Read/write Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | กำหนดว่าตัวเลขควรละเลยการจัดเรียงข้อความแบบแนวตั้งตามภาษาตะวันออกหรือไม่. ไม่ได้ใช้การสืบทอด. Read/write [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | คืนค่า หรือกำหนด Id ของภาษาตรวจสอบ. ใช้เพื่อตรวจสอบการสะกดและไวยากรณ์. Read/write String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรละติน. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. Read/write [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | คืนค่า properties ของ LineFormat สำหรับการรอบขอบข้อความ. ไม่ได้ใช้การสืบทอด. Read-only [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | กำหนดว่าความสูงของข้อความควรทำให้เป็นมาตรฐานหรือไม่. ไม่ได้ใช้การสืบทอด. Read/write [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | กำหนดว่าข้อความไม่ควรตรวจสอบหรือไม่. ไม่ได้ใช้การสืบทอด. Read/write [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | คืนค่า หรือกำหนดการเพิ่มระยะห่างระหว่างอักขระ. **float.NaN** หมายถึงค่าที่ไม่ได้กำหนดและควรสืบทอดจาก Master. Read/write Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | รับหรือกำหนดค่าที่บ่งบอกว่าการตรวจสอบการสะกดเปิดใช้งานสำหรับส่วนของข้อความหรือไม่. เมื่อ property นี้ตั้งเป็น false, การตรวจสอบการสะกดสำหรับองค์ประกอบข้อความจะถูกยกเลิก. เมื่อตั้งเป็น true, การตรวจสอบการสะกดจะอนุญาต. ค่าเริ่มต้นคือ `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | คืนค่า หรือกำหนดประเภทการขีดเส้นผ่านของข้อความ. ไม่ได้ใช้การสืบทอด. Read/write [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | คืนค่า หรือกำหนดข้อมูลแบบอักษรสัญลักษณ์. Null หมายถึงแบบอักษรไม่ได้กำหนดและควรสืบทอดจาก Master. Read/write [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | คืนค่า หรือกำหนดประเภทการใช้ตัวพิมพ์ใหญ่ของข้อความ. ไม่ได้ใช้การสืบทอด. Read/write [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | คืนค่า properties ของ FillFormat สำหรับเส้นขีดเส้นใต้. ไม่ได้ใช้การสืบทอด. Read-only [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | คืนค่า properties ของ LineFormat ที่ใช้รอบขอบเส้นขีดเส้นใต้. ไม่ได้ใช้การสืบทอด. Read-only [`ILineFormat`](../ilineformat). |

## วิธีการ

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | เปรียบเทียบกับอ็อบเจกต์ที่ระบุ. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | คืนค่า hash code. |

### ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject)
* อินเทอร์เฟซ [IBasePortionFormat](../ibaseportionformat)
* เนมส페ส [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->