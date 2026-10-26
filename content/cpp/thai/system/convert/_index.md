---
title: Convert
second_title: Aspose.Slides สำหรับ API ของ C++
description: "โครงสร้างที่ประกอบด้วยเมธอดที่ทำการแปลงค่าจากประเภทหนึ่งเป็นค่าของประเภทอื่น ประเภทนี้ควรจัดสรรบนสแต็กและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง ไม่ควรใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจ็กต์ของประเภทนี้"
type: docs
weight: 1561
url: /th/system/convert/
---
## แปลง struct

โครงสร้างที่ประกอบด้วยเมธอดสำหรับทำการแปลงค่าจากประเภทหนึ่งเป็นค่าของประเภทอื่น ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง อย่าใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการอ็อบเจกต์ของประเภทนี้.

```cpp
class Convert
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | ยังไม่ได้ดำเนินการ. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | ถอดรหัสข้อมูลที่เข้ารหัสแบบ base-64 ที่เป็นช่วงในอาร์เรย์ของอักขระ Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | ถอดรหัสข้อมูลที่เข้ารหัสแบบ base-64 ที่เป็นสตริง. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | ส่งค่าชนิด TypeCode ที่แสดงถึงประเภทของค่าที่บรรจุไว้ที่ระบุ. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | ยังไม่ได้ดำเนินการ. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | ยังไม่ได้ดำเนินการ การจำลองการทำงาน ตรวจสอบว่าค่าเป็น nullptr หรือไม่. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | เข้ารหัส base-64 ช่วงของอิลิเมนต์ในอาร์เรย์ไบต์ที่ระบุและเก็บข้อมูลที่เข้ารหัสเป็นอาร์เรย์ของอักขระ Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | เข้ารหัส base-64 ช่วงของอิลิเมนต์ในอาร์เรย์ไบต์ที่ระบุและเก็บข้อมูลที่เข้ารหัสเป็นอาร์เรย์ของอักขระ Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | เข้ารหัส base-64 อิลิเมนต์ในอาร์เรย์ไบต์ที่ระบุและคืนข้อมูลที่เข้ารหัสเป็นสตริง. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | เข้ารหัส base-64 อิลิเมนต์ในอาร์เรย์ไบต์ที่ระบุและคืนข้อมูลที่เข้ารหัสเป็นสตริง. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | เข้ารหัส base-64 อิลิเมนต์ในอาร์เรย์ไบต์ที่ระบุและคืนข้อมูลที่เข้ารหัสเป็นสตริง. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | เข้ารหัส base-64 อิลิเมนต์ในอาร์เรย์ไบต์ที่ระบุและคืนข้อมูลที่เข้ารหัสเป็นสตริง. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | คืนค่าบูลีนที่ระบุ. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | แปลงจำนวนเต็มบวก 8-bit ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 8-bit ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | แปลงจำนวนเต็มบวก 16-bit ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 16-bit ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | แปลงจำนวนเต็มบวก 32-bit ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 32-bit ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | แปลงจำนวนเต็มบวก 64-bit ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 64-bit ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | แปลงเลข float ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | แปลงเลข double ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | แปลงจำนวนทศนิยมที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | แปลงสตริง null ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | แปลง c-string ที่ระบุเป็นค่าชนิด bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | แปลงสตริงที่ระบุเป็นค่าชนิด bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุเป็นค่าชนิด bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บรรจุไว้ที่ระบุเป็นค่าบูลีนที่เท่าเทียม. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | แปลงค่าบูลีนที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | คืนจำนวนเต็มบวก 8-bit ที่ระบุ. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 8-bit ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | แปลงจำนวนเต็มบวก 16-bit ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 16-bit ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | แปลงจำนวนเต็มบวก 32-bit ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 32-bit ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | แปลงจำนวนเต็มบวก 64-bit ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 64-bit ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | แปลงเลข float ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | แปลงเลข double ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | แปลงจำนวนทศนิยมที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | แปลงอักขระ Unicode ที่ระบุเป็นจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | แปลงสตริง null ที่ระบุเป็นค่าจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | แปลง c-string ที่มีการแสดงผลเป็นตัวเลขเป็นค่าจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | แปลงสตring ที่มีการแสดงผลเป็นตัวเลขเป็นค่าจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | แปลงสตring ที่มีการแสดงผลเป็นตัวเลขในฐานที่ระบุเป็นค่าจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตring ที่มีการแสดงผลเป็นตัวเลขเป็นค่าจำนวนเต็มบวก 8-bit ที่เท่าเทียมโดยใช้ข้อมูลการฟอร์แมตที่ให้มา. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตring ที่มีการแสดงผลเป็นตัวเลขเป็นค่าจำนวนเต็มบวก 8-bit ที่เท่าเทียมโดยใช้ข้อมูลการฟอร์แมตและสไตล์ตัวเลขที่ให้มา. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บรรจุไว้ที่ระบุเป็นค่าจำนวนเต็มบวก 8-bit ที่เท่าเทียม. |
| static char_t [ToChar](./tochar/)(**bool**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | แปลงจำนวนเต็มบวก 8-bit ที่ระบุเป็นอักขระ Unicode ที่เท่าเทียม. |
| static char_t [ToChar](./tochar/)(**int8_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 8-bit ที่ระบุเป็นอักขระ Unicode ที่เท่าเทียม. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | แปลงจำนวนเต็มบวก 16-bit ที่ระบุเป็นอักขระ Unicode ที่เท่าเทียม. |
| static char_t [ToChar](./tochar/)(**int16_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 16-bit ที่ระบุเป็นอักขระ Unicode ที่เท่าเทียม. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | แปลงจำนวนเต็มบวก 32-bit ที่ระบุเป็นอักขระ Unicode ที่เท่าเทียม. |
| static char_t [ToChar](./tochar/)(**int32_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 32-bit ที่ระบุเป็นอักขระ Unicode ที่เท่าเทียม. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | แปลงจำนวนเต็มบวก 64-bit ที่ระบุเป็นอักขระ Unicode ที่เท่าเทียม. |
| static char_t [ToChar](./tochar/)(**int64_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 64-bit ที่ระบุเป็นอักขระ Unicode ที่เท่าเทียม. |
| static char_t [ToChar](./tochar/)(**float**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static char_t [ToChar](./tochar/)(**double**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | คืนอักขระ Unicode ที่ระบุ. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static char_t [ToChar](./tochar/)(const char_t *) | แปลงอักขระแรกและอักขระเดียวของ c-string ที่ระบุเป็นค่า char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | แปลงอักขระแรกและอักขระเดียวของสตring ที่ระบุเป็นค่า char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงอักขระแรกและอักขระเดียวของสตring ที่ระบุเป็นค่า char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บรรจุไว้ที่ระบุเป็นอักขระ Unicode ที่เท่าเทียม. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | ส่งคืนวันที่และเวลาที่ระบุ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | แปลงสตริงที่ระบุเป็นอินสแตนซ์ของคลาส [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุเป็นอินสแตนซ์ของคลาส [DateTime](../datetime/) โดยใช้ข้อมูลการจัดรูปแบบที่ระบุ. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บ็อกซ์ที่ระบุให้เป็นค่า [DateTime](../datetime/) ที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | แปลงค่าบูลีนที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | แปลงจำนวนเต็มบวก 8 บิตที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | แปลงจำนวนเต็มลบ 8 บิตที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | แปลงจำนวนเต็มบวก 16 บิตที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | แปลงจำนวนเต็มลบ 16 บิตที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | แปลงจำนวนเต็มบวก 32 บิตที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | แปลงจำนวนเต็มลบ 32 บิตที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | แปลงจำนวนเต็มบวก 64 บิตที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | แปลงจำนวนเต็มลบ 64 บิตที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | แปลงจำนวน float ที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | แปลงจำนวน double ที่ระบุเป็นจำนวนฐานสิบที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | ส่งคืนจำนวนฐานสิบที่ระบุ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | แปลง null-string ที่ระบุให้เป็นค่า [Decimal](../decimal/) ที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | แปลง c-string ที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า [Decimal](../decimal/) ที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า [Decimal](../decimal/) ที่เทียบเท่า. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า [Decimal](../decimal/) ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า [Decimal](../decimal/) ที่เทียบเท่าโดยใช้รูปแบบตัวเลขและข้อมูลการจัดรูปแบบที่ระบุ. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บ็อกซ์ที่ระบุให้เป็นค่า [Decimal](../decimal/) ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | แปลงค่าบูลีนที่ระบุเป็นจำนวนจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | แปลงจำนวนเต็มบวก 8 บิตที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | แปลงจำนวนเต็มลบ 8 บิตที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | แปลงจำนวนเต็มบวก 16 บิตที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | แปลงจำนวนเต็มลบ 16 บิตที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | แปลงจำนวนเต็มบวก 32 บิตที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | แปลงจำนวนเต็มลบ 32 บิตที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | แปลงจำนวนเต็มบวก 64 บิตที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | แปลงจำนวนเต็มลบ 64 บิตที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | แปลงจำนวนแบบ single-precision ที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | ส่งคืนจำนวน double ที่ระบุ. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | แปลงจำนวนฐานสิบที่ระบุเป็นจำนวนจริงแบบ double-precision ที่เทียบเท่า. |
| static **double** [ToDouble](./todouble/)(char_t) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | แปลง null-string ที่ระบุให้เป็นค่า double-precision floating-point ที่เทียบเท่า. |
| static **double** [ToDouble](./todouble/)(const char_t *) | แปลง c-string ที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า double-precision floating-point ที่เทียบเท่า. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า double-precision floating-point ที่เทียบเท่า. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า double-precision floating-point ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า double-precision floating-point ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ระบุ. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บ็อกซ์ที่ระบุให้เป็นค่า double-precision floating-point หากประเภทของค่าที่บ็อกซ์คือ [String](../string/) จะใช้รูปแบบสตริงที่ระบุระหว่างการแปลง. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | แปลงค่าบูลีนที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | แปลงจำนวนเต็มบวก 8 บิตที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | แปลงจำนวนเต็มลบ 8 บิตที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | แปลงจำนวนเต็มบวก 16 บิตที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | ส่งคืนจำนวนเต็ม 16-bit signed ที่ระบุ. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | แปลงจำนวนเต็มบวก 32 บิตที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | แปลงจำนวนเต็มลบ 32 บิตที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | แปลงจำนวนเต็มบวก 64 บิตที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | แปลงจำนวนเต็มลบ 64 บิตที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | แปลงจำนวน float ที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | แปลงจำนวน double ที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | แปลงจำนวนฐานสิบที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | แปลงอักขระยูนิโค้ดที่ระบุเป็นจำนวนเต็ม 16-bit signed ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | แปลง null-string ที่ระบุให้เป็นค่าจำนวนเต็ม 16-bit ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | แปลง c-string ที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า จำนวนเต็ม 16-bit ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า จำนวนเต็ม 16-bit ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขในฐานที่ระบุให้เป็นค่า จำนวนเต็ม 16-bit ที่เทียบเท่า. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า 16-bit signed ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งเป็นการแทนค่าเลขเป็นสตริงให้เป็นค่า 16-bit signed ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ระบุ. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บ็อกซ์ที่ระบุให้เป็นค่า 16-bit integer ที่เทียบเท่า. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | แปลงค่าบูลีนที่ระบุเป็นจำนวนเต็ม 32-bit signed ที่เทียบเท่า. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | แปลงจำนวนเต็มบวก 8 บิตที่ระบุเป็นจำนวนเต็ม 32-bit signed ที่เทียบเท่า. |

| static constexpr int [ToInt32](./toint32/)(**int8_t**) | แปลงจำนวนเต็ม signed 8 บิตที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | แปลงจำนวนเต็มไม่เป็นลบ 16 บิตที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | แปลงจำนวนเต็ม signed 16 บิตที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static int [ToInt32](./toint32/)(**uint32_t**) | แปลงจำนวนเต็มไม่เป็นลบ 32 บิตที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | คืนค่า จำนวนเต็ม signed 32 บิตที่ระบุ. |
| static int [ToInt32](./toint32/)(**uint64_t**) | แปลงจำนวนเต็มไม่เป็นลบ 64 บิตที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static int [ToInt32](./toint32/)(**int64_t**) | แปลงจำนวนเต็ม signed 64 บิตที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static int [ToInt32](./toint32/)(**float**) | แปลงจำนวนจริงแบบ float ที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static int [ToInt32](./toint32/)(**double**) | แปลงจำนวนจริงแบบ double ที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | แปลงจำนวนทศนิยมที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static constexpr int [ToInt32](./toint32/)(char_t) | แปลงอักขระยูนิโค้ดที่ระบุให้เป็นจำนวนเต็ม signed 32 บิตที่เทียบเท่า. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | แปลงสตริง null ที่ระบุให้เป็นค่า 32-bit integer ที่เทียบเท่า. |
| static int [ToInt32](./toint32/)(const char_t *) | แปลง c-string ที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 32-bit integer ที่เทียบเท่า. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 32-bit integer ที่เทียบเท่า. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขในฐานที่ระบุให้เป็นค่า 32-bit integer ที่เทียบเท่า. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 32-bit integer ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 32-bit integer ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ระบุ. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าชนิด boxed ที่ระบุให้เป็นค่า 32-bit integer ที่เทียบเท่า. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | แปลงค่าบูลีนที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | แปลงจำนวนเต็มไม่เป็นลบ 8 บิตที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | แปลงจำนวนเต็ม signed 8 บิตที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | แปลงจำนวนเต็มไม่เป็นลบ 16 บิตที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | แปลงจำนวนเต็ม signed 16 บิตที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | แปลงจำนวนเต็มไม่เป็นลบ 32 บิตที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | แปลงจำนวนเต็ม signed 32 บิตที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | แปลงจำนวนเต็มไม่เป็นลบ 64 บิตที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | คืนค่า จำนวนเต็ม signed 64 บิตที่ระบุ. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | แปลงจำนวนจริงแบบ float ที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | แปลงจำนวนจริงแบบ double ที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | แปลงจำนวนทศนิยมที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | แปลงอักขระยูนิโค้ดที่ระบุให้เป็นจำนวนเต็ม signed 64 บิตที่เทียบเท่า. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | แปลงสตริง null ที่ระบุให้เป็นค่า int 64-bit integer ที่เทียบเท่า. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | แปลง c-string ที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 64-bit integer ที่เทียบเท่า. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 64-bit integer ที่เทียบเท่า. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขในฐานที่ระบุให้เป็นค่า 64-bit integer ที่เทียบเท่า. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 64-bit integer ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 64-bit integer ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ระบุ. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าชนิด boxed ที่ระบุให้เป็นค่า 64-bit integer ที่เทียบเท่า. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | แปลงค่าบูลีนที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | แปลงจำนวนเต็มไม่เป็นลบ 8 บิตที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | คืนค่า จำนวนเต็ม signed 8 บิตที่ระบุ. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | แปลงจำนวนเต็มไม่เป็นลบ 16 บิตที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | แปลงจำนวนเต็ม signed 16 บิตที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | แปลงจำนวนเต็มไม่เป็นลบ 32 บิตที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | แปลงจำนวนเต็ม signed 32 บิตที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | แปลงจำนวนเต็มไม่เป็นลบ 64 บิตที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | แปลงจำนวนเต็ม signed 64 บิตที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | แปลงจำนวนจริงแบบ float ที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | แปลงจำนวนจริงแบบ double ที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | แปลงจำนวนทศนิยมที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | แปลงอักขระยูนิโค้ดที่ระบุให้เป็นจำนวนเต็ม signed 8 บิตที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | การแปลงไม่รองรับ เสมอจะโยน InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | แปลงสตริง null ที่ระบุให้เป็นค่า 8-bit integer ที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | แปลง c-string ที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 8-bit integer ที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 8-bit integer ที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขในฐานที่ระบุให้เป็นค่า 8-bit integer ที่เทียบเท่า. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า unsigned 8-bit integer ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงผลเป็นสตริงของตัวเลขให้เป็นค่า 8-bit integer ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ระบุ. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าชนิด boxed ที่ระบุให้เป็นค่า 8-bit integer ที่เทียบเท่า. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | แปลงค่าบูลีนที่ระบุให้เป็นจำนวนเลขจุดลอยความแม่นยำเดี่ยวที่เทียบเท่า. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | แปลงจำนวนเต็มไม่เป็นลบ 8 บิตที่ระบุให้เป็นจำนวนเลขจุดลอยความแม่นยำเดี่ยวที่เทียบเท่า. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | แปลงจำนวนเต็ม signed 8 บิตที่ระบุให้เป็นจำนวนเลขจุดลอยความแม่นยำเดี่ยวที่เทียบเท่า. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | แปลงจำนวนเต็มไม่เป็นลบ 16 บิตที่ระบุให้เป็นจำนวนเลขจุดลอยความแม่นยำเดี่ยวที่เทียบเท่า. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | แปลงจำนวนเต็ม signed 16 บิตที่ระบุให้เป็นจำนวนเลขจุดลอยความแม่นยำเดี่ยวที่เทียบเท่า. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | แปลงจำนวนเต็มไม่เป็นลบ 32 บิตที่ระบุให้เป็นจำนวนเลขจุดลอยความแม่นยำเดี่ยวที่เทียบเท่า. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | แปลงจำนวนเต็ม signed 32 บิตที่ระบุให้เป็นจำนวนเลขจุดลอยความแม่นยำเดี่ยวที่เทียบเท่า. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | แปลงจำนวนเต็มบวก 64-บิตที่ระบุให้เป็นจำนวนจริงแบบจุดลอยเดี่ยวความแม่นยำเดียวกัน |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | แปลงจำนวนเต็มมีเครื่องหมาย 64-บิตที่ระบุให้เป็นจำนวนจริงแบบจุดลอยเดี่ยวความแม่นยำเดียวกัน |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | คืนค่าตัวเลข float ที่ระบุ |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | แปลงตัวเลขแบบ double-precision ที่ระบุให้เป็นจำนวนจริงแบบจุดลอยเดี่ยวความแม่นยำเดียวกัน |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | แปลงจำนวน decimal ที่ระบุให้เป็นจำนวนจริงแบบจุดลอยเดี่ยวความแม่นยำเดียวกัน |
| static **float** [ToSingle](./tosingle/)(char_t) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | ไม่รองรับการแปลง จะทำให้เกิด InvalidCastException เสมอ |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | แปลงสตริงค่า null ที่ระบุให้เป็นค่าจุดลอยเดี่ยวความแม่นยำเดียวกัน |
| static **float** [ToSingle](./tosingle/)(const char_t *) | แปลง c-string ที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นค่าจุดลอยเดี่ยวความแม่นยำเดียวกัน |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นค่าจุดลอยเดี่ยวความแม่นยำเดียวกัน |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นค่าจุดลอยเดี่ยวความแม่นยำเดียวกันโดยใช้ข้อมูลการจัดรูปแบบที่ให้ไว้ |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแทนค่าตัวเลขเป็นสตริงให้เป็นค่าจุดลอยเดี่ยวความแม่นยำเดียวกันโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ให้ไว้ |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บรรจุในกล่องให้เป็นค่าจุดลอยเดี่ยวความแม่นยำเดียวกัน |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**float**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**double**) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | แปลงค่าที่ระบุให้เป็นสตริง |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรม |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรมที่จัดให้โดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/) ที่ระบุ |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรมที่จัดให้โดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/) ที่ระบุ |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรมที่จัดให้โดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/) ที่ระบุ |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรมที่จัดให้โดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/) ที่ระบุ |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรมที่จัดให้โดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/) ที่ระบุ |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุให้เป็นสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบเฉพาะวัฒนธรรมที่จัดให้โดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/) ที่ระบุ |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุเป็นตัวแทนในรูปแบบสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบตามวัฒนธรรมที่กำหนดโดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุเป็นตัวแทนในรูปแบบสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบตามวัฒนธรรมที่กำหนดโดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุเป็นตัวแทนในรูปแบบสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบตามวัฒนธรรมที่กำหนดโดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุเป็นตัวแทนในรูปแบบสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบตามวัฒนธรรมที่กำหนดโดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุเป็นตัวแทนในรูปแบบสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบตามวัฒนธรรมที่กำหนดโดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่ระบุเป็นตัวแทนในรูปแบบสตริงโดยใช้รูปแบบสตริงที่ระบุและข้อมูลการจัดรูปแบบตามวัฒนธรรมที่กำหนดโดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | แปลงค่าที่ระบุเป็นสตริง. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | แปลงค่าที่ระบุเป็นสตริงโดยใช้รูปแบบสตริงที่ระบุ. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | แปลงอาเรย์ของอักขระยูนิโค้ดที่ระบุเป็นสตริง. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงอาเรย์ของอักขระยูนิโค้ดที่ระบุเป็นสตริงโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุโดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | คืนค่าที่ระบุ; ไม่ได้ทำการแปลงค่า. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | แปลงค่าบูลีนที่ระบุเป็นตัวแทนในรูปแบบสตริง. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าบูลีนที่ระบุเป็นตัวแทนในรูปแบบสตริง. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | แปลงค่าบูลีนที่ระบุเป็นตัวแทนในรูปแบบสตริง. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | แปลงค่าบูลีนที่ระบุเป็นตัวแทนในรูปแบบสตริง. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าบูลีนที่ระบุเป็นตัวแทนในรูปแบบสตริง. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | แปลงค่าบูลีนที่ระบุเป็นตัวแทนในรูปแบบสตริง. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | แปลงค่าบูลีนที่ระบุเป็นตัวแทนในรูปแบบสตริง. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | แปลงค่าจำนวนเต็มที่ระบุเป็นตัวแทนในรูปแบบสตริงในฐานที่ระบุ. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | แปลงค่าจำนวนเต็มที่ระบุเป็นตัวแทนในรูปแบบสตริงในฐานที่ระบุ. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | แปลงค่าจำนวนเต็มที่ระบุเป็นตัวแทนในรูปแบบสต-ringในฐานที่ระบุ. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | แปลงค่าจำนวนเต็มที่ระบุเป็นตัวแทนในรูปแบบสต-ringในฐานที่ระบุ. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บรรจุเป็นกล่องเป็นตัวแทนในรูปแบบสตริง หากประเภทของค่าที่บรรจุเป็นกล่องเป็น [String](../string/) จะใช้รูปแบบสตริงที่ระบุในระหว่างการแปลงค่า. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | แปลงค่าบูลีนที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | แปลงจำนวนเต็มบวก 8 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | แปลงจำนวนเต็มที่มีเครื่องหมาย 8 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | คืนค่าจำนวนเต็มบวกขนาด 16 บิตที่ระบุ. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | แปลงจำนวนเต็มที่มีเครื่องหมาย 16 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | แปลงจำนวนเต็มบวก 32 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | แปลงจำนวนเต็มที่มีเครื่องหมาย 32 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | แปลงจำนวนเต็มบวก 64 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | แปลงจำนวนเต็มที่มีเครื่องหมาย 64 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | แปลงตัวเลข float ที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | แปลงตัวเลข double ที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | แปลงจำนวนเลขฐานสิบที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | แปลงอักขระยูนิโค้ดที่ระบุเป็นจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | การแปลงไม่รองรับ จะทำให้เกิด InvalidCastException เสมอ. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | แปลงสตริง null ที่ระบุเป็นค่าจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | แปลง c-string ที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นสตริงเป็นค่าจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นสตริงเป็นค่าจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนในฐานที่ระบุเป็นสตริงเป็นค่าจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นสตริงเป็นค่าจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ให้มา. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่ระบุซึ่งมีการแสดงผลของจำนวนเป็นสตริงเป็นค่าจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ให้มา. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บรรจุเป็นกล่องเป็นค่าจำนวนเต็มบวกขนาด 16 บิตที่เทียบเท่า. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | แปลงค่าบูลีนที่ระบุเป็นจำนวนเต็มบวกขนาด 32 บิตที่เทียบเท่า. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | แปลงจำนวนเต็มบวก 8 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 32 บิตที่เทียบเท่า. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | แปลงจำนวนเต็มที่มีเครื่องหมาย 8 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 32 บิตที่เทียบเท่า. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | แปลงจำนวนเต็มบวก 16 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 32 บิตที่เทียบเท่า. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | แปลงจำนวนเต็มที่มีเครื่องหมาย 16 บิตที่ระบุเป็นจำนวนเต็มบวกขนาด 32 บิตที่เทียบเท่า. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | คืนค่าจำนวนเต็มบวกขนาด 32 บิตที่ระบุ. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | แปลงจำนวนเต็มแบบ signed ขนาด 32-บิตที่ระบุให้เป็นจำนวนเต็มแบบ unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | แปลงจำนวนเต็มแบบ unsigned ขนาด 64-บิตที่ระบุให้เป็นจำนวนเต็มแบบ unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | แปลงจำนวนเต็มแบบ signed ขนาด 64-บิตที่ระบุให้เป็นจำนวนเต็มแบบ unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | แปลงจำนวนจริงแบบ float ที่ระบุให้เป็นจำนวนเต็มแบบ unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | แปลงจำนวนจริงแบบ double ที่ระบุให้เป็นจำนวนเต็มแบบ unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | แปลงจำนวนทศนิยมที่ระบุให้เป็นจำนวนเต็มแบบ unsigned ขนาด 32-บิตที่เทียบเท่า |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | แปลงอักขระยูนิโค้ดที่ระบุให้เป็นจำนวนเต็มแบบ unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | ไม่รองรับการแปลงค่า จะขับเคลื่อน InvalidCastException เสมอ |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | แปลงสตริง null ที่ระบุให้เป็นค่าจำนวนเต็ม unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | แปลงสตริง C-string ที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าจำนวนเต็ม unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | แปลงสตริงที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าจำนวนเต็ม unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | แปลงสตริงที่มีการแสดงตัวเลขในฐานที่ระบุให้เป็นค่าจำนวนเต็ม unsigned ขนาด 32-บิตที่เทียบเท่า |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าจำนวนเต็ม unsigned ขนาด 32-บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าจำนวนเต็ม unsigned ขนาด 32-บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ระบุ |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บรรจุไว้ให้เป็นค่าจำนวนเต็ม unsigned ขนาด 32-บิตที่เทียบเท่า |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | แปลงค่า boolean ที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | แปลงจำนวนเต็ม unsigned ขนาด 8-บิตที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | แปลงจำนวนเต็ม signed ขนาด 8-บิตที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | แปลงจำนวนเต็ม unsigned ขนาด 16-บิตที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | แปลงจำนวนเต็ม signed ขนาด 16-บิตที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | แปลงจำนวนเต็ม unsigned ขนาด 32-บิตที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | แปลงจำนวนเต็ม signed ขนาด 32-บิตที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | คืนค่าจำนวนเต็ม unsigned ขนาด 64-บิตที่ระบุ |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | แปลงจำนวนเต็ม signed ขนาด 64-บิตที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | แปลงจำนวนจริงแบบ float ที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | แปลงจำนวนจริงแบบ double ที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | แปลงจำนวนทศนิยมที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | แปลงอักขระยูนิโค้ดที่ระบุให้เป็นจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | ไม่รองรับการแปลงค่า จะขับเคลื่อน InvalidCastException เสมอ |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | แปลงสตริง null ที่ระบุให้เป็นค่าจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | แปลงสตริง C-string ที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | แปลงสตริงที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | แปลงสตริงที่มีการแสดงตัวเลขในฐานที่ระบุให้เป็นค่าจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่ระบุ |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงสตริงที่มีการแสดงตัวเลขเป็นสตริงให้เป็นค่าจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและรูปแบบตัวเลขที่ระบุ |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงค่าที่บรรจุไว้ให้เป็นค่าจำนวนเต็ม unsigned ขนาด 64-บิตที่เทียบเท่า |
## ดูเพิ่มเติม

* เนมส페ซ [System](../)
* ไลบรารี [Aspose.Slides](../../)