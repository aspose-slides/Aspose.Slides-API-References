---
title: Hyperlink
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: แสดงถึงไฮเปอร์ลิงก์
type: docs
weight: 5140
url: /th/aspose.slides/hyperlink/
---
## คลาส Hyperlink

แสดงถึงไฮเปอร์ลิงก์หนึ่งรายการ.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์เฉพาะ หมายเหตุ: ไฮเปอร์ลิงก์ที่สร้างควรถูกกำหนดให้กับวัตถุบางอย่างจากการนำเสนอเดียวกัน ไม่เช่นนั้นลิงก์จะถูกบันทึกเป็น NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นแหล่งข้อมูลและแทนที่คุณสมบัติเชิงรอง. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | ส่งกลับไฮเปอร์ลิงก์ที่จบการแสดงผล. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์แรกของการนำเสนอ. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์สุดท้ายของการนำเสนอ. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์ที่ดูล่าสุด. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | ส่งกลับไฮเปอร์ลิงก์พิเศษ "play mediafile". ใช้ใน AudioFrame และ VideoFrame. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์ถัดไป. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | ส่งกลับไฮเปอร์ลิงก์พิเศษ "do nothing". อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์ก่อนหน้า. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | ส่งกลับประเภทของการกระทำของ Hyperlink. อ่านอย่างเดียว [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซฐาน IPresentationComponent. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | แสดงถึงแหล่งที่มาของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน. อ่าน/เขียน [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | ระบุ URL ภายนอก. อ่านอย่างเดียว String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | แสดงถึงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วนนั้น PowerPoint ทำงานเฉพาะสำหรับลิงก์และข้อความที่สอดคล้องกันในส่วน มันอนุญาตให้สร้างข้อความสำหรับไฮเปอร์ลิงก์ในรูปแบบ URL ที่ถูกต้อง ซึ่งแตกต่างจากที่อยู่จริงของลิงก์ ในกรณีนี้เมื่อคุณดูลิงก์ในหน้าต่างแก้ไข มันจะถูกเปลี่ยนให้ตรงกับข้อความส่วนนี้ คุณสมบัตินี้แสดงค่าต้นฉบับของไฮเปอร์ลิงก์. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | กำหนดว่าไฮเปอร์ลิงก์ควรแสดงไฮไลท์เมื่อคลิกหรือไม่. อ่าน/เขียน Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | กำหนดว่าเป้าหมายของไฮเปอร์ลิงก์แม่จะถูกเพิ่มไปยังรายการไฮเปอร์ลิงก์ที่ดูแล้วเมื่อถูกเรียกหรือไม่. อ่าน/เขียน Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | แสดงถึงเสียงที่เล่นของไฮเปอร์ลิงก์. อ่าน/เขียน [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | กำหนดว่าควรหยุดเสียงเมื่อคลิกลิงก์หรือไม่. อ่าน/เขียน Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | ส่งกลับเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของไฮเปอร์ลิงก์แม่เมื่อมีอยู่. อ่าน/เขียน String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | หาก Hyperlink ชี้ไปยังสไลด์เฉพาะจะส่งกลับสไลด์นั้น. อ่านอย่างเดียว [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | ส่งกลับสตริงที่อาจแสดงในอินเทอร์เฟซผู้ใช้เป็นที่เชื่อมโยงกับไฮเปอร์ลิงก์แม่. อ่าน/เขียน String. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | กำหนดว่าตัวอย่าง Hyperlink สองตัวเท่ากันหรือไม่. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | กำหนดว่าตัวอย่าง Hyperlink สองตัวเท่ากันหรือไม่. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะที่เหมาะกับการใช้ในอัลกอริธึมแฮชและโครงสร้างข้อมูลเช่นตารางแฮช. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | ทดสอบไฮเปอร์ลิงก์สองตัวว่ามีค่าเท่ากัน. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | ทดสอบไฮเปอร์ลิงก์สองตัวว่ามีค่าไม่เท่ากัน. |

### ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject)
* อินเทอร์เฟซ [IHyperlink](../ihyperlink)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->