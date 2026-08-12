---
title: ChineseLunisolarCalendar
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ปฏิทินจันทรคติจีน. อ็อบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน System::MakeObject() เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการขัดจังหวะ assertion. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 27
url: /th/system.globalization/chineselunisolarcalendar/
---
## ChineseLunisolarCalendar คลาส

Chinese lunisolar calendar. Objects of this คลาส should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this คลาส into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ChineseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## เมธอด

| Method | คำอธิบาย |
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
|  [ChineseLunisolarCalendar](./chineselunisolarcalendar/)() | คอนสตรัคเตอร์เริ่มต้น. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | สร้างสำเนาของอ็อบเจ็กต์ปัจจุบันและคืนพอยน์เตอร์แชร์ให้กับมัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมสไตล์ C# ที่ในนั้น NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมสไตล์ C# ที่ในนั้น NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | ข้อมูล RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | รับดัชนีของยุคปัจจุบัน. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | รับค่าของยุคปัจจุบัน. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | รับรายการของยุคที่มีอยู่ในปฏิทิน. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | ตรวจสอบว่าปฏิทินเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | จุดเวลาสูงสุดที่ปฏิทินรองรับ. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | จุดเวลาขั้นต่ำที่ปฏิทินรองรับ. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | รับปีสุดท้ายที่สามารถแสดงด้วยสองหลักได้. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | รับลำดับฟากฟ้า. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมต่อกับอ็อบเจ็กต์. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | รับวันของเดือนสำหรับจุดเวลาที่ระบุ. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | รับวันของสัปดาห์สำหรับจุดเวลาที่ระบุ. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | รับวันของปีสำหรับจุดเวลาที่ระบุ. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | รับจำนวนวันในเดือนที่ระบุ. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | รับจำนวนวันในเดือนที่ระบุ. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | รับจำนวนวันในเดือนที่ระบุ. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | รับจำนวนวันในปีที่ระบุ. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | รับจำนวนวันในปีที่ระบุ. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | รับยุคสำหรับจุดเวลาที่ระบุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | รับชั่วโมงสำหรับจุดเวลาที่ระบุ. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | รับเดือนอธิกวันสำหรับปีที่ระบุ. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | รับเดือนอธิกวันสำหรับปีที่ระบุ. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | รับเดือนอธิกวันสำหรับปีที่ระบุ. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | รับมิลลิวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | รับนาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | รับเดือนสำหรับจุดเวลาที่ระบุ. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | รับจำนวนเดือนในปีที่ระบุ. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | ข้อมูล RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | ข้อมูล RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | รับวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | รับปีในรอบ 60 ปี. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | รับสาขาทางดิน. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | รับสัปดาห์ของปีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | รับปีสำหรับจุดเวลาที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นอนาล็อกของออปอเรเตอร์ 'is' ของ C#. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | ตรวจสอบว่าวันนั้นเป็นวันอธิกหรือไม่. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | ตรวจสอบว่าวันนั้นเป็นวันอธิกหรือไม่. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | ตรวจสอบว่าวันนั้นเป็นวันอธิกหรือไม่. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | ตรวจสอบว่าเดือนนั้นเป็นเดือนอธิกหรือไม่. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | ตรวจสอบว่าเดือนนั้นเป็นเดือนอธิกหรือไม่. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | ตรวจสอบว่าเดือนนั้นเป็นเดือนอธิกหรือไม่. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | ตรวจสอบว่าปีนั้นเป็นปีอธิกหรือไม่. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | ตรวจสอบว่าปีนั้นเป็นปีอธิกหรือไม่. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | ตรวจสอบว่าปีนั้นเป็นปีอธิกหรือไม่. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | ตรวจสอบค่าปี, เดือน, วันและยุค. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนชนิดกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกในซับคลาส. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกในซับคลาส. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | รับเวอร์ชันอ่านอย่างเดียวของปฏิทิน. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | ตั้งค่าปีสุดท้ายที่สามารถแสดงด้วยสองหลักได้. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็นพอยน์เตอร์อ่อน (แทนที่เป็นพอยน์เตอร์แชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์ให้เป็นโหมดอ่อน. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | สร้างอ็อบเจ็กต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | สร้างอ็อบเจ็กต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | แปลงปีเป็นปีสี่หลักโดยใช้คุณสมบัติ TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| Field | คำอธิบาย |
| --- | --- |
| static constexpr [ChineseEra](./chineseera/) | ยุคจีนปัจจุบัน. |

## ดูเพิ่มเติม

* คลาส [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)