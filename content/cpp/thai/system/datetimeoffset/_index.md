---
title: DateTimeOffset
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "บรรจุวันที่และเวลาในวันซึ่งสัมพันธ์กับ Coordinated Universal Time. ออบเจ็กต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้โอเปอเรเตอร์ new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 235
url: /th/system/datetimeoffset/
---
## DateTimeOffset คลาส

บรรจุวันที่และเวลาของวันที่สัมพันธ์กับเวลามาตรฐานสากล (Coordinated Universal Time). ออบเจ็กต์ของคลาสนี้ควรจัดสรรเฉพาะด้วยฟังก์ชัน [System::MakeObject()](../makeobject/). ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้โอเปอเรเตอร์ new เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด. หันคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

```cpp
class DateTimeOffset
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | เพิ่มช่วงเวลาเฉพาะที่กำหนดให้กับอ็อบเจ็กต์ [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | เพิ่มจำนวนวันที่ระบุให้กับอ็อบเจ็กต์ [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | เพิ่มจำนวนชั่วโมงที่ระบุให้กับอ็อบเจ็กต์ [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | เพิ่มจำนวนมิลลิวินาทีที่ระบุให้กับอ็อบเจ็กต์ [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | เพิ่มจำนวนนาทีที่ระบุให้กับอ็อบเจ็กต์ [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | เพิ่มจำนวนเดือนที่ระบุให้กับอ็อบเจ็กต์ [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | เพิ่มจำนวนวินาทีที่ระบุให้กับอ็อบเจ็กต์ [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | เพิ่มจำนวนทิกที่ระบุให้กับอ็อบเจ็กต์ [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | เพิ่มจำนวนปีที่ระบุให้กับอ็อบเจ็กต์ [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | เปรียบเทียบอ็อบเจ็กต์ [DateTimeOffset](./) สองตัว. |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | เปรียบเทียบอ็อบเจ็กต์ [DateTimeOffset](./) สองตัว. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | เปรียบเทียบอ็อบเจ็กต์ [DateTimeOffset](./) สองตัว. |
| constexpr [DateTimeOffset](./datetimeoffset/)() | คอนสตรัคเตอร์เริ่มต้น. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | คอนสตรัคเตอร์. |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | คอนสตรัคเตอร์. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | คอนสตรัคเตอร์. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | คอนสตรัคเตอร์. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | คอนสตรัคเตอร์. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | คอนสตรัคเตอร์. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | ตรวจสอบว่าอ็อบเจ็กต์ [DateTimeOffset](./) สองตัวแสดงจุดเวลาเดียวกันหรือไม่. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | ตรวจสอบว่าอ็อบเจ็กต์ [DateTimeOffset](./) สองตัวแสดงจุดเวลาเดียวกันหรือไม่. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | ตรวจสอบว่าอ็อบเจ็กต์ [DateTimeOffset](./) สองตัวแสดงจุดเวลาเดียวกันหรือไม่. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | ตรวจสอบว่าอ็อบเจ็กต์ [DateTimeOffset](./) สองตัวแสดงจุดเวลาเดียวกันและมีส่วนชดเชยเหมือนกันหรือไม่. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | ตรวจสอบว่าอ็อบเจ็กต์ [DateTimeOffset](./) สองตัวแสดงจุดเวลาเดียวกันและมีส่วนชดเชยเหมือนกันหรือไม่. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) เวลาไฟล์เป็นวันที่และเวลาโดยมีส่วนชดเชยเวลาท้องถิ่น. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time เป็นอ็อบเจ็กต์ [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time เป็นอ็อบเจ็กต์ [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | รับส่วนของวันที่ของออบเจ็กต์ปัจจุบัน. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | รับค่า [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | รับวันของเดือนของออบเจ็กต์ปัจจุบัน. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | รับวันของสัปดาห์ของออบเจ็กต์ปัจจุบัน. |
| int [get_DayOfYear](./get_dayofyear/)() const | รับวันของปีของออบเจ็กต์ปัจจุบัน. |
| int [get_Hour](./get_hour/)() const | รับส่วนของชั่วโมงของออบเจ็กต์ปัจจุบัน. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | รับค่า [DateTime](../datetime/) ที่แสดงวันที่และเวลาในท้องถิ่น. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | รับส่วนของมิลลิวินาทีของออบเจ็กต์ปัจจุบัน. |
| int [get_Minute](./get_minute/)() const | รับส่วนของนาทีของออบเจ็กต์ปัจจุบัน. |
| int [get_Month](./get_month/)() const | รับส่วนของเดือนของออบเจ็กต์ปัจจุบัน. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | รับ [DateTimeOffset](./) ที่วันที่และเวลาได้รับการตั้งเป็นเวลาท้องถิ่นปัจจุบันและส่วนชดเชยตั้งเป็นส่วนชดเชยของเวลาในท้องถิ่น. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | รับส่วนชดเชยจาก UTC. |
| constexpr int [get_Second](./get_second/)() const | รับส่วนของวินาทีของออบเจ็กต์ปัจจุบัน. |
| **int64_t** [get_Ticks](./get_ticks/)() const | รับจำนวนทิกของออบเจ็กต์ปัจจุบัน. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | รับเวลาของวันของออบเจ็กต์ปัจจุบัน. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | รับค่า [DateTime](../datetime/) ที่แสดงวันที่และเวลา UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | รับ [DateTimeOffset](./) ที่วันที่และเวลาได้รับการตั้งเป็นเวลาตาม UTC ปัจจุบันและส่วนชดเชยเป็น [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | รับจำนวนทิกของออบเจ็กต์ปัจจุบันในเวลา UTC. |
| int [get_Year](./get_year/)() const | รับส่วนของปีของออบเจ็กต์ปัจจุบัน. |
| int [GetHashCode](./gethashcode/)() const | รับค่าแฮชโค้ดของออบเจ็กต์ [DateTimeOffset](./) ปัจจุบัน. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | กำหนดว่าค่าออบเจ็กต์ปัจจุบันและออบเจ็กต์ [DateTimeOffset](./) ที่ระบุแสดงค่าของวันที่และเวลาที่แตกต่างกันหรือไม่. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Returns a new instance of [DateTimeOffset](./) class that represents the date and time value that is the sum of the value represented by the current object and the specified time span. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Returns a new instance of the [DateTimeOffset](./) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Returns an instance of [TimeSpan](../timespan/) class that represents the time interval between the date and time values represented by the current and the specified objects. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | กำหนดว่าค่าออบเจ็กต์ปัจจุบันแสดงค่าวันที่และเวลาที่เร็วกว่า ค่าที่แสดงโดยออบเจ็กต์ [DateTimeOffset](./) ที่ระบุหรือไม่. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | กำหนดว่าค่าออบเจ็กต์ปัจจุบันแสดงค่าวันที่และเวลาที่เร็วกว่าหรือเท่ากับค่าที่แสดงโดยออบเจ็กต์ [DateTimeOffset](./) ที่ระบุหรือไม่. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | กำหนดว่าออบเจ็กต์ปัจจุบันและออบเจ็กต์ [DateTimeOffset](./) ที่ระบุแสดงค่าวันที่และเวลาเดียวกันหรือไม่. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | กำหนดว่าค่าออบเจ็กต์ปัจจุบันแสดงค่าวันที่และเวลาที่ช้ากว่าค่าที่แสดงโดยออบเจ็กต์ [DateTimeOffset](./) ที่ระบุหรือไม่. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | กำหนดว่าค่าออบเจ็กต์ปัจจุบันแสดงค่าวันที่และเวลาที่ช้ากว่าหรือเท่ากับค่าที่แสดงโดยออบเจ็กต์ [DateTimeOffset](./) ที่ระบุหรือไม่. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงที่ระบุเป็นค่าเทียบเท่า [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | แปลงสตริงที่ระบุเป็นอ็อบเจ็กต์ [DateTimeOffset](./) โดยใช้ผู้จัดรูปแบบที่ระบุและสไตล์การจัดรูปแบบ. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | แปลงสตริงที่ระบุเป็นอ็อบเจ็กต์ [DateTimeOffset](./) โดยใช้รูปแบบ ผู้จัดรูปแบบและสไตล์การจัดรูปแบบที่ระบุ. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | แปลงสตริงที่ระบุเป็นอ็อบเจ็กต์ [DateTimeOffset](./) โดยใช้รูปแบบหลายแบบ ผู้จัดรูปแบบและสไตล์การจัดรูปแบบที่ระบุ. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | ลบช่วงเวลาเฉพาะที่ระบุออกจากออบเจ็กต์ปัจจุบัน. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | ลบค่า [DateTimeOffset](./) ที่ระบุออกจากออบเจ็กต์ปัจจุบัน. |
| **int64_t** [ToFileTime](./tofiletime/)() const | แปลงออบเจ็กต์ปัจจุบันเป็นเวลาไฟล์ [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | แปลงออบเจ็กต์ปัจจุบันเป็นอ็อบเจ็กต์ที่แสดงเวลาในท้องถิ่น,. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | แทนที่ส่วนชดเชยของออบเจ็กต์ปัจจุบันด้วยส่วนชดเชยที่ระบุ. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | แปลงออบเจ็กต์ปัจจุบันเป็นสตริงโดยใช้รูปแบบและผู้จัดรูปแบบที่ระบุ. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | แปลงออบเจ็กต์ปัจจุบันเป็นสตริงโดยใช้ผู้จัดรูปแบบที่ระบุ. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | แปลงออบเจ็กต์ปัจจุบันเป็นสตริงโดยใช้รูปแบบที่ระบุ. |
| [String](../string/) [ToString](./tostring/)() const | แปลงออบเจ็กต์ปัจจุบันเป็นสตริง. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | แปลงออบเจ็กต์ปัจจุบันเป็นอ็อบเจ็กต์ที่แสดงเวลา UTC,. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | รับจำนวนมิลลิวินาทีที่ผ่านตั้งแต่จุดเริ่มต้นของ Unix epoch. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | รับจำนวนวินาทีที่ผ่านตั้งแต่จุดเริ่มต้นของ Unix epoch. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | พยายามแปลงสตริงที่ระบุเป็นอ็อบเจ็กต์ [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | พยายามแปลงสตริงที่ระบุเป็นอ็อบเจ็กต์ [DateTimeOffset](./) โดยใช้ผู้จัดรูปแบบและสไตล์การจัดรูปแบบที่ระบุ. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | พยายามแปลงสตริงที่ระบุเป็นอ็อบเจ็กต์ [DateTimeOffset](./) โดยใช้หลายรูปแบบ ผู้จัดรูปแบบและสไตล์การจัดรูปแบบที่ระบุ. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | พยายามแปลงสตริงที่ระบุเป็นอ็อบเจ็กต์ [DateTimeOffset](./) โดยใช้รูปแบบ ผู้จัดรูปแบบและสไตล์การจัดรูปแบบที่ระบุ. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | ส่งคืนอ็อบเจ็กต์ [TypeInfo](../typeinfo/) ที่แสดงโครงสร้าง [TimeSpan](../timespan/). |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | รับส่วนชดเชยสูงสุดในหน่วยทิก. |
| static [MaxValue](./maxvalue/) | รับค่ามากที่สุดของ [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | รับส่วนชดเชยขั้นต่ำในหน่วยทิก. |
| static [MinValue](./minvalue/) | รับค่าที่เกิดขึ้นก่อนที่สุดของ [DateTimeOffset](./). |
| static [UnixEpoch](./unixepoch/) | รับจุดเริ่มต้นของ Unix epoch. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)