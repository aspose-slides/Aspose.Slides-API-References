---
title: IMathBox
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุการจัดกล่อง (บรรจุ) เชิงตรรกะขององค์ประกอบคณิตศาสตร์ ตัวอย่างเช่น อ็อบเจกต์ที่ถูกบ็อกซ์สามารถทำหน้าที่เป็นตัวจำลองโอเปอเรเตอร์ที่มีหรือไม่มีจุดจัดแนว, ทำหน้าที่เป็นจุดตัดบรรทัด, หรือถูกจัดกลุ่มเพื่อไม่ให้เกิดการตัดบรรทัดภายใน ตัวอย่างเช่น \"==\" ควรถูกบ็อกซ์เพื่อป้องกันการตัดบรรทัด.
type: docs
weight: 170
url: /th/aspose.slides.mathtext/imathbox/
---
## IMathBox คลาส


Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the \"==\" operator should be boxed to prevent line breaks.

```cpp
class IMathBox : public virtual Aspose::Slides::MathText::IMathElement
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | ตั้งเครื่องหมายสำเนียง (อักขระที่อยู่ด้านบนขององค์ประกอบนี้) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | สร้างเศษส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | สร้างเศษส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | ล้อมรอบองค์ประกอบคณิตศาสตร์ในวงเล็บ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | ล้อมรอบองค์ประกอบนี้ในอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| virtual **bool** [get_AlignmentPoint](./get_alignmentpoint/)() | เมื่อเป็นจริง, ตัวจำลองโอเปอเรเตอร์นี้ทำหน้าที่เป็นจุดการจัดแนว; นั่นคือ จุดจัดแนวที่กำหนดในสมการอื่น ๆ สามารถจัดแนวกับมันได้. ค่าเริ่มต้น: false |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() | อาร์กิวเมนต์ฐาน |
| virtual **bool** [get_Differential](./get_differential/)() | Differential. เมื่อเป็นจริง, กล่องทำหน้าที่เป็น differential (เช่น \\uD835\\uDC51\\uD835\\uDC65 ในตัวอินทิกรัล) และรับการเว้นระยะแนวนอนที่เหมาะสมสำหรับ differential ทางคณิตศาสตร์. ค่าเริ่มต้น: false |
| virtual **uint8_t** [get_ExplicitBreak](./get_explicitbreak/)() | Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของออบเจกต์ Box หรือไม่, ทำให้บรรทัดห่อที่จุดเริ่มต้นของกล่อง. ระบุจำนวนของโอเปอเรเตอร์บนบรรทัดข้อความคณิตศาสตร์ก่อนหน้า ที่จะใช้เป็นจุดจัดแนวสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์ ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มี explicit break) |
| virtual **bool** [get_NoBreak](./get_nobreak/)() | No break. คุณสมบัตินี้ระบุคุณสมบัติ \"unbreakable\" ของกล่องออบเจกต์. เมื่อเป็นจริง, จะไม่มีการตัดบรรทัดภายในกล่อง. สิ่งนี้อาจสำคัญสำหรับตัวจำลองโอเปอเรเตอร์ที่ประกอบด้วยโอเปอเรเตอร์ไบนารีมากกว่าหนึ่งตัว. หากไม่ได้ระบุองค์ประกอบนี้, การตัดบรรทัดภายในกล่องสามารถเกิดขึ้นได้. ค่าเริ่มต้น: true |
| virtual **bool** [get_OperatorEmulator](./get_operatoremulator/)() | Operator Emulator. เมื่อเป็นจริง, กล่องและเนื้อหาของมันทำหน้าที่เป็นโอเปอเรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์. ตัวอย่างเช่น, อักขระนี้สามารถทำหน้าที่เป็นจุดตัดบรรทัดและสามารถจัดแนวกับโอเปอเรเตอร์อื่น ๆ ได้. Operator Emulators มักใช้เมื่อ glyph หนึ่งหรือหลายตัวรวมกันเป็นโอเปอเรเตอร์ เช่น '=='. ค่าเริ่มต้น: false |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | ดึงองค์ประกอบลูก |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจกต์. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระกลุ่มเช่นวงเล็บปีกกาล่างหรืออื่น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | รับอินทิกรัล |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับอินทิกรัล |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | รับอินทิกรัลโดยไม่มีขอบเขต |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | รับอินทิกรัล |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | รับอินทิกรัล |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. Analog of C# 'is' operator. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างโอเปอเรเตอร์ N-ary |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | สร้างโอเปอเรเตอร์ N-ary |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรเลย, จริง ๆ แล้วเพียงเริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลย, จริง ๆ แล้วเพียงเริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | ตั้งบาร์บนด้านบนขององค์ประกอบนี้ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิง-เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมตามค่าที่ระบุ |
| virtual void [set_AlignmentPoint](./set_alignmentpoint/)(**bool**) | เมื่อเป็นจริง, ตัวจำลองโอเปอเรเตอร์นี้ทำหน้าที่เป็นจุดการจัดแนว; นั่นคือ จุดจัดแนวที่กำหนดในสมการอื่น ๆ สามารถจัดแนวกับมันได้. ค่าเริ่มต้น: false |
| virtual void [set_Differential](./set_differential/)(**bool**) | Differential. เมื่อเป็นจริง, กล่องทำหน้าที่เป็น differential (เช่น \\uD835\\uDC51\\uD835\\uDC65 ในตัวอินทิกรัล) และรับการเว้นระยะแนวนอนที่เหมาะสมสำหรับ differential ทางคณิตศาสตร์. ค่าเริ่มต้น: false |
| virtual void [set_ExplicitBreak](./set_explicitbreak/)(**uint8_t**) | Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของออบเจกต์ Box หรือไม่, ทำให้บรรทัดห่อที่จุดเริ่มต้นของกล่อง. ระบุจำนวนของโอเปอเรเตอร์บนบรรทัดข้อความคณิตศาสตร์ก่อนหน้า ที่จะใช้เป็นจุดจัดแนวสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์ ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มี explicit break) |
| virtual void [set_NoBreak](./set_nobreak/)(**bool**) | No break. คุณสมบัตินี้ระบุคุณสมบัติ \"unbreakable\" ของกล่องออบเจกต์. เมื่อเป็นจริง, จะไม่มีการตัดบรรทัดภายในกล่อง. สิ่งนี้อาจสำคัญสำหรับตัวจำลองโอเปอเรเตอร์ที่ประกอบด้วยโอเปอเรเตอร์ไบนารีมากกว่าหนึ่งตัว. หากไม่ได้ระบุองค์ประกอบนี้, การตัดบรรทัดภายในกล่องสามารถเกิดขึ้นได้. ค่าเริ่มต้น: true |
| virtual void [set_OperatorEmulator](./set_operatoremulator/)(**bool**) | Operator Emulator. เมื่อเป็นจริง, กล่องและเนื้อหาของมันทำหน้าที่เป็นโอเปอเรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์. ตัวอย่างเช่น, อักขระนี้สามารถทำหน้าที่เป็นจุดตัดบรรทัดและสามารถจัดแนวกับโอเปอเรเตอร์อื่น ๆ ได้. Operator Emulators มักใช้เมื่อ glyph หนึ่งหรือหลายตัวรวมกันเป็นโอเปอเรเตอร์ เช่น '=='. ค่าเริ่มต้น: false |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับขอบล่าง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | รับขอบล่าง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวห้อย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | สร้างตัวห้อย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวห้อยและตัวขึ้นบนด้านซ้าย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | สร้างตัวห้อยและตัวขึ้นบนด้านซ้าย |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวห้อยและตัวขึ้นบนด้านขวา |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | สร้างตัวห้อยและตัวขึ้นบนด้านขวา |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้างตัวขึ้นบน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | สร้างตัวขึ้นบน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | รับขอบบน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | รับขอบบน |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | วางองค์ประกอบนี้ใน border-box |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | วางองค์ประกอบนี้ใน border-box |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](./)\> [ToBox](../imathelement/tobox/)() | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ. ออบเจกต์บ็อกซ์สามารถ (เช่น) ทำหน้าที่เป็นตัวจำลองโอเปอเรเตอร์ที่มีหรือไม่มีจุดจัดแนว, ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้เกิดการตัดบรรทัดภายใน |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | ใส่ในอาร์เรย์แนวตั้ง |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์. คืนค่าทรัพยากรโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
```

## ดูเพิ่มเติม

* คลาส [IMathElement](../imathelement/)
* เนมสเปซ [Aspose::Slides::MathText](../)
* ไลบรารี [Aspose.Slides](../../)