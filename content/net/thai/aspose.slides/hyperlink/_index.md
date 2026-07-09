---
title: Hyperlink
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
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
| [Hyperlink](hyperlink#constructor_1)(ISlide) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์เฉพาะ. หมายเหตุ: ไฮเปอร์ลิงก์ที่สร้างควรถูกกำหนดให้กับวัตถุบางอย่างจากการนำเสนอเดียวกัน, มิฉะนั้นลิงก์จะถูกบันทึกเป็น NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นแหล่งที่มา, เขียนทับคุณสมบัติรอง. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | ส่งคืนไฮเปอร์ลิงก์ที่จบการแสดง. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์แรกของการนำเสนอ. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์สุดท้ายของการนำเสนอ. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์ที่ดูครั้งสุดท้าย. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | ส่งคืนไฮเปอร์ลิงก์พิเศษ "play mediafile". ใช้ใน AudioFrame และ VideoFrame. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์ถัดไป. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | ส่งคืนไฮเปอร์ลิงก์พิเศษ "do nothing". อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์ก่อนหน้า. อ่านอย่างเดียว [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | ส่งคืนประเภทของการกระทำของ Hyperlink. อ่านอย่างเดียว [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IPresentationComponent พื้นฐาน. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | แสดงถึงแหล่งสีของไฮเปอร์ลิงก์ - ทั้งจากสไตล์หรือรูปแบบส่วน. อ่านเขียน [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | ระบุ URL ภายนอก. อ่านอย่างเดียว String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | แสดงถึงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วนนั้น. PowerPoint มีพฤติกรรมพิเศษสำหรับลิงก์และข้อความที่สอดคล้องในส่วน. มันอนุญาตให้สร้างข้อความสำหรับไฮเปอร์ลิงก์ในรูปแบบ URL ที่ถูกต้อง, ซึ่งแตกต่างจากที่อยู่จริงของลิงก์. ในกรณีนี้, เมื่อคุณดูลิงก์ในหน้าต่างแก้ไข, จะถูกเปลี่ยนให้ตรงกับส่วนข้อความ. คุณสมบัตินี้แสดงค่าต้นฉบับของไฮเปอร์ลิงก์. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลต์เมื่อคลิกหรือไม่. อ่านเขียน Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | กำหนดว่าเป้าหมายของไฮเปอร์ลิงก์พ่อแม่จะถูกเพิ่มในรายการของไฮเปอร์ลิงก์ที่ดูแล้วเมื่อถูกเรียกหรือไม่. อ่านเขียน Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | แสดงถึงเสียงที่เล่นของไฮเปอร์ลิงก์. อ่านเขียน [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | กำหนดว่าควรหยุดเสียงเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. อ่านเขียน Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | ส่งคืนเฟรมภายในชุดเฟรม HTML ของพ่อแม่สำหรับเป้าหมายของไฮเปอร์ลิงก์พ่อแม่เมื่อมีอยู่. อ่าน/เขียน String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | หาก Hyperlink ชี้ไปยังสไลด์เฉพาะจะส่งคืนสไลด์นั้น. อ่านอย่างเดียว [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | ส่งคืนสตริงที่อาจปรากฏในส่วนติดต่อผู้ใช้ที่เชื่อมโยงกับไฮเปอร์ลิงก์พ่อแม่. อ่านเขียน String. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | กำหนดว่าตัวอย่าง Hyperlink สองตัวเท่ากันหรือไม่. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | กำหนดว่าตัวอย่าง Hyperlink สองตัวเท่ากันหรือไม่. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดใดชนิดหนึ่ง, เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | ทดสอบว่าไฮเปอร์ลิงก์สองตัวเท่ากันหรือไม่. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | ทดสอบว่าไฮเปอร์ลิงก์สองตัวไม่เท่ากัน. |

### ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject)
* อินเทอร์เฟซ [IHyperlink](../ihyperlink)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->