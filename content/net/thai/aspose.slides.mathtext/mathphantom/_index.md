---
title: MathPhantom
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แทนวัตถุคณิตศาสตร์แบบแฟนตอม ltmphantgt ที่ส่งผลต่อการจัดวางขององค์ประกอบย่อยโดยไม่จำเป็นต้องแสดงผลออกมา แฟนตอมสามารถซ่อนนิพจน์ฐานของมันขณะยังคงรักษาความกว้าง ความสูง หรือความลึกไว้เพื่อจัดแนวสูตรหรือสงวนพื้นที่ การมองเห็นและพฤติกรรมเรขาคณิตจะถูกควบคุมโดยคุณสมบัติต่าง ๆ เช่น Show ZeroWid ZeroAsc ZeroDesc และ Transp.
type: docs
weight: 8920
url: /th/aspose.slides.mathtext/mathphantom/
---
## MathPhantom คลาส

แทนวัตถุคณิตศาสตร์แบบแฟนตอม (&lt;m:phant&gt;) ที่มีผลต่อการจัดวางขององค์ประกอบย่อยโดยไม่จำเป็นต้องแสดงผลออกมา แฟนตอมสามารถซ่อนนิพจน์ฐานของมันขณะยังคงรักษาความกว้าง ความสูง หรือความลึกไว้เพื่อจัดแนวสูตรหรือสงวนพื้นที่ พฤติกรรมการมองเห็นและเรขาคณิตจะถูกควบคุมโดยคุณสมบัติต่าง ๆ เช่น Show, ZeroWid, ZeroAsc, ZeroDesc, และ Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [`MathPhantom`](../mathphantom) โดยใช้องค์ประกอบคณิตศาสตร์ฐานที่ระบุ |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | อาร์กิวเมนท์ฐาน |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | รับหรือกำหนดค่าที่บ่งชี้ว่าตัวฐานจะแสดงหรือไม่ |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | รับหรือกำหนดค่าที่บ่งชี้ว่าแฟนตอมโปร่งใสต่อกฎการเว้นระยะตามคลาส |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | รับหรือกำหนดค่าที่บ่งชี้ว่าการขึ้น (ความสูงเหนือเส้นฐาน) ของตัวฐานควรถือว่าเป็นศูนย์ |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | รับหรือกำหนดค่าที่บ่งชี้ว่าการลง (ความลึกต่ำกว่าเส้นฐาน) ของตัวฐานควรถือว่าเป็นศูนย์ |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | รับหรือกำหนดค่าที่บ่งชี้ว่าความกว้างของตัวฐานควรถือว่าเป็นศูนย์ |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระที่ด้านบนขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนท์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนท์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนท์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนท์และอาร์กิวเมนท์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนท์และอาร์กิวเมนท์เพิ่มเติมที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างเศษส่วนโดยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างเศษส่วนโดยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุโดยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุโดยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนท์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนท์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | ดึงองค์ประกอบลูก |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออักขระอื่น |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | รวบรวมองค์ประกอบคณิตศาสตร์และสร้างบล็อคคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | รวบรวมข้อความคณิตศาสตร์และสร้างบล็อคคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งบาร์ที่ด้านบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | กำหนดรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนท์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | กำหนดรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนท์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างสคริปต์ย่อ |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างสคริปต์ย่อ |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวห้อยล่างและตัวห้อยบนทางซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวห้อยล่างและตัวห้อยบนทางซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวห้อยล่างและตัวห้อยบนทางขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวห้อยล่างและตัวห้อยบนทางขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างสคริปต์บน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างสคริปต์บน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่ปรากฏ (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่ใส่ในกล่องอาจ (เช่น) ทำหน้าที่เป็นอิมูเลเตอร์ของตัวดำเนินการที่มีหรือไม่มีจุดแนบ ทำหน้าที่เป็นจุดตัดบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้การตัดบรรทัดภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | ใส่ในอาร์เรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |

### ตัวอย่าง

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // ซ่อนเนื้อหา
phantom.ZeroWidth = false;     // คงความกว้าง
```

### ดูเพิ่มเติม

* คลาส [MathElementBase](../mathelementbase)
* อินเทอร์เฟซ [IMathPhantom](../imathphantom)
* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->