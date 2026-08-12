---
title: IMathRadical
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุฟังก์ชันราดิกัล ประกอบด้วยฐานและระดับที่เป็นตัวเลือก ตัวอย่างของอ็อบเจ็กต์ราดิกัลคือ \\u221A\\uD835\\uDC65.
type: docs
weight: 508
url: /th/aspose.slides.mathtext/imathradical/
---
## IMathRadical คลาส

ระบุฟังก์ชันราดิกัล ประกอบด้วยฐานและระดับที่เป็นตัวเลือก ตัวอย่างของอ็อบเจ็กต์ราดิกัลคือ \\u221A\\uD835\\uDC65.

```cpp
class IMathRadical : public virtual Aspose::Slides::MathText::IMathElement
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | ตั้งเครื่องหมายสำเนียง (อักขระที่ด้านบนขององค์ประกอบนี้) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์และอากิวเมนต์เพิ่มเติมที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์และอากิวเมนต์เพิ่มเติมที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | สร้างเศษส่วนของประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | สร้างเศษส่วนของประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | ล้อมรอบองค์ประกอบนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่น ๆ เป็นกรอบ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้กฎของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใดเลย รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใดเลย รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับฟังก์ชันของอากิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | รับฟังก์ชันของอากิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() | อากิวเมนต์ฐาน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Degree](./get_degree/)() | อากิวเมนต์ระดับ |
| virtual **bool** [get_HideDegree](./get_hidedegree/)() | ซ่อนระดับ เมื่อเป็น true จะไม่แสดงระดับ เช่น \\u221A\\uD835\\uDC65 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | รับองค์ประกอบลูก |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกบุญของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกบุญของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักขระการจัดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออักขระอื่น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | รับค่าปริพันธ์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับค่าปริพันธ์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | รับค่าปริพันธ์โดยไม่มีขอบเขต |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | รับค่าปริพันธ์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | รับค่าปริพันธ์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นอเนกบุญของตัวดำเนินการ 'is' ของ C# |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | รวมข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกบุญของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทกำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างโอเปอเรเตอร์ N-ary |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | สร้างโอเปอเรเตอร์ N-ary |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาในซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาในซับคลาส |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | ตั้งแถบบนด้านบนขององค์ประกอบนี้ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](./)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | กำหนดรากคณิตศาสตร์ของระดับที่กำหนดจากอากิวเมนต์ที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](./)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | กำหนดรากคณิตศาสตร์ของระดับที่กำหนดจากอากิวเมนต์ที่ระบุ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_HideDegree](./set_hidedegree/)(**bool**) | ซ่อนระดับ เมื่อเป็น true จะไม่แสดงระดับ เช่น \\u221A\\uD835\\uDC65 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับขอบล่าง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | รับขอบล่าง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวห้อย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | สร้างตัวหอย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวห้อยและตัวยกบนด้านซ้าย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | สร้างตัวห้อยและตัวยกบนด้านซ้าย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวห้อยและตัวยกบนด้านขวา |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | สร้างตัวห้อยและตัวยกบนด้านขวา |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวยก |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | สร้างตัวยก |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับขอบบน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | รับขอบบน |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | วางองค์ประกอบนี้ในกล่องขอบ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | วางองค์ประกอบนี้ในกล่องขอบ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | วางองค์ประกอบนี้ในกล่องที่ไม่ปรากฏ (การจัดกลุ่มตามตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่อยู่ในกล่องสามารถ (เช่น) ทำหน้าที่เป็นอีมูเลเตอร์ของโอเปอเรเตอร์พร้อมหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | ใส่ในอาเรย์แนวตั้ง |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกบุญของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | ตั้งแถบที่ด้านล่างขององค์ประกอบนี้ |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

ตัวอย่าง:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3");
// รากลูกบาศก์
```

## ดูเพิ่มเติม

* คลาส [IMathElement](../imathelement/)
* เนมสเปซ [Aspose::Slides::MathText](../)
* ไลบรารี [Aspose.Slides](../../)