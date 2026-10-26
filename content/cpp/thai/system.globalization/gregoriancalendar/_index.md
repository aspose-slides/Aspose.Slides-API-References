---
title: GregorianCalendar
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "Gregorian calendar. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 131
url: /th/system.globalization/gregoriancalendar/
---
## GregorianCalendar คลาส


Gregorian calendar. Objects of this คลาส should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this คลาส into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class GregorianCalendar : public System::Globalization::Calendar
```

## Methods

| Method | คำอธิบาย |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | เพิ่มวันไปยังจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | เพิ่มชั่วโมงไปยังจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | เพิ่มมิลลิวินาทีไปยังจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | เพิ่มนาทีไปยังจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | เพิ่มเดือนไปยังจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | เพิ่มวินาทีไปยังจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | เพิ่มสัปดาห์ไปยังจุดเวลา. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | เพิ่มปีไปยังจุดเวลา. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | ข้อมูล RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | สร้างสำเนาของอ็อบเจกต์ปัจจุบันและคืนค่า shared pointer ไปยังมัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่อะไรก็ตามรวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่อะไรก็ตามรวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | รับประเภทอัลกอริธึม. |
| virtual [GregorianCalendarTypes](../gregoriancalendartypes/) [get_CalendarType](./get_calendartype/)() const | รับประเภทปฏิทิน Gregorian. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | รับดัชนีของยุคปัจจุบัน. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | รับค่าของยุคปัจจุบัน. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | รับรายการของยุคที่มีอยู่ในปฏิทิน. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | ตรวจสอบว่าปฏิทินเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | จุดเวลามากสุดที่ปฏิทินรองรับ. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | จุดเวลาน้อยสุดที่ปฏิทินรองรับ. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | รับปีสุดท้ายที่สามารถแสดงด้วยสองหลักได้. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | รับวันของเดือนสำหรับจุดเวลาที่ระบุ. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | รับวันของสัปดาห์สำหรับจุดเวลาที่ระบุ. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | รับวันของปีสำหรับจุดเวลาที่ระบุ. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | รับจำนวนวันในเดือนที่ระบุ. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | รับจำนวนวันในเดือนที่ระบุ. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | รับจำนวนวันในเดือนที่ระบุ. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | รับจำนวนวันในปีที่ระบุ. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | รับจำนวนวันในปีที่ระบุ. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | รับจำนวนวันในปีที่ระบุ. |
| static [CalendarPtr](../calendarptr/) [GetDefaultInstance](./getdefaultinstance/)() | รับอินสแตนซ์ปฏิทิน Gregorian เริ่มต้น. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | รับยุคสำหรับจุดเวลาที่ระบุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อานาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจกต์แบบกำหนดเอง. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | รับชั่วโมงสำหรับจุดเวลาที่ระบุ. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | รับเดือน leap สำหรับปีที่ระบุ. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | รับเดือน leap สำหรับปีที่ระบุ. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | รับเดือน leap สำหรับปีที่ระบุ. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | รับมิลลิวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | รับนาทีสำหรับจุดเวลาที่ระบุ. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | รับเดือนสำหรับจุดเวลาที่ระบุ. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | รับจำนวนเดือนในปีที่ระบุ. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | ข้อมูล RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | ข้อมูล RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | รับวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. อานาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | รับสัปดาห์ของปีสำหรับจุดเวลาที่ระบุ. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | รับปีสำหรับจุดเวลาที่ระบุ. |
|  [GregorianCalendar](./gregoriancalendar/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | สร้างปฏิทิน Gregorian เฉพาะ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. อานาล็อกของตัวดำเนินการ C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | ตรวจสอบว่าวันนั้นเป็น leap หรือไม่. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | ตรวจสอบว่าวันนั้นเป็น leap หรือไม่. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | ตรวจสอบว่าวันนั้นเป็น leap หรือไม่. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | ตรวจสอบว่าเดือนนั้นเป็น leap หรือไม่. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | ตรวจสอบว่าเดือนนั้นเป็น leap หรือไม่. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | ตรวจสอบว่าเดือนนั้นเป็น leap หรือไม่. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | ตรวจสอบว่าปีนั้นเป็น leap หรือไม่. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | ตรวจสอบว่าปีนั้นเป็น leap หรือไม่. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | ตรวจสอบว่าปีนั้นเป็น leap หรือไม่. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | ตรวจสอบค่าปี, เดือน, วัน และยุค. |
| void [Lock](../../system/object/lock/)() | ทำงานเหมือนคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อานาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนนิ่งประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | รับเวอร์ชันอ่านอย่างเดียวของปฏิทิน. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr ด้วยการอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิง shared ลงตามค่าที่ระบุ. |
| virtual void [set_CalendarType](./set_calendartype/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | ตั้งค่าประเภทปฏิทิน Gregorian. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | ตั้งค่าปีสุดท้ายที่สามารถแสดงด้วยสองหลัก. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (ไม่ใช่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิง shared. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิง shared. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดตัวนับการอ้างอิง shared และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | สร้างอ็อบเจกต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | สร้างอ็อบเจกต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | สร้างอ็อบเจกต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | แปลงปีเป็นปีสี่หลักโดยใช้คุณสมบัติ TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อานาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานเหมือนการประกาศ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานเหมือนคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [ADEra](./adera/) | ยุคปัจจุบัน. |

## ดูเพิ่มเติม

* คลาส [Calendar](../calendar/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)