---
title: TimeSpan
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: "แสดงช่วงเวลาหนึ่ง ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านฟังก์ชันโดยค่า หรือโดยการอ้างอิง ไม่ควรใช้คลาส System::SmartPtr เพื่อจัดการออบเจ็กต์ของประเภทนี้."
type: docs
weight: 1314
url: /th/system/timespan/
---
## คลาส TimeSpan

แทนช่วงเวลาหนึ่ง ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านฟังก์ชันโดยค่า หรือโดยการอ้างอิง ห้ามใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการออบเจ็กต์ของประเภทนี้.

```cpp
class TimeSpan
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | ส่งคืนอินสแตนซ์ใหม่ของคลาส [TimeSpan](./) ที่แสดงช่วงเวลาที่เป็นผลรวมของช่วงเวลาที่ออบเจ็กต์ปัจจุบันและออบเจ็กต์ที่ระบุแสดง |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | เปรียบเทียบออบเจ็กต์ [TimeSpan](./) สองออบเจ็กต์ |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | เปรียบเทียบออบเจ็กต์ปัจจุบันกับออบเจ็กต์ที่ระบุ |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | เปรียบเทียบออบเจ็กต์ปัจจุบันกับออบเจ็กต์ที่ระบุ |
| [TimeSpan](./) [Duration](./duration/)() const | ส่งคืนอินสแตนซ์ใหม่ของออบเจ็กต์ [TimeSpan](./) ที่มีค่าเป็นค่าสัมบูรณ์ของออบเจ็กต์ปัจจุบัน |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | ตรวจสอบว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงเท่ากับช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่ |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | ตรวจสอบว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงเท่ากับช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่ |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | ส่งคืน true หากออบเจ็กต์ที่ระบุแสดงช่วงเวลาเดียวกัน, หากไม่ใช่จะส่งคืน false |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | ส่งคืนออบเจ็กต์ [TimeSpan](./) ใหม่ที่แสดงช่วงเวลาที่ระบุ |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | ส่งคืนออบเจ็กต์ [TimeSpan](./) ใหม่ที่แสดงช่วงเวลาที่ระบุ |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | ส่งคืนออบเจ็กต์ [TimeSpan](./) ใหม่ที่แสดงช่วงเวลาที่ระบุ |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | ส่งคืนออบเจ็กต์ [TimeSpan](./) ใหม่ที่แสดงช่วงเวลาที่ระบุ |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | ส่งคืนออบเจ็กต์ [TimeSpan](./) ใหม่ที่แสดงช่วงเวลาที่ระบุ |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | ส่งคืนออบเจ็กต์ [TimeSpan](./) ใหม่ที่แสดงช่วงเวลาที่ระบุ |
| constexpr int [get_Days](./get_days/)() const | ส่งคืนส่วนของวันจากช่วงเวลาที่ออบเจ็กต์ [TimeSpan](./) ปัจจุบัน |
| constexpr int [get_Hours](./get_hours/)() const | ส่งคืนส่วนของชั่วโมงจากช่วงเวลาที่ออบเจ็กต์ [TimeSpan](./) ปัจจุบัน |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | ส่งคืนส่วนของมิลลิวินาทีจากช่วงเวลาที่ออบเจ็กต์ [TimeSpan](./) ปัจจุบัน |
| constexpr int [get_Minutes](./get_minutes/)() const | ส่งคืนส่วนของนาทีจากช่วงเวลาที่ออบเจ็กต์ [TimeSpan](./) ปัจจุบัน |
| constexpr int [get_Seconds](./get_seconds/)() const | ส่งคืนส่วนของวินาทีจากช่วงเวลาที่ออบเจ็กต์ [TimeSpan](./) ปัจจุบัน |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | ส่งคืนจำนวนช่วงเวลา 100 นาโนวินาทีที่ประกอบเป็นช่วงเวลาที่ออบเจ็กต์ [TimeSpan](./) ปัจจุบัน |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | ส่งคืนค่าของออบเจ็กต์ [TimeSpan](./) ปัจจุบันที่แสดงเป็นจำนวนวันเต็มและส่วนเศษ |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | ส่งคืนค่าของออบเจ็กต์ [TimeSpan](./) ปัจจุบันที่แสดงเป็นจำนวนชั่วโมงเต็มและส่วนเศษ |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | ส่งคืนค่าของออบเจ็กต์ [TimeSpan](./) ปัจจุบันที่แสดงเป็นจำนวนมิลลิวินาทีเต็มและส่วนเศษ |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | ส่งคืนค่าของออบเจ็กต์ [TimeSpan](./) ปัจจุบันที่แสดงเป็นจำนวน นาทีเต็มและส่วนเศษ |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | ส่งคืนค่าของออบเจ็กต์ [TimeSpan](./) ปัจจุบันที่แสดงเป็นจำนวนวินาทีเต็มและส่วนเศษ |
| int [GetHashCode](./gethashcode/)() const | ส่งคืนค่าแฮชโค้ดของออบเจ็กต์ปัจจุบัน |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | ส่งคืนอินสแตนซ์ใหม่ของออบเจ็กต์ [TimeSpan](./) ที่แสดงค่าตรงข้ามของออบเจ็กต์ [TimeSpan](./) ปัจจุบัน |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | ตรวจสอบว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงไม่เท่ากับช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่ |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | ส่งคืนอินสแตนซ์ใหม่ของคลาส [TimeSpan](./) ที่แสดงช่วงเวลาที่เป็นผลรวมของช่วงเวลาที่ออบเจ็กต์ปัจจุบันและออบเจ็กต์ที่ระบุแสดง |
| [TimeSpan](./) [operator+](./operator_plus/)() const | ส่งคืนตัวเอง |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | กำหนดให้กับออบเจ็กต์ปัจจุบันช่วงเวลาที่เป็นผลรวมของช่วงเวลาที่ออบเจ็กต์ปัจจุบันและออบเจ็กต์ที่ระบุ |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | ส่งคืนอินสแตนซ์ใหม่ของคลาส [TimeSpan](./) ที่แสดงช่วงเวลาผลลัพธ์ของการลบช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงจากช่วงเวลาที่ออบเจ็กต์ปัจจุบัน |
| [TimeSpan](./) [operator-](./operator_minus/)() const | ส่งคืนอินสแตนซ์ใหม่ของออบเจ็กต์ [TimeSpan](./) ที่แสดงค่าตรงข้ามของออบเจ็กต์ [TimeSpan](./) ปัจจุบัน |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | กำหนดให้กับออบเจ็กต์ปัจจุบันช่วงเวลาที่เป็นผลลัพธ์ของการลบช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงจากออบเจ็กต์ปัจจุบัน |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | ตรวจสอบว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงสั้นกว่าช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่ |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | ตรวจสอบว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงสั้นกว่าหรือเท่ากับช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่ |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | กำหนดช่วงเวลาที่ออบเจ็กต์ [TimeSpan](./) ระบุให้เป็นค่าเดียวกับออบเจ็กต์ [TimeSpan](./) ปัจจุบัน |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | ตรวจสอบว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงเท่ากับช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่ |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | ตรวจสอบว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงยาวกว่าช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่ |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | ตรวจสอบว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงยาวกว่าหรือเท่ากับช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่ |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่า |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่าโดยใช้ผู้จัดรูปแบบที่ระบุ |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุ, ตัวจัดรูปแบบและสไตล์ |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุ, ตัวจัดรูปแบบและสไตล์ |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | ส่งคืนอินสแตนซ์ใหม่ของคลาส [TimeSpan](./) ที่แสดงช่วงเวลาผลลัพธ์ของการลบช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงจากช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดง |
| constexpr [TimeSpan](./timespan/)() | สร้างออบเจ็กต์ [TimeSpan](./) ที่แสดงช่วงเวลาเป็นศูนย์ |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | สร้างอินสแตนซ์ของคลาส [TimeSpan](./) ที่แสดงช่วงเวลาที่ระบุ |
|  [TimeSpan](./timespan/)(int, int, int) | สร้างอินสแตนซ์ของคลาส [TimeSpan](./) ที่แสดงช่วงเวลาซึ่งเท่ากับผลรวมของจำนวนชั่วโมง นาที และวินาทีที่ระบุ |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | สร้างอินสแตนซ์ของคลาส [TimeSpan](./) ที่แสดงช่วงเวลาซึ่งเท่ากับผลรวมของจำนวนชั่วโมง นาที วินาที และมิลลิวินาทีที่ระบุ |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | สร้างออบเจ็กต์ [TimeSpan](./) ที่แสดงช่วงเวลาที่เท่ากับช่วงเวลาที่ออบเจ็กต์ [TimeSpan](./) ระบุแสดง |
| [String](../string/) [ToString](./tostring/)() const | ส่งคืนการแสดงผลเป็นสตริงของช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดง |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | แปลงค่าของออบเจ็กต์ปัจจุบันเป็นสตริงที่เทียบเท่าโดยใช้รูปแบบที่ระบุ |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | แปลงค่าของออบเจ็กต์ปัจจุบันเป็นสตริงที่เทียบเท่าโดยใช้รูปแบบและผู้จัดรูปแบบที่ระบุ |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่าและส่งคืนผลลัพธ์ของการแปลง |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่าโดยใช้ผู้จัดรูปแบบที่ระบุและส่งคืนผลของการแปลง |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่าโดยใช้รูปแบบที่ระบุและผู้จัดรูปแบบ, แล้วส่งคืนผลการแปลง |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่าโดยใช้รูปแบบ, ผู้จัดรูปแบบและสไตล์ที่ระบุ, แล้วส่งคืนผลการแปลง |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่าโดยใช้รูปแบบ, ผู้จัดรูปแบบและสไตล์ที่ระบุ, แล้วส่งคืนผลการแปลง |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | แปลงสตริงเป็นออบเจ็กต์ [TimeSpan](./) ที่เทียบเท่าโดยใช้รูปแบบและผู้จัดรูปแบบ, แล้วส่งคืนผลการแปลง |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | ส่งคืนออบเจ็กต์ [TypeInfo](../typeinfo/) ที่แสดงโครงสร้าง [TimeSpan](./) |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [MaxValue](./maxvalue/) | ออบเจ็กต์ [TimeSpan](./) ที่แสดงช่วงเวลาที่ยาวที่สุดที่เป็นไปได้ |
| static [MinValue](./minvalue/) | /// ออบเจ็กต์ [TimeSpan](./) ที่แสดงช่วงเวลาที่สั้นที่สุดที่เป็นไปได้ |
| static constexpr [TicksPerDay](./ticksperday/) | จำนวนช่วงเวลา 100 นาโนวินาทีในหนึ่งวัน (ช่วงเวลา 24 ชั่วโมง) |
| static constexpr [TicksPerHour](./ticksperhour/) | จำนวนช่วงเวลา 100 นาโนวินาทีในหนึ่งชั่วโมง |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | จำนวนช่วงเวลา 100 นาโนวินาทีในหนึ่งมิลลิวินาที |
| static constexpr [TicksPerMinute](./ticksperminute/) | จำนวนช่วงเวลา 100 นาโนวินาทีในหนึ่งนาที |
| static constexpr [TicksPerSecond](./tickspersecond/) | จำนวนช่วงเวลา 100 นาโนวินาทีในหนึ่งวินาที |
| static [Zero](./zero/) | ออบเจ็กต์ [TimeSpan](./) ที่แสดงช่วงเวลาเป็นศูนย์ |

## หมายเหตุ

```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้แสดงผลลัพธ์ต่อไปนี้:
จำนวนติ๊ก: 260928000000000
จำนวนมิลลิวินาที: 0
จำนวนมิลลิวินาทีทั้งหมด: 2.60928e+10
จำนวนนาที: 0
จำนวนนาทีทั้งหมด: 434880
จำนวนชั่วโมง: 0
จำนวนชั่วโมงทั้งหมด: 0
จำนวนวัน: 302
จำนวนวันทั้งหมด: 302
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)