---
title: MathBar
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: กำหนดฟังก์ชันบาร์ที่ประกอบด้วยอาร์กิวเมนต์ฐานและบาร์เหนือหรือบาร์ล่าง
type: docs
weight: 8570
url: /th/aspose.slides.mathtext/mathbar/
---
## MathBar คลาส

กำหนดฟังก์ชันบาร์ ซึ่งประกอบด้วยอาร์กิวเมนต์ฐานและบาร์เหนือหรือบาร์ล่าง

```csharp
public sealed class MathBar : MathElementBase, IMathBar
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathBar](mathbar#constructor)(IMathElement) | เริ่มต้น MathBar ด้วยบาร์เหนือ (ตำแหน่งบน) |
| [MathBar](mathbar#constructor_1)(IMathElement, MathTopBotPositions) | เริ่มต้น MathBar ด้วยตำแหน่งที่กำหนด |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathbar/base) { get; } | อาร์กิวเมนต์ฐาน |
| [Position](../../aspose.slides.mathtext/mathbar/position) { get; set; } | ตำแหน่งของเส้นบาร์ ค่าเริ่มต้น: บน |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
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
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุเช่นวงเล็บหรืออักขระอื่นเป็นกรอบ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathbar/getchildren)() | ดึงองค์ประกอบลูก |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่มเช่นวงเล็บปีกกาล่างหรืออักขระอื่น |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งบาร์บนส่วนบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขีดจำกัดล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขีดจำกัดล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างตัวห้อย |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างตัวห้อย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวยกบนทางซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวห้อยและตัวยกบนทางซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวยกบนทางขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวห้อยและตัวยกบนทางขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างตัวยกบน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างตัวยกบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขีดจำกัดบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขีดจำกัดบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | ใส่องค์ประกอบนี้ในกล่องที่ไม่เป็นภาพ (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้สำหรับจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุในกล่องสามารถ (เช่น) ทำหน้าที่เป็นเครื่องจำลองตัวดำเนินการที่มีหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | ใส่ในแถวแนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
MathBar mathBar = new MathBar(new MathematicalText("x"));
```

### ดูเพิ่มเติม

* คลาส [MathElementBase](../mathelementbase)
* อินเทอร์เฟซ [IMathBar](../imathbar)
* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->