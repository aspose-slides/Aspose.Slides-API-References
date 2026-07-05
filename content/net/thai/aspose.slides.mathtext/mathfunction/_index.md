---
title: MathFunction
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: ระบุฟังก์ชันของอาร์กิวเมนต์หนึ่ง.
type: docs
weight: 8720
url: /th/aspose.slides.mathtext/mathfunction/
---
## คลาส MathFunction

ระบุฟังก์ชันของอาร์กิวเมนต์หนึ่ง

```csharp
public sealed class MathFunction : MathElementBase, IMathFunction
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathFunction](mathfunction#constructor)(IMathElement, IMathElement) | สร้างอินสแตนซ์ใหม่ของคลาส MathFunction |
| [MathFunction](mathfunction#constructor_1)(string, IMathElement) | สร้างอินสแตนซ์ใหม่ของคลาส MathFunction |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathfunction/base) { get; } | อาร์กิวเมนต์ของฟังก์ชัน |
| [Name](../../aspose.slides.mathtext/mathfunction/name) { get; } | ชื่อฟังก์ชัน ตัวอย่างเช่น ชื่อฟังก์ชันได้แก่ sin และ cos |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระที่ด้านบนขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathfunction/getchildren)() | รับองค์ประกอบลูก |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่ม เช่น วงเล็บโค้งล่างหรืออื่น |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบจำกัด |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งแถบที่ด้านบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขีดจำกัดล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขีดจำกัดล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างตัวห้อย |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างตัวห้อย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวยกบนด้านซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวห้อยและตัวยกบนด้านซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวยกบนด้านขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวห้อยและตัวยกบนด้านขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างตัวยกบน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างตัวยกบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขีดจำกัดบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขีดจำกัดบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกล่องกรอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องกรอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่เป็นภาพ (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุในกล่องอาจใช้เป็นจำลองตัวดำเนินการโดยมีหรือไม่มีจุดจัดแนว ใช้เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้อักขระตัดบรรทัดภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | ใส่ในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งแถบที่ด้านล่างขององค์ประกอบนี้ |

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
MathFunction func = new MathFunction("sin", new MathematicalText("x"));
```

### ดูเพิ่มเติม

* คลาส [MathElementBase](../mathelementbase)
* อินเทอร์เฟซ [IMathFunction](../imathfunction)
* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->