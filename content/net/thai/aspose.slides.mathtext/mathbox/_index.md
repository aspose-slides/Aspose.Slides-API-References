---
title: MathBox
second_title: Aspose.Sildes สำหรับ .NET API อ้างอิง
description: ระบุการบรรจุเชิงตรรกะขององค์ประกอบทางคณิตศาสตร์ ตัวอย่างเช่น วัตถุที่บรรจุสามารถทำหน้าที่เป็นอีมูเลเตอร์ของโอเปอเรเตอร์ที่มีหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดตัดบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน ตัวอย่างเช่น โอเปอเรเตอร์ ควรจะถูกบรรจุเพื่อป้องกันการตัดบรรทัด
type: docs
weight: 8630
url: /th/aspose.slides.mathtext/mathbox/
---
## คลาส MathBox

ระบุการบรรจุปฏิบัติทำนองตรรกะ (การบรรจุ) ขององค์ประกอบทางคณิตศาสตร์ ตัวอย่างเช่น วัตถุที่บรรจุสามารถทำหน้าที่เป็นอีมูเลเตอร์ของโอเปอเรเตอร์ที่มีหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดตัดบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน ตัวอย่างเช่น โอเปอเรเตอร์ "==" ควรจะถูกบรรจุเพื่อป้องกันการตัดบรรทัด

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## คอนสตรัคเตอร์

| Name | Description |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | เริ่มต้น MathBox ด้วยองค์ประกอบที่ระบุเป็นอาร์กิวเมนต์ |

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | เมื่อเป็นจริง, อีมูเลเตอร์ของโอเปอเรเตอร์นี้ทำหน้าที่เป็นจุดจัดแนว; คือ จุดจัดแนวที่กำหนดในสมการอื่นสามารถจัดแนวกับมันได้ ค่าเริ่มต้น: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | อาร์กิวเมนต์ฐาน |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | ดิฟเฟอเรนเชียล เมื่อเป็นจริง, กล่องทำหน้าที่เป็นดิฟเฟอเรนเชียล (เช่น 𝑑𝑥 ในอินเทเกรนด์) และได้รับการเว้นระยะแนวนอนที่เหมาะสมสำหรับดิฟเฟอเรนเชียลทางคณิตศาสตร์ ค่าเริ่มต้น: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | การแบ่งบรรทัดโดยเจตนาระบุว่ามีการแบ่งบรรทัดที่จุดเริ่มต้นของอ็อบเจ็กต์ Box หรือไม่, เพื่อให้บรรทัดตัดที่จุดเริ่มต้นของอ็อบเจ็กต์กล่อง. ระบุจำนวนของโอเปอเรเตอร์ในบรรทัดก่อนของข้อความคณิตศาสตร์ที่ใช้เป็นจุดจัดแนวสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์ ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการแบ่งบรรทัดโดยเจตนา) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | ไม่มีการแบ่งบรรทัด คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" ของกล่องอ็อบเจ็กต์ เมื่อเป็นจริง, จะไม่มีการแบ่งบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับอีมูเลเตอร์ของโอเปอเรเตอร์ที่ประกอบด้วยโอเปอเรเตอร์ไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุองค์ประกอบนี้, การแบ่งบรรทัดอาจเกิดภายในกล่อง ค่าเริ่มต้น: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | อีมูเลเตอร์ของโอเปอเรเตอร์. เมื่อเป็นจริง, กล่องและเนื้อหาของมันทำงานเป็นโอเปอเรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์ ซึ่งหมายความว่า เช่น ตัวอักษรสามารถทำหน้าที่เป็นจุดสำหรับการแบ่งบรรทัดและสามารถจัดแนวกับโอเปอเรเตอร์อื่นได้ อีมูเลเตอร์ของโอเปอเรเตอร์มักใช้เมื่อ glyph หนึ่งหรือหลายตัวรวมกันเป็นโอเปอเรเตอร์ เช่น '==' ค่าเริ่มต้น: false |

## วิธีการ

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระที่อยู่บนสุดขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างเศษส่วนของประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างเศษส่วนของประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่กำหนด เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | รับอิลิเมนต์ลูก |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่ม เช่น วงเล็บโค้งล่างหรืออักขระอื่น |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างโอเปอเรเตอร์ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างโอเปอเรเตอร์ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งบาร์บนส่วนบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | กำหนดรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | กำหนดรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างตัวล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างตัวล่าง |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวล่างและตัวบนทางด้านซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวล่างและตัวบนทางด้านซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวล่างและตัวบนทางด้านขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวล่างและตัวบนทางด้านขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างตัวบน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างตัวบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่บรรจุสามารถ (เช่น) ทำหน้าที่เป็นอีมูเลเตอร์ของโอเปอเรเตอร์ที่มีหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดแบ่งบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้มีการแบ่งบรรทัดภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | ใส่ในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งบาร์ที่ส่วนล่างขององค์ประกอบนี้ |

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### ดูเพิ่มเติม

* คลาส [MathElementBase](../mathelementbase)
* อินเทอร์เฟซ [IMathBox](../imathbox)
* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->