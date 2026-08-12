---
title: JulianCalendar
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ปฏิทินจูเลียน. อ็อบเจ็กต์ของคลาสนี้ควรสร้างขึ้นเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject() . ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 209
url: /th/system.globalization/juliancalendar/
---
## JulianCalendar คลาส

Julian calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class JulianCalendar : public System::Globalization::Calendar
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | เพิ่มวันให้กับจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | เพิ่มชั่วโมงให้กับจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | เพิ่มมิลลิวินาทีให้กับจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | เพิ่มนาทีให้กับจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | เพิ่มเดือนให้กับจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | เพิ่มวินาทีให้กับจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | เพิ่มสัปดาห์ให้กับจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | เพิ่มปีให้กับจุดเวลา. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | ข้อมูล RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | สร้างสำเนาของอ็อบเจ็กต์ปัจจุบันและคืนพอยน์เตอร์แบบ shared ให้กับมัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยในสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยในสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | รับประเภทอัลกอริธึม. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | รับดัชนีของยุคปัจจุบัน. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | รับค่าของยุคปัจจุบัน. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | รับรายการของยุคที่มีอยู่ในปฏิทิน. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | ตรวจสอบว่าปฏิทินเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | จุดเวลาสูงสุดที่ปฏิทินสนับสนุน. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | จุดเวลาอย่างต่ำที่ปฏิทินสนับสนุน. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | รับปีสุดท้ายที่สามารถแทนได้ด้วยสองหลัก. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | รับวันของเดือนสำหรับจุดเวลาที่ระบุ. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | รับวันของสัปดาห์สำหรับจุดเวลาที่ระบุ. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | รับวันของปีสำหรับจุดเวลาที่ระบุ. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | รับจำนวนวันในเดือนที่ระบุ. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | รับจำนวนวันในเดือนที่ระบุ. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | รับจำนวนวันในเดือนที่ระบุ. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | รับจำนวนวันในปีที่ระบุ. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | รับจำนวนวันในปีที่ระบุ. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | รับจำนวนวันในปีที่ระบุ. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | รับยุคสำหรับจุดเวลาที่ระบุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็น analog ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำ hash ของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | รับชั่วโมงสำหรับจุดเวลาที่ระบุ. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | รับเดือนอธิกสุรัตติสำหรับปีที่ระบุ. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | รับเดือนอธิกสุรัตติสำหรับปีที่ระบุ. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | รับเดือนอธิกสุรัตติสำหรับปีที่ระบุ. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | รับมิลลิวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | รับนาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | รับเดือนสำหรับจุดเวลาที่ระบุ. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | รับจำนวนเดือนในปีที่ระบุ. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | ข้อมูล RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | ข้อมูล RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | รับวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็น analog ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | รับสัปดาห์ของปีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | รับปีสำหรับจุดเวลาที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็น analog ของ operator 'is' ของ C#. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | ตรวจสอบว่าวันเป็นวันอธิกสุรัตติหรือไม่. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | ตรวจสอบว่าวันเป็นวันอธิกสุรัตติหรือไม่. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | ตรวจสอบว่าวันเป็นวันอธิกสุรัตติหรือไม่. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรัตติหรือไม่. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรัตติหรือไม่. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรัตติหรือไม่. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | ตรวจสอบว่าปีเป็นปีอธิกสุรัตติหรือไม่. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | ตรวจสอบว่าปีเป็นปีอธิกสุรัตติหรือไม่. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | ตรวจสอบว่าปีเป็นปีอธิกสุรัตติหรือไม่. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | ตรวจสอบค่าปี, เดือน, วันและยุค. |
|  [JulianCalendar](./juliancalendar/)() | ตัวสร้าง. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็น analog ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนนิ่งของประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | รับเวอร์ชันอ่านอย่างเดียวของปฏิทิน. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบ shared ตามค่าที่ระบุ. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | ตั้งค่าปีสุดท้ายที่สามารถแทนด้วยสองหลัก. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n'th เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบ shared. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ shared. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับการอ้างอิงแบบ shared. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | สร้างอ็อบเจ็กต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | สร้างอ็อบเจ็กต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | แปลงปีเป็นปีสี่หลักโดยใช้คุณสมบัติ TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็น analog ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [JulianEra](./julianera/) | ยุคจูเลียนปัจจุบัน. |

## ดูเพิ่มเติม

* คลาส [Calendar](../calendar/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)