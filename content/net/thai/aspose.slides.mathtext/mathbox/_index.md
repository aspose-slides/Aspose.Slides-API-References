---
title: MathBox
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: ระบุการบรรจุบ็อกซ์เชิงตรรกะขององค์ประกอบทางคณิตศาสตร์ ตัวอย่างเช่น วัตถุที่ถูกบ็อกซ์สามารถทำหน้าที่เป็นอิมูเลเตอร์ของตัวดำเนินการที่มีหรือไม่มีจุดจัดตำแหน่ง ทำหน้าที่เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน ตัวอย่างเช่น ตัวดำเนินการควรถูกบ็อกซ์เพื่อป้องกันการตัดบรรทัด
type: docs
weight: 8650
url: /th/aspose.slides.mathtext/mathbox/
---
## คลาส MathBox

ระบุการบ็อกซ์ (แพคเกจ) เชิงตรรกะขององค์ประกอบทางคณิตศาสตร์ ตัวอย่างเช่น วัตถุที่ถูกบ็อกซ์สามารถทำหน้าที่เป็นอิมูเลเตอร์ของตัวดำเนินการที่มีหรือไม่มีจุดจัดตำแหน่ง ทำหน้าที่เป็นจุดตัดบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน ตัวอย่างเช่น ตัวดำเนินการ "==" ควรจะถูกบ็อกซ์เพื่อป้องกันการตัดบรรทัด

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | เริ่มต้น MathBox ด้วยองค์ประกอบที่ระบุเป็นอาร์กิวเมนต์ |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | เมื่อเป็นจริง, อิมูเลเตอร์ของตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดตำแหน่ง; กล่าวคือ จุดจัดตำแหน่งที่กำหนดในสมการอื่นสามารถจัดตำแหน่งกับมันได้ ค่าเริ่มต้น: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | อาร์กิวเมนต์ฐาน |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential เมื่อเป็นจริง, กล่องทำหน้าที่เป็นดิฟเฟอเรนเชียล (เช่น 𝑑𝑥 ในอินทิกรัล), และได้รับช่องว่างแนวนอนที่เหมาะสมสำหรับดิฟเฟอเรนเชียลทางคณิตศาสตร์ ค่าเริ่มต้น: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่, ซึ่งทำให้บรรทัดหักที่จุดเริ่มต้นของวัตถุบ็อกซ์ ระบุจำนวนของตัวดำเนินการในบรรทัดก่อนหน้าของข้อความคณิตศาสตร์ที่จะใช้เป็นจุดจัดตำแหน่งสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์ ค่าได้ที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดแบบชัดเจน) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ เมื่อเป็นจริง, จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับอิมูเลเตอร์ของตัวดำเนินการที่ประกอบด้วยตัวดำเนินการไบนารีมากกว่าหนึ่ง เมื่อองค์ประกอบนี้ไม่ได้ระบุ, การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. เมื่อเป็นจริง, กล่องและเนื้อหาภายในทำงานเหมือนตัวดำเนินการเดียวและสืบทอดคุณสมบัติของตัวดำเนินการ ซึ่งหมายความว่า, ตัวอักษรอาจทำหน้าที่เป็นจุดตัดบรรทัดและสามารถจัดตำแหน่งกับตัวดำเนินการอื่นได้ อิมูเลเตอร์ของตัวดำเนินการมักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็นตัวดำเนินการ เช่น '==' ค่าเริ่มต้น: false |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระที่ด้านบนขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างเศษส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างเศษส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | รับองค์ประกอบลูก |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บโค้งล่างหรืออักขระอื่น |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งบาร์บนด้านบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างตัวห้อย |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างตัวห้อย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวบวกบนด้านซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวห้อยและตัวบวกบนด้านซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวบวกบนด้านขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวห้อยและตัวบวกบนด้านขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างตัวบวกบน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างตัวบวกบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่ถูกบ็อกซ์สามารถ (เช่น) ทำหน้าที่เป็นอิมูเลเตอร์ของตัวดำเนินการที่มีหรือไม่มีจุดจัดตำแหน่ง, ทำหน้าที่เป็นจุดตัดบรรทัด, หรือถูกจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | วางในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |

### ตัวอย่าง

Example:

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