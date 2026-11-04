---
title: MathBlock
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: ระบุอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นบนบรรทัดของตนเอง. ทุกโซนคณิตศาสตร์รวมถึงสมการ นิพจน์ อาเรย์ของสมการหรือ นิพจน์ และสูตร จะถูกแทนด้วย math block.
type: docs
weight: 8610
url: /th/aspose.slides.mathtext/mathblock/
---
## MathBlock คลาส

ระบุอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นบนบรรทัดของตนเอง ทุกโซนคณิตศาสตร์ รวมถึงสมการ, นิพจน์, อาเรย์ของสมการหรือ นิพจน์, และสูตร จะถูกแสดงโดย math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathBlock](mathblock#constructor)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก |
| [MathBlock](mathblock#constructor_1)(IMathElement) | สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | รับจำนวนขององค์ประกอบคณิตศาสตร์ลูกที่จริง ๆ อยู่ในคอลเลกชัน. อ่านอย่างเดียว Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | คืนค่า false เนื่องจากคอลเลกชันของ child elements สามารถแก้ไขได้. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | รับหรือกำหนด IMathElement ที่ตำแหน่งที่ระบุ. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระบนส่วนบนขององค์ประกอบนี้) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | เพิ่ม math element ไปยังส่วนท้ายของคอลเลกชัน. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | ลบองค์ประกอบทั้งหมดออกจากคอลเลกชัน. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | กำหนดว่าคอลเลกชันมีค่าที่ระบุหรือไม่. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | คัดลอกไปยังอาร์เรย์ที่ระบุ. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | กำหนดขอบเขตของ child elements ด้วยอักขระคั่น (โดยไม่มีวงเล็บ) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างส่วนเศษโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างส่วนเศษโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างส่วนเศษประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างส่วนเศษประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบ math element ด้วยวงเล็บ |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | ล้อมรอบ child elements ของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่น ๆ เป็นกรอบ |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | ล้อมรอบ child elements ของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่น ๆ เป็นกรอบและกำหนดขอบเขตด้วยอักขระคั่น |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | รับ child elements |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาตรงล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่มเช่นวงเล็บปีกกาตรงล่างหรืออักขระอื่น |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | กำหนดดัชนีของ math element เฉพาะในคอลเลกชัน |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | แทรก MathElement ไปยังคอลเลกชันที่ตำแหน่งที่ระบุ |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินติกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินติกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินติกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินติกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินติกรัล |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | เชื่อมต่อ math element กับบล็อกคณิตศาสตร์นี้ |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | เชื่อมต่อข้อความคณิตศาสตร์กับบล็อกคณิตศาสตร์นี้ |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | เชื่อมต่อบล็อกคณิตศาสตร์อื่นกับบล็อกนี้ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างโอเปอเรเตอร์ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างโอเปอเรเตอร์ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งบาร์บนส่วนบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | กำหนดรากคณิตศาสตร์ระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | กำหนดรากคณิตศาสตร์ระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | ลบการพบครั้งแรกของอ็อบเจกต์เฉพาะจากคอลเลกชัน. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างตัวห้อย |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างตัวห้อย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวบนด้านซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวห้อยและตัวบนด้านซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวบนด้านขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวห้อยและตัวบนด้านขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างตัวบน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างตัวบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกล่องกรอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องกรอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | วาง child elements ในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งบาร์บนส่วนล่างขององค์ประกอบนี้ |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | บันทึกเนื้อหาของ [`MathBlock`](../mathblock) นี้เป็น MathML |

### ตัวอย่าง

Example:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### ดูเพิ่มเติม

* คลาส [MathElementBase](../mathelementbase)
* อินเทอร์เฟซ [IMathBlock](../imathblock)
* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->