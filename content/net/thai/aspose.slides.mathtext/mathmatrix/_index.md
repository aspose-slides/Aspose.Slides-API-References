---
title: MathMatrix
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: ระบุวัตถุ Matrix ที่ประกอบด้วยองค์ประกอบย่อยซึ่งจัดเรียงในหนึ่งหรือหลายแถวและคอลัมน์ จะต้องสังเกตว่าเมทริกซ์ไม่มีตัวคั่นในตัว การใส่เมทริกซ์ในวงเล็บควรใช้วัตถุตัวคั่น IMathDelimiter สามารถใช้ค่า Null เพื่อสร้างช่องว่างในเมทริกซ์ได้
type: docs
weight: 8850
url: /th/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix คลาส

ระบุวัตถุ Matrix ซึ่งประกอบด้วยองค์ประกอบย่อยที่จัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์ ต้องทราบว่าเมทริกซ์ไม่มีตัวคั่นในตัว การใส่เมทริกซ์ในวงเล็บควรใช้วัตถุตัวคั่น (IMathDelimiter) สามารถใช้ค่า Null เพื่อสร้างช่องว่างในเมทริกซ์ได้

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | สร้างอินสแตนซ์ใหม่ของคลาส MathMatrix. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | ระบุการจัดตำแหน่งแนวตั้งสัมพันธ์กับข้อความโดยรอบ ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | จำนวนคอลัมน์ในเมทริกซ์ |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | ค่าของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ถูกตั้งเป็น 3 ("Exactly") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ถูกตั้งเป็น 4 ("Multiple") หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em ในกรณีอื่น ๆ จะถูกละเลย ค่าเริ่มต้น: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | ประเภทของระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยระยะห่างแนวนอนอาจเป็น em หรือ point (เก็บเป็น twips). ค่าเริ่มต้น: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | ซ่อนตัวย่อสำหรับองค์ประกอบเมทริกซ์ที่ว่างเปล่า ค่าเริ่มต้น: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | องค์ประกอบของเมทริกซ์ |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | ความกว้างคอลัมน์ขั้นต่ำในหน่วย twips (1/20 ของจุด) ระยะห่างช่อง (หรือที่เรียกว่า “Column Gap” หรือ “Gap Width”) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์เมทริกซ์ทั้งหมด (ระยะทางระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | จำนวนแถวในเมทริกซ์ |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | ค่าของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ถูกตั้งเป็น 3 ("Exactly") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ถูกตั้งเป็น 4 ("Multiple") หน่วยจะถูกตีความเป็นครึ่งบรรทัด. ค่าเริ่มต้น: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | ประเภทของระยะห่างแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยระยะห่างแนวตั้งอาจเป็น lines หรือ point (เก็บเป็น twips). ค่าเริ่มต้น: SingleSpacingGap (0) |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | ลบคอลัมน์ที่ระบุ |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | ลบแถวที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างส่วนที่มีตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างส่วนที่มีตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างส่วนของประเภทที่ระบุโดยมีตัวเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างส่วนของประเภทที่ระบุโดยมีตัวเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ใส่องค์ประกอบคณิตศาสตร์ในวงเล็บ |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ใส่องค์ประกอบคณิตศาสตร์ในอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | รับองค์ประกอบลูก |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | รับการจัดแนวนอนของคอลัมน์ที่ระบุ |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออื่น |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | แทรกคอลัมน์ใหม่หลังจากคอลัมน์ที่ระบุ โดยเริ่มต้นองค์ประกอบทั้งหมดในคอลัมน์ใหม่เป็น null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มต้นองค์ประกอบทั้งหมดในคอลัมน์ใหม่เป็น null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | แทรกแถวใหม่หลังจากแถวที่ระบุ โดยเริ่มต้นองค์ประกอบทั้งหมดในแถวใหม่เป็น null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | แทรกแถวใหม่ก่อนแถวที่ระบุ โดยเริ่มต้นองค์ประกอบทั้งหมดในแถวใหม่เป็น null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งบาร์บนด้านบนขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ระบุรากคณิตศาสตร์ของลำดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ระบุรากคณิตศาสตร์ของลำดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุหลายคอลัมน์ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับขอบจำกัดล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับขอบจำกัดล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างตัวห้อย |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างตัวห้อย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวยกทางซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวหอยและตัวยกทางซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวยกทางขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวหอยและตัวยกทางขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างตัวยก |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างตัวยก |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับขอบจำกัดบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับขอบจำกัดบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกรอบขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกรอบขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุในกล่องอาจทำหน้าที่เป็นอีมูเลเตอร์ตัวดำเนินการพร้อมหรือไม่มีจุดจัดเรียง ใช้เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | ใส่ในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### ดูเพิ่มเติม

* คลาส [MathElementBase](../mathelementbase)
* อินเทอร์เฟส [IMathMatrix](../imathmatrix)
* เนมสเปซ [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->