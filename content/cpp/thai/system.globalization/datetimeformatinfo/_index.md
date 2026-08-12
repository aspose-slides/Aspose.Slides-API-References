---
title: DateTimeFormatInfo
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ชุดของพารามิเตอร์การจัดรูปแบบวันที่และเวลา. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ผู้ดำเนินการ new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 66
url: /th/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo คลาส


ชุดของพารามิเตอร์การจัดรูปแบบวันที่และเวลา. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ผู้ดำเนินการ new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการยืนยัน. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ทำสำเนาข้อมูลรูปแบบ. |
|  [DateTimeFormatInfo](./datetimeformatinfo/)() | คอนสตรัคเตอร์เริ่มต้น, สร้างข้อมูลรูปแบบที่ไม่เปลี่ยนแปลง. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิด [Object.Equals](../../system/object/equals/) ของ C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าลอยตัวแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าลอยตัวแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | รับชื่อวันแบบย่อ. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | รับชื่อเดือนแบบย่อในรูปแบบสันธาน. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | รับชื่อเดือนแบบย่อ. |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | รับสัญลักษณ์ AM. |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | รับปฏิทินที่เชื่อมโยงกับตัวจัดรูปแบบ. |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | รับกฎสัปดาห์ของปฏิทินที่เชื่อมโยงกับตัวจัดรูปแบบ. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | รับตัวจัดรูปแบบวันที่และเวลาของเธรดปัจจุบัน. |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | รับตัวคั่นวันที่. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | รับชื่อวัน. |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | รับวันแรกของสัปดาห์. |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | รับรูปแบบวันที่และเวลาครบ. |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | รับตัวจัดรูปแบบวันที่และเวลาที่ไม่แปรผัน. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | ตรวจสอบว่าตัวจัดรูปแบบเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | รับรูปแบบวันที่แบบยาว. |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | รับรูปแบบเวลายาว. |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | รับรูปแบบวันของเดือน. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | รับชื่อเดือนในรูปแบบสันธาน. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | รับชื่อเดือน. |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | รับชื่อปฏิทินพื้นเมืองหากมี. |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | รับสัญลักษณ์ PM. |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | รับรูปแบบ RFC1123. |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | รับรูปแบบวันที่สั้น. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | รับชื่อวันที่สั้นที่สุดที่เป็นไปได้. |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | รับรูปแบบเวลาสั้น. |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | รับรูปแบบวันที่และเวลาที่เรียงลำดับได้. |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | รับตัวคั่นเวลา. |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | รับรูปแบบวันที่และเวลาที่เรียงลำดับสากล. |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | รับรูปแบบปีและเดือน. |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | รับชื่อวันสัปดาห์แบบย่อ. |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | รับชื่อยุคแบบย่อ. |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | รับชื่อเดือนแบบย่อ. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | รับรูปแบบทั้งหมดที่ค่าตัววันและเวลาอาจจัดรูปแบบได้. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | รับรูปแบบทั้งหมดที่ค่าตัววันและเวลาอาจจัดรูปแบบได้โดยใช้สตริงรูปแบบที่ระบุ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | รับชื่อวันสัปดาห์. |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | รับยุคตามชื่อ. |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | รับชื่อยุค. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | รับตัวจัดรูปแบบของประเภทเฉพาะ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเคียงของเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C#. ทำให้สามารถทำแฮชของวัตถุกำหนดเองได้. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | รับตัวจัดรูปแบบที่เชื่อมโยงกับผู้ให้รูปแบบ. |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | รับชื่อเดือนปีอธิษฐาน. |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | รับชื่อเดือนในรูปแบบสันธาน. |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | รับชื่อเดือน. |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | รับชื่อตัวย่อของวันสัปดาห์ที่ระบุ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นเทียบเคียงของการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นเทียบเคียงของตัวดำเนินการ 'is' ของ C#. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเทียบเคียงของเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. ทำให้สามารถทำสำเนาประเภทกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดให้ซับคลาสสร้างโดยคัดลอกได้. |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดให้ซับคลาสสร้างโดยคัดลอกได้. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | รับเวอร์ชันอ่านอย่างเดียวของตัวจัดรูปแบบ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | ตั้งค่าชื่อวันแบบย่อ. |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | ตั้งค่าชื่อเดือนแบบย่อในรูปแบบสันธาน. |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | ตั้งค่าชื่อเดือนแบบย่อ. |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | ตั้งค่าสัญลักษณ์ AM. |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | ตั้งค่าปฏิทินที่เชื่อมโยงกับตัวจัดรูปแบบ. |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | ตั้งค่ากฎสัปดาห์ของปฏิทินที่เชื่อมโยงกับตัวจัดรูปแบบ. |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | ตั้งค่าตัวคั่นวันที่. |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | ตั้งค่าชื่อวัน. |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | ตั้งค่าวันแรกของสัปดาห์. |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | ตั้งค่ารูปแบบวันที่และเวลาครบ. |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | ตั้งค่ารูปแบบวันที่แบบยาว. |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | ตั้งค่ารูปแบบเวลายาว. |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | ตั้งค่ารูปแบบวันของเดือน. |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | ตั้งค่าชื่อเดือนในรูปแบบสันธาน. |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | ตั้งค่าชื่อเดือน. |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | ตั้งค่าสัญลักษณ์ PM. |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | ตั้งค่ารูปแบบวันที่สั้น. |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | ตั้งค่าชื่อวันที่สั้นที่สุดที่เป็นไปได้. |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | ตั้งค่ารูปแบบเวลาสั้น. |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | ตั้งค่าตัวคั่นเวลา. |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | ตั้งค่ารูปแบบปีและเดือน. |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | ตั้งค่ารูปแบบสำหรับรูปแบบที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนท์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเทียบเคียงของเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. ทำให้สามารถแปลงวัตถุกำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการดำเนินการ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อคของคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* คลาส [IFormatProvider](../../system/iformatprovider/)
* คลาส [ICloneable](../../system/icloneable/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)