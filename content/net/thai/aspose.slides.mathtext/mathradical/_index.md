---
title: MathRadical
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: ระบุฟังก์ชันรากที่ประกอบด้วยฐานและระดับที่เป็นตัวเลือก ตัวอย่างของอ็อบเจกต์รากคือ .
type: docs
weight: 8940
url: /th/aspose.slides.mathtext/mathradical/
---
## คลาส MathRadical

ระบุฟังก์ชันรากที่ประกอบด้วยฐานและระดับที่เป็นตัวเลือก ตัวอย่างของอ็อบเจกต์รากคือ √𝑥.

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | สร้างอินสแตนซ์ใหม่ของคลาส MathRadical. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | อาร์กิวเมนต์ฐาน |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | อาร์กิวเมนต์ระดับ |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | ซ่อนระดับ เมื่อค่าเป็น true ระดับจะไม่แสดง เช่น √𝑥 |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระที่อยู่ด้านบนขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่น ๆ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | ใช้ฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | ใช้ฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | รับองค์ประกอบลูก |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บก้ามปืนล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่ม เช่น วงเล็บก้ามปืนล่างหรืออักขระอื่น |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | เชื่อมโยงองค์ประกอบคณิตศาสตร์และสร้างบล็อคคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | เชื่อมโยงข้อความคณิตศาสตร์และสร้างบล็อคคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งบาร์ที่ด้านบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างดัชนีล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างดัชนีล่าง |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างดัชนีล่างและดัชนีบนทางซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างดัชนีล่างและดัชนีบนทางซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างดัชนีล่างและดัชนีบนทางขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างดัชนีล่างและดัชนีบนทางขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างดัชนีบน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างดัชนีบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่มองเห็น (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อกลุ่มส่วนของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่อยู่ในกล่องสามารถทำหน้าที่เป็นอิมูเลเตอร์ของตัวดำเนินการพร้อมหรือไม่มีจุดจัดแนว ใช้เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | ใส่ในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |

### ตัวอย่าง

Example:

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### ดูเพิ่มเติม

* คลาส [MathElementBase](../mathelementbase)
* อินเทอร์เฟซ [IMathRadical](../imathradical)
* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->