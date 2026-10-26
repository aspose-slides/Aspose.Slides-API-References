---
title: MathMatrix
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: ระบุวัตถุ Matrix ที่ประกอบด้วยองค์ประกอบลูกที่จัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์ การสังเกตว่ามาตริกซ์ไม่มีตัวแบ่งในตัว การวางมาตริกซ์ในวงเล็บควรใช้วัตถุ delimiter IMathDelimiter อาร์กิวเมนต์ null สามารถใช้เพื่อสร้างช่องว่างในมาตริกซ์
type: docs
weight: 8850
url: /th/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix คลาส

ระบุวัตถุ Matrix ที่ประกอบด้วยองค์ประกอบลูกที่จัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์ การสังเกตว่ามาตริกซ์ไม่มีตัวแบ่งในตัว การวางมาตริกซ์ในวงเล็บควรใช้วัตถุ delimiter (IMathDelimiter) อาร์กิวเมนต์ null สามารถใช้เพื่อสร้างช่องว่างในมาตริกซ์

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## คอนสตรัคเตอร์

| Name | Description |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | สร้างอินสแตนซ์ใหม่ของคลาส MathMatrix |

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | จำนวนคอลัมน์ในมาตริกซ์ |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | ค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของมาตริกซ์ หาก ColumnGapRule ถูกตั้งค่าเป็น 3 ("Exactly") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ถูกตั้งค่าเป็น 4 ("Multiple") หน่วยจะถูกตีความเป็นจำนวนการเพิ่ม 0.5 em ในกรณีอื่น ๆ จะถูกละเลย ค่าเริ่มต้น: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | ชนิดของการเว้นระยะแนวนอนระหว่างคอลัมน์ของมาตริกซ์ หน่วยการเว้นระยะแนวนอนสามารถเป็น ems หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | ซ่อนตัวแทนขององค์ประกอบมาตริกซ์ที่ว่าง ค่าเริ่มต้น: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | องค์ประกอบของมาตริกซ์ |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | ความกว้างคอลัมน์สูงสุดขั้นต่ำเป็น twips (1/20 ของจุด) ช่องว่าง (ที่เรียกว่า “Column Gap” หรือ “Gap Width”) จะถูกเพิ่มไปที่ MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์ทั้งหมดของ Matrix (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ที่แตกต่าง) ค่าเริ่มต้น: 0 |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | จำนวนแถวในมาตริกซ์ |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | ค่าการเว้นระยะแนวตั้งระหว่างแถวของมาตริกซ์ หาก RowGapRule ถูกตั้งค่าเป็น 3 ("Exactly") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ถูกตั้งค่าเป็น 4 ("Multiple") หน่วยจะถูกตีความเป็นครึ่งบรรทัด ค่าเริ่มต้น: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | ชนิดของการเว้นระยะแนวตั้งระหว่างแถวของมาตริกซ์ หน่วยการเว้นระยะแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0) |

## Methods

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | ลบคอลัมน์ที่ระบุ |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | ลบแถวที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | สร้างเศษส่วนด้วยเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | สร้างเศษส่วนด้วยเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | สร้างเศษส่วนชนิดที่ระบุด้วยเศษนี้และตัวส่วนที่ระบุ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | สร้างเศษส่วนชนิดที่ระบุด้วยเศษนี้และตัวส่วนที่ระบุ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงกลม |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงกลมหรืออักขระอื่นเป็นกรอบ |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | รับลูกขององค์ประกอบ |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | รับการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออักขระอื่น |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ เริ่มแรกทุกองค์ประกอบในคอลัมน์ใหม่เป็น null |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ เริ่มแรกทุกองค์ประกอบในคอลัมน์ใหม่เป็น null |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | แทรกแถวใหม่หลังแถวที่ระบุ เริ่มแรกทุกองค์ประกอบในแถวใหม่เป็น null |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | แทรกแถวใหม่ก่อนแถวที่ระบุ เริ่มแรกทุกองค์ประกอบในแถวใหม่เป็น null |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | รับอินทิกรัล |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | รับอินทิกรัล |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | สร้างตัวดำเนินการ N-ary |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | สร้างตัวดำเนินการ N-ary |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | ตั้งแถบบนสุดขององค์ประกอบนี้ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | ตั้งค่าการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | ตั้งค่าการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | รับลิมิตล่าง |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | รับลิมิตล่าง |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | สร้างตัวห้อย |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | สร้างตัวห้อย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวยกบนด้านซ้าย |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | สร้างตัวห้อยและตัวยกบนด้านซ้าย |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | สร้างตัวห้อยและตัวยกบนด้านขวา |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | สร้างตัวห้อยและตัวยกบนด้านขวา |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | สร้างตัวยกบน |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | สร้างตัวยกบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | รับลิมิตบน |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | รับลิมิตบน |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่อยู่ในกล่องอาจทำหน้าที่เป็นอิมูเลเตอร์ของผู้ดำเนินการโดยมีหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดขึ้นบรรทัดใหม่ หรือจัดกลุ่มเพื่อไม่ให้มีการขึ้นบรรทัดใหม่ภายใน |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | ใส่ในอาเรย์แนวตั้ง |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | ตั้งแถบที่ด้านล่างขององค์ประกอบนี้ |

### Examples

Example:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->