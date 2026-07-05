---
title: IMathElement
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: อินเทอร์เฟซพื้นฐานขององค์ประกอบคณิตศาสตร์ใด ๆ เช่น เศษส่วน, ข้อความคณิตศาสตร์, ฟังก์ชัน, นิพจน์ที่มีหลายองค์ประกอบ เป็นต้น
type: docs
weight: 8230
url: /th/aspose.slides.mathtext/imathelement/
---
## อินเทอร์เฟซ IMathElement

อินเทอร์เฟซพื้นฐานขององค์ประกอบคณิตศาสตร์ใด ๆ: เศษส่วน, ข้อความคณิตศาสตร์, ฟังก์ชัน, นิพจน์ที่มีหลายองค์ประกอบ ฯลฯ

```csharp
public interface IMathElement
```

## Methods

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | สร้างเศษส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | สร้างเศษส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | ล้อมรอบองค์ประกอบนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่น ๆ เป็นกรอบ |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | รับองค์ประกอบลูก |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรจัดกลุ่ม เช่น วงเล็บโค้งล่างหรืออักขระอื่น |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | ตั้งแถบบนสุดขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | รับค่าขอบล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | รับค่าขอบล่าง |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | สร้างตัวห้อย |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | สร้างตัวห้อย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวบนทางซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | สร้างตัวห้อยและตัวบนทางซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวบนทางขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | สร้างตัวห้อยและตัวบนทางขวา |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | สร้างตัวบน |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | สร้างตัวบน |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | รับค่าขอบบน |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | รับค่าขอบบน |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่ปรากฏ (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ อ็อบเจกต์ที่อยู่ในกล่องสามารถทำหน้าที่เป็นอิมูเลเตอร์ของตัวดำเนินการพร้อมหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้เกิดการตัดบรรทัดภายใน |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | วางในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | ตั้งแถบด้านล่างขององค์ประกอบนี้ |

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->