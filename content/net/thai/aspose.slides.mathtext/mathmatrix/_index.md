---
title: MathMatrix
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: ระบุวัตถุ Matrix ซึ่งประกอบด้วยองค์ประกอบย่อยที่จัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์ จำเป็นต้องสังเกตว่ามาเทริกซ์ไม่มีตัวขอบในตัว เพื่อวางเมทริกซ์ในวงเล็บคุณควรใช้วัตถุ delimiter IMathDelimiter สามารถใช้ค่า Null เพื่อสร้างช่องว่างในเมทริกซ์ได้.
type: docs
weight: 8870
url: /th/aspose.slides.mathtext/mathmatrix/
---
## คลาส MathMatrix

ระบุวัตถุ Matrix ซึ่งประกอบด้วยองค์ประกอบย่อยที่จัดแถวเป็นหนึ่งหรือหลายแถวและคอลัมน์ จำเป็นต้องสังเกตว่ามาเทริกซ์ไม่มีกำหนดขอบในตัว เพื่อวางเมทริกซ์ในวงเล็บคุณควรใช้วัตถุ delimiter (IMathDelimiter) สามารถใช้ค่า null เพื่อสร้างช่องว่างในเมทริกซ์ได้.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathMatrix. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | ระบุตำแหน่งจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | จำนวนคอลัมน์ในเมทริกซ์ |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | ค่าเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็นจำนวนของการเพิ่ม 0.5 em ในกรณีอื่น ๆ จะละเลย ค่าเริ่มต้น: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | ประเภทของเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยเว้นระยะแนวนอนสามารถเป็น ems หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | ซ่อนตัวเติมสำหรับองค์ประกอบเมทริกซ์ที่ว่างเปล่า ค่าเริ่มต้น: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | องค์ประกอบของเมทริกซ์ |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | ความกว้างคอลัมน์ต่ำสุดเป็น twips (1/20 ของจุด) ระยะห่างช่อง (ที่เรียกว่า “Column Gap” หรือ “Gap Width”) จะเพิ่มเข้าไปกับ MinColumnWidth เพื่อกำหนดระยะเว้นระยะคอลัมน์ของเมทริกซ์ทั้งหมด (ระยะระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | จำนวนแถวในเมทริกซ์ |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | ค่าเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งค่าเป็น 3 (\"Exactly\") หน่วยจะตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งค่าเป็น 4 (\"Multiple\") หน่วยจะตีความเป็น half-lines ค่าเริ่มต้น: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | ประเภทของเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยเว้นระยะแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0) |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระที่ด้านบนขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์และอากิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์และอากิวเมนต์เพิ่มเติมที่ระบุ |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | ลบคอลัมน์ที่ระบุ |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | ลบแถวที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บ หรืออักขระอื่นเป็นกรอบ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอากิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอากิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | รับองค์ประกอบลูก |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | รับการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บเคิร์ลีกล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรการจัดกลุ่ม เช่น วงเล็บเคิร์ลีกล่าง หรืออื่น ๆ |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | แทรกคอลัมน์ใหม่หลังจากคอลัมน์ที่ระบุ โดยเริ่มต้นองค์ประกอบทั้งหมดในคอลัมน์ใหม่จะเป็น null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มต้นองค์ประกอบทั้งหมดในคอลัมน์ใหม่จะเป็น null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | แทรกแถวใหม่หลังจากแถวที่ระบุ โดยเริ่มต้นองค์ประกอบทั้งหมดในแถวใหม่จะเป็น null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | แทรกแถวใหม่ก่อนแถวที่ระบุ โดยเริ่มต้นองค์ประกอบทั้งหมดในแถวใหม่จะเป็น null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | รวมข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งบาร์ที่ด้านบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ระบุรูทคณิตศาสตร์ของดีกรีที่กำหนดจากอากิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ระบุรูทคณิตศาสตร์ของดีกรีที่กำหนดจากอากิวเมนต์ที่ระบุ |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | ตั้งการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | ตั้งการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างตัวห้อย |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างตัวห้อย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวสูงบนด้านซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวห้อยและตัวสูงบนด้านซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวสูงบนด้านขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวห้อยและตัวสูงบนด้านขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างตัวสูง |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างตัวสูง |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้สำหรับจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ ตัวอ็อบเจกต์ที่อยู่ในกรอบอาจทำหน้าที่เป็นอิมมูลเลเตอร์ของโอเปอเรเตอร์พร้อมหรือไม่มีจุดการจัดแนว, ทำหน้าที่เป็นจุดแบ่งบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้เกิดการแบ่งบรรทัดภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | ใส่ในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |

### ตัวอย่าง

```csharp
[C#]
IMMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### ดูเพิ่มเติม

* คลาส [MathElementBase](../mathelementbase)
* อินเทอร์เฟซ [IMathMatrix](../imathmatrix)
* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->