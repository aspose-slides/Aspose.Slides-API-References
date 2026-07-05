---
title: Hyperlink
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงไฮเปอร์ลิงก์.
type: docs
weight: 5120
url: /th/aspose.slides/hyperlink/
---
## คลาส Hyperlink

แสดงถึงไฮเปอร์ลิงก์

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์เฉพาะ หมายเหตุ: ไฮเปอร์ลิงก์ที่สร้างควรถูกกำหนดให้กับอ็อบเจ็กต์จากงานนำเสนอเดียวกัน มิฉะนั้นลิงก์จะถูกบันทึกเป็น NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นแหล่งที่มาและแทนที่คุณสมบัติรอง. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | คืนค่าไฮเปอร์ลิงก์ที่สิ้นสุดการแสดง. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์แรกของงานนำเสนอ. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์สุดท้ายของงานนำเสนอ. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์ที่ดูล่าสุด. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | คืนค่าไฮเปอร์ลิงก์พิเศษ "play mediafile". ใช้ใน AudioFrame และ VideoFrame. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์ถัดไป. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | คืนค่าไฮเปอร์ลิงก์พิเศษ "do nothing". อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | คืนค่าไฮเปอร์ลิงก์ไปยังสไลด์ก่อนหน้า. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | คืนค่าประเภทของการกระทำของ Hyperlink. อ่านอย่างเดียว [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซฐาน IPresentationComponent. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | แสดงแหล่งที่มาของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน. อ่าน/เขียน [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | ระบุ URL ภายนอก. อ่านอย่างเดียว String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | แสดงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาแท้จริงของส่วนนั้น PowerPoint มีการทำงานเฉพาะสำหรับลิงก์และข้อความที่สอดคล้องในส่วนนั้น มันอนุญาตให้สร้างข้อความสำหรับไฮเปอร์ลิงก์ในรูปแบบ URL ที่ถูกต้องซึ่งแตกต่างจากที่อยู่จริงของลิงก์ ในกรณีนี้ เมื่อคุณดูลิงก์ในหน้าต่างแก้ไข จะถูกเปลี่ยนให้ตรงกับข้อความของส่วนนี้ คุณสมบัตินี้แทนค่าต้นฉบับของไฮเปอร์ลิงก์. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | กำหนดว่าไฮเปอร์ลิงก์ควรเน้นเมื่อคลิกหรือไม่. อ่าน/เขียน Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | กำหนดว่าเป้าหมายของไฮเปอร์ลิงก์หลักจะถูกเพิ่มไปยังรายการไฮเปอร์ลิงก์ที่ดูแล้วเมื่อถูกเรียกหรือไม่. อ่าน/เขียน Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | แสดงเสียงที่เล่นของไฮเปอร์ลิงก์. อ่าน/เขียน [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. อ่าน/เขียน Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | คืนค่าเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของไฮเปอร์ลิงก์หลักเมื่อมีอยู่. อ่าน/เขียน String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | หาก Hyperlink ชี้ไปยังสไลด์เฉพาะจะคืนค่าสไลด์นั้น. อ่านอย่างเดียว [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | คืนค่าสตริงที่อาจแสดงในอินเทอร์เฟซผู้ใช้เป็นข้อมูลที่เชื่อมโยงกับไฮเปอร์ลิงก์หลัก. อ่าน/เขียน String. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | กำหนดว่าตัวอย่าง Hyperlink สองอันเท่ากันหรือไม่. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | กำหนดว่าตัวอย่าง Hyperlink สองอันเท่ากันหรือไม่. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดที่ระบุ เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่นตารางแฮช. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | ทดสอบไฮเปอร์ลิงก์สองอันเพื่อความเท่าเทียม. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | ทดสอบไฮเปอร์ลิงก์สองอันเพื่อความไม่เท่าเทียม. |

### ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject)
* อินเทอร์เฟซ [IHyperlink](../ihyperlink)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->