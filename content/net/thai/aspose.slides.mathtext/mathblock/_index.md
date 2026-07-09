---
title: MathBlock
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: ระบุอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นบนบรรทัดของมันเอง ทั้งโซนคณิตศาสตร์รวมถึงสมการ นิพจน์ อาเรย์ของสมการหรือ นิพจน์ และสูตร แสดงด้วย math block.
type: docs
weight: 8590
url: /th/aspose.slides.mathtext/mathblock/
---
## MathBlock คลาส

ระบุอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นบนบรรทัดของมันเอง ทั้งโซนคณิตศาสตร์รวมถึงสมการ, นิพจน์, อาเรย์ของสมการหรือ นิพจน์, และสูตร แสดงด้วย math block

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathBlock](mathblock#constructor)() | เริ่มต้นอินสแตนซ์ใหม่ของ MathBlock class. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก |
| [MathBlock](mathblock#constructor_1)(IMathElement) | สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | รับจำนวนของ child math elements ที่อยู่จริงในคอลเลกชัน อ่านอย่างเดียว Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | คืนค่า false เนื่องจากคอลเลกชันของ child elements สามารถแก้ไขได้. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | รับหรือกำหนด IMathElement ที่ตำแหน่งที่ระบุ. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระที่ด้านบนขององค์ประกอบนี้) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | เพิ่ม math element ไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | ลบทุกองค์ประกอบออกจากคอลเลกชัน. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | ตรวจสอบว่าคอลเลกชันมีค่าที่ระบุหรือไม่. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | คัดลอกไปยังอาเรย์ที่ระบุ. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | แยกส่วน child elements ด้วยอักขระตัวคั่น (โดยไม่มีวงเล็บ) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างเศษส่วนด้วย numerator นี้และ denominator ที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างเศษส่วนด้วย numerator นี้และ denominator ที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุด้วย numerator นี้และ denominator ที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุด้วย numerator นี้และ denominator ที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ใส่องค์ประกอบคณิตศาสตร์ในวงเล็บ |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | ใส่ child elements ของบล็อกนี้ในอักขระที่ระบุเช่นวงเล็บหรืออักขระอื่นเป็นกรอบ |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | ใส่ child elements ของบล็อกนี้ในอักขระที่ระบุเช่นวงเล็บหรืออักขระอื่นเป็นกรอบและแยกด้วยอักขระตัวคั่น |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | รับ child elements |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาใต้ |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่มเช่นวงเล็บปีกกาใต้หรืออักขระอื่น |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | ระบุตำแหน่งดัชนีของ math element เฉพาะในคอลเลกชัน |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | แทรก MathElement ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | เชื่อมต่อส่วนประกอบคณิตศาสตร์กับ MathBlock นี้ |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | เชื่อมต่อข้อความคณิตศาสตร์กับ MathBlock นี้ |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | เชื่อมต่อ MathBlock อื่นกับบล็อกนี้ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้าง N-ary operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้าง N-ary operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งเส้นบาร์ที่ด้านบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | ลบการปรากฏครั้งแรกของอ็อบเจ็กต์เฉพาะจากคอลเลกชัน |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบ limits ต่ำ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบ limits ต่ำ |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้าง subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้าง subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้าง subscript และ superscript ทางซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้าง subscript และ superscript ทางซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้าง subscript และ superscript ทางขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้าง subscript และ superscript ทางขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้าง superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้าง superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบ limits สูง |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบ limits สูง |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | ใส่องค์ประกอบนี้ในกล่องไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุในกล่องอาจทำหน้าที่เป็นตัวจำลองผู้ดำเนินการกับหรือไม่มีจุดจัดตำแหน่ง ใช้เป็นจุดตัดบรรทัด หรืออาจถูกจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | วาง child elements ในอาร์เรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งเส้นบาร์ที่ด้านล่างขององค์ประกอบนี้ |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | บันทึกเนื้อหาของ [`MathBlock`](../mathblock) นี้เป็น MathML |

### ตัวอย่าง

ตัวอย่าง:

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