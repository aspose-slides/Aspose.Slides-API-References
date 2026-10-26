---
title: NumberFormatInfo
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เก็บข้อมูลเกี่ยวกับวิธีการจัดรูปแบบตัวเลข การดำเนินการตั้งค่าเปิดให้เฉพาะอ็อบเจ็กต์ที่ไม่ใช่แบบอ่านอย่างเดียวเท่านั้น อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันหรือข้อผิดพลาดการตรวจสอบ ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr แล้วใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 248
url: /th/system.globalization/numberformatinfo/
---
## NumberFormatInfo คลาส

เก็บข้อมูลเกี่ยวกับวิธีการจัดรูปแบบตัวเลข การดำเนินการตั้งค่าเปิดให้เฉพาะอ็อบเจ็กต์ที่ไม่ใช่แบบอ่าน-อย่างเดียวเท่านั้น อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันหรือข้อผิดพลาดการตรวจสอบ ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ทำสำเนาข้อมูลรูปแบบ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่สองค่า NaN ถือว่าสเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่สองค่า NaN ถือว่าสเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | รับจำนวนหลักทศนิยมของสกุลเงิน. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | รับตัวคั่นทศนิยมของสกุลเงิน. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | รับตัวคั่นกลุ่มของสกุลเงิน. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | รับจำนวนหลักทศนิยมของสกุลเงินต่อกลุ่ม. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | รับรูปแบบลบของสกุลเงิน. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | รับรูปแบบบวกของสกุลเงิน. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | รับสัญลักษณ์สกุลเงิน. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | รับข้อมูลรูปแบบตัวเลขที่กำหนดโดยวัฒนธรรมของเธรดปัจจุบัน. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | รับค่าที่ระบุวิธีการแสดงรูปร่างของตัวเลข. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | รับข้อมูลรูปแบบตัวเลขที่กำหนดโดยวัฒนธรรมที่คงที่. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | ตรวจสอบว่ารูปแบบเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | รับสัญลักษณ์ Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | รับสัญลักษณ์ตัวเลข (0 ถึง 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | รับสัญลักษณ์ลบที่ไม่มีที่สิ้นสุด. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | รับเครื่องหมายลบ. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | รับจำนวนหลักทศนิยม. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | รับตัวคั่นทศนิยม. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | รับตัวคั่นกลุ่มตัวเลข. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | รับจำนวนตัวเลขต่อกลุ่ม. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | รับรูปแบบลบของจำนวน. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | รับจำนวนตำแหน่งทศนิยมในค่าร้อยละ. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | รับตัวคั่นทศนิยมในค่าร้อยละ. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | รับตัวคั่นกลุ่มในค่าร้อยละ. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | รับจำนวนตัวเลขต่อกลุ่มของค่าร้อยละ. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | รับรูปแบบลบของเปอร์เซ็นต์. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | รับรูปแบบบวกของเปอร์เซ็นต์. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | รับสัญลักษณ์เปอร์เซ็นต์. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | รับสัญลักษณ์ permille. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | รับสัญลักษณ์บวกที่ไม่มีที่สิ้นสุด. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | รับเครื่องหมายบวก. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจ็กต์. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | รับฟอร์แมตเตอร์ของประเภทเฉพาะ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้การสร้างแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | รับฟอร์แมตเตอร์ที่เชื่อมกับผู้ให้รูปแบบ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์. เทียบเท่าการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เทียบเท่ากับตัวดำเนินการ 'is' ของ C#. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทกำหนดเอง. |
|  [NumberFormatInfo](./numberformatinfo/)() | คอนสตรัคเตอร์เริ่มต้น (invariant [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | รับเวอร์ชันอ่านอย่างเดียวของฟอร์แมตเตอร์. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | ตั้งค่าจำนวนหลักทศนิยมของสกุลเงิน. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | ตั้งค่าตัวคั่นทศนิยมของสกุลเงิน. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | ตั้งค่าตัวคั่นกลุ่มของสกุลเงิน. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | ตั้งค่าจำนวนหลักทศนิยมของสกุลเงินต่อกลุ่ม. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | ตั้งค่ารูปแบบลบของสกุลเงิน. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | ตั้งค่ารูปแบบบวกของสกุลเงิน. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | ตั้งค่าสัญลักษณ์สกุลเงิน. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | ตั้งค่าที่ระบุวิธีแสดงรูปร่างของตัวเลข. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | ตั้งค่าสัญลักษณ์ Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | ตั้งค่าสัญลักษณ์ตัวเลข (0 ถึง 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | ตั้งค่าสัญลักษณ์ลบที่ไม่มีที่สิ้นสุด. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | ตั้งค่าเครื่องหมายลบ. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | ตั้งค่าจำนวนหลักทศนิยม. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | ตั้งค่าตัวคั่นทศนิยม. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | ตั้งค่าตัวคั่นกลุ่มตัวเลข. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | ตั้งค่าจำนวนตัวเลขต่อกลุ่ม. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | ตั้งค่ารูปแบบลบของจำนวน. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | ตั้งค่าจำนวนตำแหน่งทศนิยมในค่าร้อยละ. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | ตั้งค่าตัวคั่นทศนิยมในค่าร้อยละ. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | ตั้งค่าตัวคั่นกลุ่มในค่าร้อยละ. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | ตั้งค่าจำนวนตัวเลขต่อกลุ่มของค่าร้อยละ. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | ตั้งค่ารูปแบบลบของเปอร์เซ็นต์. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | ตั้งค่ารูปแบบบวกของเปอร์เซ็นต์. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | ตั้งค่าสัญลักษณ์เปอร์เซ็นต์. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | ตั้งค่าสัญลักษณ์ permille. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | ตั้งค่าสัญลักษณ์บวกที่ไม่มีที่สิ้นสุด. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | ตั้งค่าเครื่องหมายบวก. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่ม

* คลาส [Object](../../system/object/)
* คลาส [IFormatProvider](../../system/iformatprovider/)
* คลาส [ICloneable](../../system/icloneable/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)