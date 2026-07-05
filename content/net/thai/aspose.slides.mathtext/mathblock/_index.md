---
title: MathBlock
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: ระบุอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นบนบรรทัดของมันเอง โซนคณิตศาสตร์ทั้งหมดรวมถึงสมการ นิพจน์ อาเรย์ของสมการหรือ นิพจน์ และสูตร จะถูกแทนด้วยบล็อกคณิตศาสตร์
type: docs
weight: 8590
url: /th/aspose.slides.mathtext/mathblock/
---
## คลาส MathBlock

ระบุอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นบนบรรทัดของมันเอง โซนคณิตศาสตร์ทั้งหมด รวมถึงสมการ, นิพจน์, อาร์เรย์ของสมการหรือ นิพจน์, และสูตร จะถูกแทนด้วยบล็อกคณิตศาสตร์

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathBlock](mathblock#constructor)() | สร้างอินสแตนซ์ใหม่ของคลาส MathBlock |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก |
| [MathBlock](mathblock#constructor_1)(IMathElement) | สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุลงในบล็อก |

[Count](../../aspose.slides.mathtext/mathblock/count) { get; } | รับจำนวนขององค์ประกอบคณิตศาสตร์ลูกที่อยู่จริงในคอลเลกชันนี้ อ่านอย่างเดียว Int32. |
[IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | คืนค่า false เนื่องจากคอลเลกชันขององค์ประกอบลูกสามารถแก้ไขได้. |
[Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | รับหรือกำหนด IMathElement ที่ตำแหน่งที่ระบุ. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระที่อยู่ด้านบนขององค์ประกอบนี้) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | เพิ่มองค์ประกอบคณิตศาสตร์ลงในส่วนท้ายของคอลเลกชัน |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | ลบทุกองค์ประกอบออกจากคอลเลกชัน |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | ตรวจสอบว่าคอลเลกชันมีค่าที่ระบุหรือไม่ |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | คัดลอกไปยังอาร์เรย์ที่ระบุ |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | กำหนดขอบเขตขององค์ประกอบลูกด้วยอักขระคั่น (โดยไม่มีวงเล็บ) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างส่วนที่มีตัวเศษเป็นนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างส่วนที่มีตัวเศษเป็นนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างส่วนของประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างส่วนของประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | ล้อมรอบองค์ประกอบลูกของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเพื่อเป็นกรอบ |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | ล้อมรอบองค์ประกอบลูกของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบและกำหนดขอบเขตด้วยอักขระคั่น |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | รับองค์ประกอบลูก |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออักขระอื่น |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | กำหนดดัชนีขององค์ประกอบคณิตศาสตร์ที่ระบุในคอลเลกชัน |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | แทรก MathElement ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | รวมองค์ประกอบคณิตศาสตร์เข้ากับบล็อกคณิตศาสตร์นี้ |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | รวมข้อความคณิตศาสตร์เข้ากับบล็อกคณิตศาสตร์นี้ |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | รวมบล็อกคณิตศาสตร์อื่นกับบล็อกนี้ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างผู้ดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างผู้ดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งบาร์บนด้านบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | กำหนดรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | กำหนดรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | ลบการเกิดครั้งแรกของวัตถุที่ระบุออกจากคอลเลกชัน |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างตัวล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างตัวล่าง |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวล่างและตัวบนทางซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวล่างและตัวบนทางซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวล่างและตัวบนทางขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวล่างและตัวบนทางขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างตัวบน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างตัวบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกรอบกล่อง |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกรอบกล่อง |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่มีการแสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้สำหรับจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่อยู่ในกล่องอาจ (เช่น) ทำหน้าที่เป็นตัวจำลองตัวดำเนินการที่มีหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นตำแหน่งการตัดบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | วางองค์ประกอบลูกในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |
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