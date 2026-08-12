---
title: IMathMatrix
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุวัตถุ Matrix ที่ประกอบด้วยองค์ประกอบย่อยที่จัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์ ควรทราบว่าระบบเมทริกซ์ไม่มีตัวแบ่งในตัว เพื่อวางเมทริกซ์ในวงเล็บคุณควรใช้วัตถุตัวแบ่ง (IMathDelimiter) สามารถใช้อาร์กิวเมนต์ Null เพื่อสร้างช่องว่างในเมทริกซ์ได้
type: docs
weight: 391
url: /th/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix คลาส


Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object ([IMathDelimiter](../imathdelimiter/)). Null arguments can be used to create gaps in matrices.

```cpp
class IMathMatrix : public virtual Aspose::Slides::MathText::IMathElement
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | ตั้งเครื่องหมายสำเนียง (อักขระที่อยู่ด้านบนขององค์ประกอบนี้) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| virtual void [DeleteColumn](./deletecolumn/)(**int32_t**) | ลบคอลัมน์ที่ระบุ |
| virtual void [DeleteRow](./deleterow/)(**int32_t**) | ลบแถวที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างเศษส่วนโดยมีตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | สร้างเศษส่วนโดยมีตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | สร้างเศษส่วนประเภทที่ระบุโดยมีตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | สร้างเศษส่วนประเภทที่ระบุโดยมีตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | ล้อมรอบองค์ประกอบนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้รูปแบบของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaNด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaNด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| virtual [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | จำนวนคอลัมน์ในเมทริกซ์ |
| virtual **uint32_t** [get_ColumnGap](./get_columngap/)() | ค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 (\"Multiple\") หน่วยจะถูกตีความเป็นจำนวน 0.5 em หากเป็นกรณีอื่นจะถูกละเว้น ค่าเริ่มต้น: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() | ประเภทของการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยการเว้นระยะแนวนอนสามารถเป็น em หรือ point (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0) |
| virtual **bool** [get_HidePlaceholders](./get_hideplaceholders/)() | ซ่อนตัวแทนขององค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false |
| virtual **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() | ความกว้างคอลัมน์ขั้นต่ำในหน่วย twips (1/20 ของจุด) ระยะห่างระหว่างคอลัมน์ (เรียกอีกอย่างว่า \"Column Gap\" หรือ \"Gap Width\") จะถูกบวกกับ MinColumnWidth เพื่อกำหนดระยะห่างทั้งหมดของ Matrix [Column](../../aspose.slides/column/) (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่างๆ) ค่าเริ่มต้น: 0 |
| virtual **int32_t** [get_RowCount](./get_rowcount/)() | จำนวนแถวในเมทริกซ์ |
| virtual **uint32_t** [get_RowGap](./get_rowgap/)() | ค่าการเว่นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 (\"Multiple\") หน่วยจะถูกตีความเป็น half-lines ค่าเริ่มต้น: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() | ประเภทของการเว่นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยการเว่นระยะแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0) |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | รับองค์ประกอบลูก |
| virtual [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) | รับการจัดแนวนอนของคอลัมน์ที่ระบุ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานที่คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาด้านล่าง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่มเช่นวงเล็บปีกกาด้านล่างหรืออักขระอื่น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | องค์ประกอบของเมทริกซ์ |
| virtual void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | องค์ประกอบของเมทริกซ์ |
| virtual void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) | แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ โดยเริ่มต้นทั้งหมดในคอลัมน์ใหม่จะเป็น null |
| virtual void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มต้นทั้งหมดในคอลัมน์ใหม่จะเป็น null |
| virtual void [InsertRowAfter](./insertrowafter/)(**int32_t**) | แทรกแถวใหม่หลังแถวที่ระบุ โดยเริ่มต้นทั้งหมดในแถวใหม่จะเป็น null |
| virtual void [InsertRowBefore](./insertrowbefore/)(**int32_t**) | แทรกแถวใหม่ก่อนแถวที่ระบุ โดยเริ่มต้นทั้งหมดในแถวใหม่จะเป็น null |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | รับอินทิกรัล |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับอินทิกรัล |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | รับอินทิגרัลโดยไม่มีขอบเขต |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | รับอินทิกรัล |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | รับอินทิกรัล |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C# |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | รวมข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| void [Lock](../../system/object/lock/)() | ดำเนินการคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการทำงานที่คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างโอเปอเรเตอร์ N-ary |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | สร้างโอเปอเรเตอร์ N-ary |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | ตั้งบาร์ที่ด้านบนขององค์ประกอบนี้ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าด้วย nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ |
| virtual void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ ค่าที่เป็นไปได้คือ top, bottom, และ center ค่าเริ่มต้น: Center |
| virtual void [set_ColumnGap](./set_columngap/)(**uint32_t**) | ค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งเป็น 4 (\"Multiple\") หน่วยจะถูกตีความเป็นจำนวน 0.5 em หากเป็นกรณีอื่นจะถูกละเว้น ค่าเริ่มต้น: 0 |
| virtual void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) | ประเภทของการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยการเว้นระยะแนวนอนสามารถเป็น em หรือ point (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0) |
| virtual void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) | ซ่อนตัวแทนขององค์ประกอบเมทริกซ์ที่ว่าง ค่าเริ่มต้น: false |
| virtual void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) | ความกว้างคอลัมน์ขั้นต่ำในหน่วย twips (1/20 ของจุด) ระยะห่างระหว่างคอลัมน์ (เรียกอีกอย่างว่า \"Column Gap\" หรือ \"Gap Width\") จะถูกบวกกับ MinColumnWidth เพื่อกำหนดระยะห่างทั้งหมดของ Matrix [Column](../../aspose.slides/column/) (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่างๆ) ค่าเริ่มต้น: 0 |
| virtual void [set_RowGap](./set_rowgap/)(**uint32_t**) | ค่าการเว่นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งเป็น 3 (\"Exactly\") หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งเป็น 4 (\"Multiple\") หน่วยจะถูกตีความเป็น half-lines ค่าเริ่มต้น: 0 |
| virtual void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) | ประเภทของการเว่นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หน่วยการเว่นระยะแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips) ค่าเริ่มต้น: SingleSpacingGap (0) |
| virtual void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ |
| virtual void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับขีดจำกัดล่าง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | รับขีดจำกัดล่าง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวห้อย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | สร้างตัวห้อย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวห้อยและตัวบนด้านซ้าย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | สร้างตัวห้อยและตัวบนด้านซ้าย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวห้อยและตัวบนด้านขวา |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | สร้างตัวห้อยและตัวบนด้านขวา |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวบน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | สร้างตัวบน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนการเป็น shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับขีดจำกัดบน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | รับขีดจำกัดบน |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | วางองค์ประกอบนี้ในกล่องเส้นขอบ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | วางองค์ประกอบนี้ในกล่องเส้นขอบ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (กล่องเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่อยู่ในกล่องสามารถ (เช่น) ทำหน้าที่เป็นโอเปอเรเตอร์จำลองโดยมีหรือไม่มีจุดจัดตำแหน่ง ทำหน้าที่เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | ใส่ในอาเรย์แนวตั้ง |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการทำงานที่คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## ดูเพิ่มเติม

* คลาส [IMathElement](../imathelement/)
* เนมสเปซ [Aspose::Slides::MathText](../)
* ไลบรารี [Aspose.Slides](../../)