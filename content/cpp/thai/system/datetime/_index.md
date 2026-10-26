---
title: DateTime
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงค่าวันและเวลาที่ระบุบนสเกลเวลาต่อเนื่อง ประเภทนี้ควรจัดสรรบนสแตกและส่งให้ฟังก์ชันโดยค่าหรือด้วยการอ้างอิง ไม่ควรใช้คลาส System::SmartPtr เพื่อจัดการวัตถุของประเภทนี้"
type: docs
weight: 222
url: /th/system/datetime/
---
## DateTime คลาส

แสดงถึงค่าที่เป็นวันที่และเวลาเฉพาะบนต่อเนื่องของเวลา ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยอ้างอิง อย่าใช้ [System::SmartPtr](../smartptr/) คลาสเพื่อจัดการอ็อบเจกต์ของประเภทนี้.

```cpp
class DateTime
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งได้มาจากการบวกช่วงเวลาเฉพาะที่ระบุกับค่าที่เป็นวันที่และเวลาในวัตถุปัจจุบัน. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลรวมของค่าที่เป็นวันที่และเวลาในวัตถุปัจจุบันกับจำนวนวันที่ระบุ. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลรวมของค่าที่เป็นวันที่และเวลาในวัตถุปัจจุบันกับจำนวนชั่วโมงที่ระบุ. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลรวมของค่าที่เป็นวันที่และเวลาในวัตถุปัจจุบันกับจำนวนมิลลิวินาทีที่ระบุ. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลรวมของค่าที่เป็นวันที่และเวลาในวัตถุปัจจุบันกับจำนวนนาทีที่ระบุ. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลรวมของค่าที่เป็นวันที่และเวลาในวัตถุปัจจุบันกับจำนวนเดือนที่ระบุ. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลรวมของค่าที่เป็นวันที่และเวลาในวัตถุปัจจุบันกับจำนวนวินาทีที่ระบุ. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลรวมของค่าที่เป็นวันที่และ เวลาในวัตถุปัจจุบันกับจำนวนช่วงเวลา 100-นาโนวินาทีที่ระบุ. |
| [DateTime](./) [AddYears](./addyears/)(int) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลาเท่ากับค่าที่เป็นวันที่และเวลาในวัตถุปัจจุบันโดยเพิ่มส่วนปีขึ้นตามจำนวนที่ระบุ. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | เปรียบเทียบค่าทั้งสองที่แสดงโดยอินสแตนซ์ที่ระบุของ [DateTime](./) คลาสและส่งค่าที่ระบุตำแหน่งสัมพัทธ์ของค่าเหล่านั้นบนเส้นเวลา. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | เปรียบเทียบค่าที่เป็นวันที่และเวลาสองค่าโดยวัตถุปัจจุบันและอินสแตนซ์ที่ระบุของ [DateTime](./) คลาส และส่งค่าที่ระบุตำแหน่งสัมพัทธ์ของค่าเหล่านั้นบนเส้นเวลา. |
| constexpr [DateTime](./datetime/)() | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่เล็กที่สุดที่เป็นไปได้เท่ากับ MinValue. |
| [DateTime](./datetime/)(int, int, int) | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่ระบุเป็นปี, เดือน, และวันเฉพาะ. |
| [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่ระบุเป็นปี, เดือน, และวันในปฏิทินที่ระบุ. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่ระบุเป็นปี, เดือน, วัน, ชม., นาที, และวินาทีเฉพาะ. |
| [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่ระบุเป็นปี, เดือน, วัน, ชม., นาที, และวินาทีเฉพาะ. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่ระบุเป็นปี, เดือน, วัน, ชม., นาที, และวินาทีในปฏิทินที่ระบุ. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่ระบุเป็นปี, เดือน, วัน, ชม., นาที, วินาที และมิลลิวินาทีเฉพาะ. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่ระบุเป็นปี, เดือน, วัน, ชม., นาที, วินาที และมิลลิวินาทีในปฏิทินที่ระบุ. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่ระบุเป็นจำนวนติ๊ก. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | สร้างอินสแตนซ์ที่แสดงค่าที่เป็นวันที่และเวลาที่ระบุเป็นจำนวนติ๊ก ใช้ภายในเท่านั้น. |
| [DateTime](./datetime/)(const [DateTime](./)\&) | สร้างอินสแตนซ์โดยคัดลอก. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | คืนค่าจำนวนวันในเดือนที่ระบุของปีที่ระบุ. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | กำหนดว่ามีอินสแตนซ์ที่ระบุของ [DateTime](./) คลาสแสดงค่าที่เป็นวันที่และเวลาเดียวกันหรือไม่. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | กำหนดว่ามีอินสแตนซ์ที่ระบุของ [DateTime](./) คลาสแสดงค่าที่เป็นวันที่และเวลาเดียวกับวัตถุปัจจุบันหรือไม่. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | ทำการแปลงค่าที่เป็นวันที่และเวลาแบบ serialized จากจำนวนเต็มบวก 64 บิตที่ระบุและตั้งค่าอินสแตนซ์ใหม่ของ [DateTime](./) คลาสให้เป็นค่านั้น. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | แปลงค่าเวลาจากไฟล์ที่ระบุเป็นอินสแตนซ์ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลาเดียวกับเวลาท้องถิ่น. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | แปลงค่าเวลาจากไฟล์ที่ระบุเป็นอินสแตนซ์ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลาเดียวกับเวลา UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | คืนค่าอินสแตนซ์ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลาเทียบเท่ากับ OLE Automation Date ที่ระบุ. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | แปลงค่าเวลา Unix ที่ระบุเป็นอินสแตนซ์ของ [DateTime](./) คลาส ใช้ภายในเท่านั้น. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงส่วนวันที่ของวันที่และเวลาที่วัตถุปัจจุบันโดยตั้งค่าหน่วยของส่วนเวลาให้เป็น 0. |
| int [get_Day](./get_day/)() const | คืนค่าเลขลำดับของวันในเดือนที่วัตถุปัจจุบันแสดง. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | คืนค่าที่แสดงวันของสัปดาห์ที่วัตถุปัจจุบันแสดง. |
| int [get_DayOfYear](./get_dayofyear/)() const | คืนค่าเลขลำดับของวันในปีที่วัตถุปัจจุบันแสดง. |
| constexpr int [get_Hour](./get_hour/)() const | คืนค่าหน่วยชั่วโมงของค่าที่เป็นวันที่และเวลาที่วัตถุปัจจุบันแสดง. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | คืนค่าที่แสดงว่าค่าที่เป็นวันที่และเวลาที่วัตถุปัจจุบันเป็นเวลาท้องถิ่นหรือเวลามาตรฐาน UTC หรือไม่เป็นทั้งสองอย่าง. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | คืนค่าหน่วยมิลลิวินาทีของค่าที่เป็นวันที่และเวลาที่วัตถุปัจจุบันแสดง. |
| constexpr int [get_Minute](./get_minute/)() const | คืนค่าหน่วยนาทีของค่าที่เป็นวันที่และเวลาที่วัตถุปัจจุบันแสดง. |
| int [get_Month](./get_month/)() const | คืนค่าเลขลำดับของเดือนในปีที่วัตถุปัจจุบันแสดง. |
| static [DateTime](./) [get_Now](./get_now/)() | คืนค่าอินสแตนซ์ของ [DateTime](./) คลาสที่แสดงเวลาปัจจุบันเป็นเวลาท้องถิ่น. |
| constexpr int [get_Second](./get_second/)() const | คืนค่าหน่วยวินาทีของค่าที่เป็นวันที่และเวลาที่วัตถุปัจจุบันแสดง. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | คืนจำนวนช่วงเวลา 100-นาโนวินาทีที่ผ่านมาตั้งแต่เวลา 0:00:00 UTC, 1 มกราคม 0001 ตามปฏิทินเกรกอเรียนจนถึงวันที่และเวลาที่วัตถุปัจจุบันแสดง. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | คืนค่าที่แสดงช่วงเวลาตั้งแต่ต้นวันที่วัตถุปัจจุบันแสดงจนถึงค่าที่เป็นวันที่และเวลาที่วัตถุปัจจุบันแสดง. |
| static [DateTime](./) [get_Today](./get_today/)() | คืนค่าอินสแตนซ์ของ [DateTime](./) คลาสที่แสดงวันที่ปัจจุบันโดยตั้งค่าหน่วยของส่วนเวลาของค่าที่วัตถุแสดงเป็น 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | คืนค่าอินสแตนซ์ของ [DateTime](./) คลาสที่แสดงเวลาปัจจุบันเป็น UTC. |
| int [get_Year](./get_year/)() const | คืนค่าปีที่วัตถุปัจจุบันแสดง. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | ดึงส่วนของวันที่ ใช้ภายในเท่านั้น. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | คืนอาเรย์ของสตริงที่แต่ละองค์ประกอบเป็นการแสดงผลเป็นสตริงของวัตถุปัจจุบันโดยจัดรูปแบบด้วยหนึ่งในรูปแบบวันที่และเวลามาตรฐาน. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | คืนอาเรย์ของสตริงที่แต่ละองค์ประกอบเป็นการแสดงผลเป็นสตริงของวัตถุปัจจุบันโดยจัดรูปแบบด้วยรูปแบบวันที่และเวลามาตรฐานที่ระบุ. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | คืนอาเรย์ของสตริงที่แต่ละองค์ประกอบเป็นการแสดงผลเป็นสตริงของวัตถุปัจจุบันโดยจัดรูปแบบด้วยหนึ่งในรูปแบบวันที่และเวลามาตรฐานและผู้ให้รูปแบบที่ระบุ. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | คืนอาเรย์ของสตริงที่แต่ละองค์ประกอบเป็นการแสดงผลเป็นสตริงของวัตถุปัจจุบันโดยจัดรูปแบบด้วยรูปแบบวันที่และเวลามาตรฐานที่ระบุและผู้ให้รูปแบบ. |
| int [GetHashCode](./gethashcode/)() const | คืนค่าแฮชโค้ดของวัตถุปัจจุบัน. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | กำหนดว่าค่าที่เป็นวันที่และเวลาที่วัตถุปัจจุบันอยู่ในช่วงเวลาออมแสงของโซนเวลาปัจจุบันหรือไม่. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | กำหนดว่าปีที่ระบุเป็นปีอธิกสุรินทร์หรือไม่. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | กำหนดว่าวัตถุปัจจุบันและวัตถุ [DateTime](./) ที่ระบุแสดงค่าที่เป็นวันที่และเวลาที่แตกต่างกันหรือไม่. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลรวมของค่าที่วัตถุปัจจุบันแสดงกับช่วงเวลาที่ระบุ. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | กำหนดวัตถุปัจจุบันให้เป็นค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลรวมของค่าที่วัตถุปัจจุบันแสดงกับช่วงเวลาที่ระบุ. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | คืนค่าตัวอย่างใหม่ของ [DateTime](./) คลาสที่แสดงค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลลบของช่วงเวลาที่ระบุจากค่าที่วัตถุปัจจุบันแสดง. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | คืนค่าอินสแตนซ์ของ [TimeSpan](../timespan/) คลาสที่แสดงช่วงเวลาระหว่างค่าที่เป็นวันที่และเวลาที่วัตถุปัจจุบันและวัตถุที่ระบุ. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | กำหนดวัตถุปัจจุบันให้เป็นค่าที่เป็นวันที่และเวลา ซึ่งเป็นผลลบของช่วงเวลาที่ระบุจากค่าที่เป็นวันที่และเวลาที่วัตถุปัจจุบันแสดง. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | กำหนดว่าวัตถุปัจจุบันแสดงค่าที่เป็นวันที่และเวลาที่เกิดก่อนค่าที่วัตถุ [DateTime](./) ที่ระบุแสดงหรือไม่. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | กำหนดว่าวัตถุปัจจุบันแสดงค่าที่เป็นวันที่และเวลาที่เกิดก่อนหรือเท่ากับค่าที่วัตถุ [DateTime](./) ที่ระบุแสดงหรือไม่. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | กำหนดค่าที่แสดงโดยอินสแตนซ์ [DateTime](./) ที่ระบุให้กับวัตถุปัจจุบัน. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | กำหนดว่าวัตถุปัจจุบันและวัตถุ [DateTime](./) ที่ระบุแสดงค่าที่เป็นวันที่และเวลาเดียวกันหรือไม่. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | กำหนดว่าวัตถุปัจจุบันแทนค่าที่เป็นวันและเวลา ซึ่งอยู่หลังค่าที่แทนโดยวัตถุ [DateTime](./) ที่ระบุหรือไม่ |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | กำหนดว่าวัตถุปัจจุบันแทนค่าที่เป็นวันและเวลา ซึ่งอยู่หลังหรือเท่ากับค่าที่แทนโดยวัตถุ [DateTime](./) ที่ระบุหรือไม่ |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | แปลงการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่ระบุให้เป็นออบเจ็กต์ [DateTime](./) ที่เทียบเท่า |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | แปลงการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่ระบุให้เป็นออบเจ็กต์ [DateTime](./) ที่เทียบเท่าโดยใช้ข้อมูลรูปแบบตามวัฒนธรรม |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | แปลงการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่ระบุให้เป็นออบเจ็กต์ [DateTime](./) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุและข้อมูลรูปแบบตามวัฒนธรรม รูปแบบของสตริงต้องตรงกับรูปแบบที่ระบุอย่างแม่นยำ จะโยนข้อยกเว้นหากการแปลงล้มเหลว |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | แปลงการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่ระบุให้เป็นออบเจ็กต์ [DateTime](./) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุ, ข้อมูลรูปแบบตามวัฒนธรรมและสไตล์ รูปแบบของสตริงต้องตรงกับหนึ่งหรือหลายรูปแบบที่ระบุอย่างแม่นยำ จะโยนข้อยกเว้นหากการแปลงล้มเหลว |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | สร้างออบเจ็กต์ [DateTime](./) ใหม่ที่แทนจำนวน tick เดียวกันกับออบเจ็กต์ [DateTime](./) ที่ระบุและแทนเวลาท้องถิ่น, เวลามาตรฐาน UTC หรือไม่มีตามที่กำหนดโดยอาร์กูเมนต์ **kind** |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | คืนค่าอินสแตนซ์ใหม่ของคลาส [DateTime](./) ที่แทนค่าที่เป็นวันและเวลาซึ่งเป็นผลลัพธ์ของการลบช่วงเวลาเฉพาะที่ระบุจากค่าที่แทนโดยวัตถุปัจจุบัน |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | คืนค่าอินสแตนซ์ของคลาส [TimeSpan](../timespan/) ที่แทนช่วงเวลาระหว่างค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันและวัตถุที่ระบุ |
| **int64_t** [ToBinary](./tobinary/)() const | ทำการซีเรียลไลซ์วัตถุปัจจุบัน |
| **int64_t** [ToFileTime](./tofiletime/)() const | คืนค่าที่แทนค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันในรูปของ File time |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | แปลงค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันเป็น File time UTC |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | คืนค่าอินสแตนซ์ใหม่ของคลาส [DateTime](./) ที่แทนค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันในรูปของเวลาท้องถิ่น |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | คืนสตริงที่มีการแสดงผลวันแบบเต็มของวัตถุปัจจุบัน |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | คืนสตริงที่มีการแสดงผลเวลาแบบเต็มของวัตถุปัจจุบัน |
| **double** [ToOADate](./tooadate/)() const | คืนค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันในรูปของ OLE Automation Date |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | คืนสตริงที่มีการแสดงผลวันแบบสั้นของวัตถุปัจจุบัน |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | คืนสตริงที่มีการแสดงผลเวลาแบบสั้นของวัตถุปัจจุบัน |
| [String](../string/) [ToString](./tostring/)() const | คืนการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันโดยใช้รูปแบบตามขนบธรรมเนียมของวัฒนธรรมปัจจุบัน |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | คืนการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันโดยใช้รูปแบบที่ระบุและขนบธรรมเนียมการจัดรูปแบบของวัฒนธรรมปัจจุบัน |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | คืนการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันโดยใช้ข้อมูลรูปแบบที่ระบุ |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | คืนการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันโดยใช้ข้อมูลรูปแบบที่ระบุ |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | คืนค่าอินสแตนซ์ใหม่ของคลาส [DateTime](./) ที่แทนค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันในรูปของ UTC |
| time_t [ToUnixTime](./tounixtime/)() const | คืนค่าที่แทนค่าที่เป็นวันและเวลาที่แทนโดยวัตถุปัจจุบันในรูปของ Unix time. สำหรับการใช้งานภายใน |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | แปลงการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่ระบุให้เป็นออบเจ็กต์ [DateTime](./) ที่เทียบเท่า |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | แปลงการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่ระบุให้เป็นออบเจ็กต์ [DateTime](./) ที่เทียบเท่าโดยใช้ข้อมูลรูปแบบตามวัฒนธรรมที่ระบุและสไตล์ |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) const |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | แปลงการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่ระบุให้เป็นออบเจ็กต์ [DateTime](./) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุ, ข้อมูลรูปแบบตามวัฒนธรรมและสไตล์ รูปแบบของสตริงต้องตรงกับรูปแบบที่ระบุอย่างแม่นยำ |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) const |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) const |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) const |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | แปลงการแสดงผลสตริงของค่าที่เป็นวันและเวลาที่ระบุให้เป็นออบเจ็กต์ [DateTime](./) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุ, ข้อมูลรูปแบบตามวัฒนธรรมและสไตล์ รูปแบบของสตริงต้องตรงกับหนึ่งหรือหลายรูปแบบที่ระบุอย่างแม่นยำ |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) const |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) const |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | คืนออบเจ็กต์ [TypeInfo](../typeinfo/) ที่มีข้อมูลเกี่ยวกับคลาสนี้ |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | จำนวน 100-nanosecond ในช่วงเวลาระหว่างค่าที่เป็น [DateTime](./) ที่เป็นไปได้ต่ำสุดและสูงสุด |
| static [MaxValue](./maxvalue/) | อินสแตนซ์ของคลาส [DateTime](./) ที่แทนค่าที่เป็นวันและเวลาที่เป็นไปได้สูงสุด |
| static constexpr [MinTicks](./minticks/) | จำนวน tick ขั้นต่ำที่สุดที่อินสแตนซ์ของคลาส [DateTime](./) สามารถแทนได้ |
| static [MinValue](./minvalue/) | อินสแตนซ์ของคลาส [DateTime](./) ที่แทนค่าที่เป็นวันและเวลาที่เป็นไปได้ต่ำสุด |
| static constexpr [TicksPerDay](./ticksperday/) | จำนวน tick ในหนึ่งวัน |
| static constexpr [TicksPerHour](./ticksperhour/) | จำนวน tick ในหนึ่งชั่วโมง |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | จำนวน tick ในหนึ่งไมโครวินาที |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | จำนวน tick ในหนึ่งมิลลิวินาที |
| static constexpr [TicksPerMinute](./ticksperminute/) | จำนวน tick ในหนึ่งนาที |
| static constexpr [TicksPerSecond](./tickspersecond/) | จำนวน tick ในหนึ่งวินาที |
| static [UnixEpoch](./unixepoch/) | อินสแตนซ์ของคลาส [DateTime](./) ที่แทนจุดเริ่มต้นของ Unix epoch (1970.01.01 00:00:00) |

## หมายเหตุ



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // สร้างอินสแตนซ์ของคลาส 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // พิมพ์อินสแตนซ์ในหลายรูปแบบ.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## ดูเพิ่ม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)