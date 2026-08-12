---
title: JapaneseLunisolarCalendar
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ปฏิทินจันทรคติญี่ปุ่น. ยังไม่ได้ทำการใช้งาน. วัตถุของคลาสนี้ควรสร้างเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() function. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr pointer และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชันเป็น argument."
type: docs
weight: 196
url: /th/system.globalization/japaneselunisolarcalendar/
---
## JapaneseLunisolarCalendar คลาส

Japanese lunisolar calendar. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class JapaneseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | เพิ่มวันให้กับจุดเวลา |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | เพิ่มชั่วโมงให้กับจุดเวลา |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | เพิ่มมิลลิวินาทีให้กับจุดเวลา |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | เพิ่มนาทีให้กับจุดเวลา |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | เพิ่มเดือนให้กับจุดเวลา |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | เพิ่มวินาทีให้กับจุดเวลา |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | เพิ่มสัปดาห์ให้กับจุดเวลา |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | เพิ่มปีให้กับจุดเวลา |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | ข้อมูล RTTI |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | สร้างสำเนาของวัตถุปัจจุบันและคืนพอยน์เตอร์แบบแชร์ให้ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยถือว่า NaN สองค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยถือว่า NaN สองค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | ข้อมูล RTTI |
| int [get_CurrentEra](../calendar/get_currentera/)() const | ดึงดัชนีของยุคปัจจุบัน |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | ดึงค่าของยุคปัจจุบัน |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | ดึงรายการยุคที่มีอยู่ในปฏิทิน |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | ตรวจสอบว่าปฏิทินเป็นแบบอ่านอย่างเดียวหรือไม่ |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | จุดเวลามากสุดที่ปฏิทินสนับสนุน |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | จุดเวลาน้อยสุดที่ปฏิทินสนับสนุน |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | ดึงปีสุดท้ายที่สามารถแสดงด้วยเลขสองหลักได้ |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | ดึงสเต็มดาราศาสตร์ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | ดึงวันของเดือนสำหรับจุดเวลาที่ระบุ |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | ดึงวันของสัปดาห์สำหรับจุดเวลาที่ระบุ |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | ดึงวันของปีสำหรับจุดเวลาที่ระบุ |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | ดึงจำนวนวันในเดือนที่ระบุ |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | ดึงจำนวนวันในเดือนที่ระบุ |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | ดึงจำนวนวันในปีที่ระบุ |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | ดึงจำนวนวันในปีที่ระบุ |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | ดึงยุคสำหรับจุดเวลาที่ระบุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำแฮชอ็อบเจ็กต์กำหนดเองได้ |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | ดึงชั่วโมงสำหรับจุดเวลาที่ระบุ |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | ดึงเดือนอธิกสุรทินสำหรับปีที่ระบุ |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | ข้อมูล RTTI |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | ข้อมูล RTTI |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | ดึงมิลลิวินาทีสำหรับจุดเวลาที่ระบุ |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | ดึงนาทีสำหรับจุดเวลาที่ระบุ |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | ดึงเดือนสำหรับจุดเวลาที่ระบุ |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | ดึงจำนวนเดือนในปีที่ระบุ |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | ดึงจำนวนเดือนในปีที่ระบุ |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | ดึงวินาทีสำหรับจุดเวลาที่ระบุ |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | ดึงปีในรอบ 60 ปี |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | ดึงกิ่งดิน |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงชนิดจริงของอ็อบเจ็กต์ เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | ดึงสัปดาห์ของปีสำหรับจุดเวลาที่ระบุ |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | ดึงปีสำหรับจุดเวลาที่ระบุ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType ระบุหรือไม่ เทียบเคียงกับตัวดำเนินการ 'is' ของ C# |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | ตรวจสอบว่าวันเป็นวันอธิกสุรทินหรือไม่ |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | ตรวจสอบว่าวันเป็นวันอธิกสุรทินหรือไม่ |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | ตรวจสอบว่าวันเป็นวันอธิกสุรทินหรือไม่ |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรทินหรือไม่ |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรทินหรือไม่ |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | ตรวจสอบว่าปีเป็นปีอธิกสุรทินหรือไม่ |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | ตรวจสอบว่าปีเป็นปีอธิกสุรทินหรือไม่ |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | ตรวจสอบว่าปีเป็นปีอธิกสุรทินหรือไม่ |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | ตรวจสอบค่าปี เดือน วัน และยุค |
|  [JapaneseLunisolarCalendar](./japaneselunisolarcalendar/)() | คอนสตรัคเตอร์ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรเลย จริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาให้คลาสย่อย |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรเลย จริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาให้คลาสย่อย |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | ดึงเวอร์ชันอ่านอย่างเดียวของปฏิทิน |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงประเภทค่าเทียบกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เฉพาะกรณีของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เฉพาะกรณีของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์โดยค่าเฉพาะ |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | ตั้งค่าปีสุดท้ายที่สามารถแสดงด้วยเลขสองหลัก |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n'th ให้เป็นพอยน์เตอร์อ่อน (แทนแชร์) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | สร้างอ็อบเจ็กต์ [DateTime](../../system/datetime/) จากส่วนประกอบ |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | สร้างอ็อบเจ็กต์ [DateTime](../../system/datetime/) จากส่วนประกอบ |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | แปลงปีเป็นปีสี่หลักโดยใช้คุณสมบัติ TwoDigitYearMax |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้แปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงอ่อน ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงอ่อน ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [JapaneseEra](./japaneseera/) | ยุคญี่ปุ่นปัจจุบัน |

## ดูเพิ่มเติม

* คลาส [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)