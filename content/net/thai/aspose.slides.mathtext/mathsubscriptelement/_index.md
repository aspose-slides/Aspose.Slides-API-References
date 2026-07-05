---
title: MathSubscriptElement
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: ระบุอ็อบเจ็กต์ดัชนีล่างที่ประกอบด้วยฐานและดัชนีล่างขนาดเล็กที่วางอยู่ด้านล่างและด้านขวา.
type: docs
weight: 9000
url: /th/aspose.slides.mathtext/mathsubscriptelement/
---
## คลาส MathSubscriptElement

ระบุอ็อบเจ็กต์ดัชนีล่าง ซึ่งประกอบด้วยฐานและดัชนีล่างขนาดเล็กที่วางอยู่ด้านล่างและด้านขวา

```csharp
public sealed class MathSubscriptElement : BaseScript, IMathSubscriptElement
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathSubscriptElement](mathsubscriptelement)(IMathElement, IMathElement) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathSubscriptElement |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | อากูเมนต์ฐาน |
| [Subscript](../../aspose.slides.mathtext/mathsubscriptelement/subscript) { get; } | ดัชนีล่าง |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระที่อยู่ด้านบนขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์และอากูเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | ใช้ฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์และอากูเมนต์เพิ่มเติมที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | ใช้ฟังก์ชันของอากูเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | ใช้ฟังก์ชันของอากูเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathsubscriptelement/getchildren)() | รับองค์ประกอบลูก |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออักขระอื่น |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | ใช้การอินทิเกรตโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | ใช้การอินทิเกรต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | ใช้การอินทิเกรต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | ใช้การอินทิเกรต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | ใช้การอินทิเกรต |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | เชื่อมโยงองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | เชื่อมโยงข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งแถบบนสุดขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ระบุรากคณิตศาสตร์ของระดับที่ระบุจากอากูเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ระบุรากคณิตศาสตร์ของระดับที่ระบุจากอากูเมนต์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบเขตล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบเขตล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างดัชนีล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างดัชนีล่าง |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างดัชนีล่างและดัชนีบนด้านซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างดัชนีล่างและดัชนีบนด้านซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างดัชนีล่างและดัชนีบนด้านขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างดัชนีล่างและดัชนีบนด้านขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างดัชนีบน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างดัชนีบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบเขตบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบเขตบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องไม่มีภาพ (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่อยู่ในกล่องสามารถทำหน้าที่เป็นอิมูเลเตอร์ของตัวดำเนินการที่มีหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดหยุดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | วางในแถวแนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งแถบด้านล่างขององค์ประกอบนี้ |

### ตัวอย่าง

Example:

```csharp
[C#]
MathSubscriptElement subscriptElement = new MathematicalText("N").SetSubscript("i");
```

### ดูเพิ่มเติม

* คลาส [BaseScript](../basescript)
* อินเทอร์เฟซ [IMathSubscriptElement](../imathsubscriptelement)
* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->