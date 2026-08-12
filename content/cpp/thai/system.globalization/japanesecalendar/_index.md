---
title: JapaneseCalendar
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ปฏิทินญี่ปุ่น. อ็อบเจกต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้งานและ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 183
url: /th/system.globalization/japanesecalendar/
---
## JapaneseCalendar คลาส

Japanese calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class JapaneseCalendar : public System::Globalization::Calendar
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | สร้างสำเนาของอ็อบเจกต์ปัจจุบันและคืนพอยเตอร์แบบ shared ให้. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบ floating point สไตล์ C# ที่ NaN สองค่า ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าหรือ NaN ใดๆ. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบ floating point สไตล์ C# ที่ NaN สองค่า ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าหรือ NaN ใดๆ. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | รับประเภทอัลกอริธึม. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | รับดัชนีของยุคปัจจุบัน. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | รับค่าของยุคปัจจุบัน. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | รับรายการของยุคที่มีอยู่ในปฏิทิน. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | ตรวจสอบว่าปฏิทินเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | จุดเวลาสูงสุดที่ปฏิทินรองรับ. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | จุดเวลาขั้นต่ำที่ปฏิทินรองรับ. |
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
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | รับยุคสำหรับจุดเวลาที่ระบุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อานาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์ที่กำหนดเอง. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | รับชั่วโมงสำหรับจุดเวลาที่ระบุ. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | รับเดือนอธิกสุรางค์สำหรับปีที่ระบุ. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | รับเดือนอธิกสุรางค์สำหรับปีที่ระบุ. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | รับเดือนอธิกสุรางค์สำหรับปีที่ระบุ. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | รับมิลลิวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | รับนาทีสำหรับจุดเวลาที่ระบุ. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | รับเดือนสำหรับจุดเวลาที่ระบุ. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | รับจำนวนเดือนในปีที่ระบุ. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | ข้อมูล RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | ข้อมูล RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | รับวินาทีสำหรับจุดเวลาที่ระบุ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. อานาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | รับสัปดาห์ของปีสำหรับจุดเวลาที่ระบุ. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | รับปีสำหรับจุดเวลาที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. อานาล็อกของโอเปอเรเตอร์ C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | ตรวจสอบว่าวันเป็นวันอธิกสุรณ์หรือไม่. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | ตรวจสอบว่าวันเป็นวันอธิกสุรณ์หรือไม่. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | ตรวจสอบว่าวันเป็นวันอธิกสุรณ์หรือไม่. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรณ์หรือไม่. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรณ์หรือไม่. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | ตรวจสอบว่าเดือนเป็นเดือนอธิกสุรณ์หรือไม่. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | ตรวจสอบว่าปีเป็นปีอธิกสุรณ์หรือไม่. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | ตรวจสอบว่าปีเป็นปีอธิกสุรณ์หรือไม่. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | ตรวจสอบว่าปีเป็นปีอธิกสุรณ์หรือไม่. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | ตรวจสอบค่าปี, เดือน, วันและยุค. |
|  [JapaneseCalendar](./japanesecalendar/)() | ตัวสร้าง. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อานาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คัดลอกคอนสตรัคเตอร์. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ในซับคลาส. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ในซับคลาส. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | รับเวอร์ชันอ่านอย่างเดียวของปฏิทิน. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบ shared ลงตามค่าที่ระบุ. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | ตั้งค่าปีสุดท้ายที่สามารถแสดงด้วยสองหลัก. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบ shared. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ shared. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงแบบ shared. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | สร้างอ็อบเจกต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | สร้างอ็อบเจกต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | สร้างอ็อบเจกต์ [DateTime](../../system/datetime/) จากส่วนประกอบ. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | แปลงปีเป็นปีสี่หลักโดยใช้คุณสมบัติ TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อานาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [Calendar](../calendar/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)