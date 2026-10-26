---
title: EastAsianLunisolarCalendar
second_title: ใบอ้างอิง API Aspose.Slides สำหรับ C++
description: "ปฏิทินจันทรคติแบบเอเชียตะวันออก. อ็อบเจ็กต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บน stack หรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้ส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 105
url: /th/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar คลาส


East-asian lunisolar calendar. Objects of this คลาส should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this คลาส into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
```

## Methods

| วิธีการ | คำอธิบาย |
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
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | สร้างสำเนาของอ็อบเจ็กต์ปัจจุบันและคืนค่า shared pointer ไปยังมัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่งสองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่งสองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | ข้อมูล RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | รับดัชนีของสมัยปัจจุบัน. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | รับค่าของสมัยปัจจุบัน. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | รับรายการของสมัยที่มีอยู่ในปฏิทิน. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | รับตัวระบุของปฏิทิน. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | ตรวจสอบว่าปฏิทินเป็นแบบอ่านอย่างเดียวหรือไม่. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | จุดเวลามากสุดที่ปฏิทินสนับสนุน. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | จุดเวลาอย่างน้อยที่สุดที่ปฏิทินสนับสนุน. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | รับปีสุดท้ายที่สามารถแสดงด้วยสองหลักได้. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | รับส่วนต้นของดวงดาว. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | รับวันของเดือนสำหรับจุดเวลาที่ระบุ. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | รับวันของสัปดาห์สำหรับจุดเวลาที่ระบุ. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | รับวันของปีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | รับจำนวนวันในเดือนที่ระบุ. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | รับจำนวนวันในเดือนที่ระบุ. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | รับจำนวนวันในปีที่ระบุ. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | รับจำนวนวันในปีที่ระบุ. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | รับสมัยสำหรับจุดเวลาที่ระบุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | รับชั่วโมงสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | รับเดือนอธิกสุรทินสำหรับปีที่ระบุ. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | รับเดือนอธิกสุรทินสำหรับปีที่ระบุ. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | รับมิลลิวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | รับนาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | รับเดือนสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | รับจำนวนเดือนในปีที่ระบุ. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | รับจำนวนเดือนในปีที่ระบุ. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | รับวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | รับปีในรอบ 60 ปี (sexagenary cycle). |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | รับสาขาแผ่นดิน. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์. เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | รับสัปดาห์ของปีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | รับปีสำหรับจุดเวลาที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าหากอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นอเนกประสงค์ของตัวดำเนินการ C# 'is'. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | ตรวจสอบว่าวันเป็นวันอธิกสุรทินหรือไม่. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | ตรวจสอบว่าวันเป็นวันอธิกสุรทินหรือไม่. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรทินหรือไม่. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรทินหรือไม่. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | ตรวจสอบว่าปีเป็นปีอธิกสุรทินหรือไม่. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | ตรวจสอบว่าปีเป็นปีอธิกสุรทินหรือไม่. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | ตรวจสอบค่าปี, เดือน, วันและสมัย. |
| void [Lock](../../system/object/lock/)() | ใช้งานคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถทำการโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | รับเวอร์ชันอ่านอย่างเดียวของปฏิทิน. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิง shared ลงตามค่าที่ระบุ. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | ตั้งค่าปีสุดท้ายที่สามารถแสดงด้วยสองหลัก. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอากิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิง shared. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิง shared. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าการอ้างอิง shared. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | สร้างอ็อบเจ็กต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | สร้างอ็อบเจ็กต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | แปลงปีเป็นปีสี่หลักโดยใช้คุณสมบัติ TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ใช้งานคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Calendar](../calendar/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)