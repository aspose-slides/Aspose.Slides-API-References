---
title: String
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "คลาส String ใช้ทั่วทั้งไลบรารี เป็นตัวแทนของ C# System.String เมื่อแปลโค้ด สำหรับเหตุผลด้านการเพิ่มประสิทธิภาพ ไม่ถือว่าเป็น subclass ของ Object ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิง ไม่ควรใช้คลาส System::SmartPtr เพื่จัดการอ็อบเจกต์ของประเภทนี้"
type: docs
weight: 1275
url: /th/system/string/
---
## คลาส String

[String](./) คลาสที่ใช้ทั่วไลบรารี. เป็นตัวแทนของ C# [System.String](./) เมื่อแปลงโค้ด. ด้วยเหตุผลด้านการเพิ่มประสิทธิภาพ ไม่ถือเป็นคลาสย่อยของ [Object](../object/). ประเภทนี้ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันโดยค่าหรือโดยอ้างอิง. ห้ามใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการอ็อบเจกต์ของประเภทนี้.

```cpp
class String
```

## เมธอด

| Method | Description |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) เป็นชนิดค่าที่ด้าน C++ ซึ่งโดยอัตโนมัติ (โดยไม่มีการสืบทอด) ทำให้รองรับบางอินเทอร์เฟซ. |
| const UChar * [begin](./begin/)() const | ส่งคืน pointer ไปยังจุดเริ่มต้นของบัฟเฟอร์สตริงจริง. ไม่ทำการจัดสรรใหม่ใด ๆ. ไม่ได้รับประกันว่าบัฟเฟอร์จะเป็น null-terminated. |
| [String](./) [Clone](./clone/)() const | สร้างสำเนาของสตริงปัจจุบัน. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | เปรียบเทียบสอง substring ด้วยการน้อย-เท่ากับ-มาก. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | เปรียบเทียบสอง substring ด้วยการน้อย-เท่ากับ-มาก. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | เปรียบเทียบสอง string ด้วยการน้อย-เท่ากับ-มาก. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | เปรียบเทียบสอง string ด้วยการน้อย-เท่ากับ-มาก. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | เปรียบเทียบสอง string ด้วยการน้อย-เท่ากับ-มาก. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | เปรียบเทียบสอง string ด้วยการน้อย-เท่ากับ-มาก. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | เปรียบเทียบสอง string ด้วยการน้อย-เท่ากับ-มาก โดยใช้โหมด ordinal. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | เปรียบเทียบสอง string ด้วยการน้อย-เท่ากับ-มาก โดยใช้โหมด ordinal. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | เปรียบเทียบสอง string ในรูปแบบ 'less-equals-more'. ใช้วัฒนธรรมปัจจุบัน. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | ต่อสตริง. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | ต่อสตริง. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | ต่อสตริง. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | ต่อสตริง. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | ตรวจสอบว่า str เป็นส่วนย่อยของสตริงปัจจุบัน. |
| **bool** [Contains](./contains/)(char16_t) const | ตรวจสอบว่า string มีอักขระที่กำหนด. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | สร้างสำเนาของสตริง. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | คัดลอกอักขระของ string ไปยังองค์ประกอบของอาเรย์ที่มีอยู่แล้ว. ไม่ทำการปรับขนาดใหม่. |
| const UChar * [end](./end/)() const | ส่งคืน pointer ไปยังจุดสิ้นสุดของบัฟเฟอร์สตริงจริง. ไม่ทำการจัดสรรใหม่ใด ๆ. ไม่ได้รับประกันว่าบัฟเฟอร์จะเป็น null-terminated. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | ตรวจสอบว่า string สิ้นสุดด้วย substring ที่กำหนด. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | ตรวจสอบว่า string สิ้นสุดด้วย substring ที่กำหนด. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | ตรวจสอบว่า string สิ้นสุดด้วย substring ที่กำหนด. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) การเปรียบเทียบความเท่าเทียม. รองรับหลายโหมดที่ให้โดยการนับกำหนดของ enumeration StringComparison. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) การเปรียบเทียบความเท่าเทียม. ใช้โหมดการเปรียบเทียบ [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | เปรียบเทียบเท่ากันของสอง string โดยใช้โหมดการเปรียบเทียบ Ordial. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | เปรียบเทียบเท่ากันของสอง string. |
| int [FastToAscii](./fasttoascii/)(char, int) const | พยายามแปลง [String](./) เป็นสตริง ASCII. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | จัดรูปแบบ string ในสไตล์ C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | จัดรูปแบบ string ในสไตล์ C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | จัดรูปแบบ string ในสไตล์ C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | จัดรูปแบบ string ในสไตล์ C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | จัดรูปแบบ string ในสไตล์ C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | สร้าง [String](./) จากสตริง ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | สร้าง [String](./) จากสตริง ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | สร้าง [String](./) จากสตริง ASCII. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | สร้าง [String](./) จาก utf16 string. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | สร้าง [String](./) จาก utf32 string. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | สร้าง [String](./) จาก utf8 string. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | สร้าง [String](./) จาก utf8 string. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | สร้าง [String](./) จาก utf8 string. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | สร้าง [String](./) จาก utf8 string. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | สร้าง [String](./) จาก widestring. |
| int [get_Length](./get_length/)() const | รับความยาวของสตริง. |
| int [GetHashCode](./gethashcode/)() const | สร้าง hash ของสตริงที่มีอยู่. ถูกทำใน ICU, ไม่ตรงกับ hash ใน C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | การค้นหา forward ของ substring. |
| int [IndexOf](./indexof/)(char_t, int) const | การค้นหา forward ของอักขระ. |
| int [IndexOf](./indexof/)(char_t, int, int) const | การค้นหา forward ของอักขระใน substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | การค้นหา forward ของ substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | การค้นหา forward ของ substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | การค้นหา forward ของ substring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | การค้นหา forward ของ substring. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | การค้นหา forward ของอักขระ. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | ต่อจากนั้นจะค้นหาตัวอักษรทั้งหมดของ str ในนี้. หากพบตัวอักษรแรกตำแหน่งของมันจะถูกส่งคืน, หากไม่พบจะค้นหาตัวที่สองและต่อไป. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | ค้นหาตัวอักษรใดก็ได้จากที่ส่งผ่านทั้งหมดในสตริง. เปรียบเทียบอักขระแรกของสตริงกับทุกอักขระใน anyOf, จากนั้นเปรียบเทียบอักขระที่สองและต่อไป. ส่งคืนดัชนีของตัวแรกที่ตรงกับอักขระเป้าหมายใด ๆ. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | ค้นหาตัวอักษรใดก็ได้จากที่ส่งผ่านใน substring. เปรียบเทียบอักขระแรกของสตริงกับทุกอักขระใน anyOf, จากนั้นเปรียบเทียบอักขระที่สองและต่อไป. ส่งคืนดัชนีของตัวแรกที่ตรงกับอักขระเป้าหมายใด ๆ. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | ค้นหาตัวอักษรใดก็ได้จากที่ส่งผ่านใน substring. เปรียบเทียบอักขระแรกของสตริงกับทุกอักขระใน anyOf, จากนั้นเปรียบเทียบอักขระที่สองและต่อไป. ส่งคืนดัชนีของตัวแรกที่ตรงกับอักขระเป้าหมายใด ๆ. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | แทรก substring ที่ตำแหน่งที่ระบุ. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์ string มีชนิดตามที่ [TypeInfo](../typeinfo/) ระบุ. |
| **bool** [IsAsciiString](./isasciistring/)() const | ระบุว่า [String](./) มีสัญลักษณ์ ASCII เท่านั้น. |
| **bool** [IsEmpty](./isempty/)() const | ตรวจสอบว่า string ไม่เป็น null และว่างเปล่าพร้อมกัน. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | ตรวจสอบว่า string ยูนิโค้ดถูกทำให้อยู่ในรูปแบบ normalization ที่ระบุ. |
| **bool** [IsNull](./isnull/)() const | ตรวจสอบว่า string ถือเป็น null. [String](./) เป็น null เฉพาะเมื่อมันถูกสร้างผ่านคอนสตรกเตอร์ [String()](./string/), ถูกย้าย, คัดลอก หรือกำหนดจากสตริง null หรือเมธอด [reset()](./reset/) ถูกเรียก. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | ตรวจสอบว่า string ว่างเปล่าหรือถือเป็น null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | ตรวจสอบว่า string ที่ส่งผ่านเป็น null หรือว่างเปล่า. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | ระบุว่า string ที่ระบุเป็น null, ว่างเปลา, หรือประกอบด้วยอักขระช่องว่างเท่านั้น. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | รวม array โดยใช้ string เป็นตัวคั่น. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | รวม array โดยใช้ string เป็นตัวคั่น. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | รวม array โดยใช้ string เป็นตัวคั่น. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | รวม array โดยใช้ string เป็นตัวคั่น. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | การค้นหา backward ของ substring. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | การค้นหา backward ของ substring. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | การค้นหา backward ของ substring. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | การค้นหา backward ของ substring. |
| int [LastIndexOf](./lastindexof/)(char_t) const | การค้นหา backward ของอักขระ. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | การค้นหา backward ของอักขระ. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | การค้นหา backward ของอักขระ. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | ค้นหาตัวอักษรใดก็ได้จากที่ส่งผ่านในสตริงทั้งหมดโดยย้อนหลัง. เปรียบเทียบอักขระสุดท้ายของสตริงกับทุกอักขระใน anyOf, จากนั้นเปรียบเทียบตัวก่อนหน้าและต่อไป. ส่งคืนดัชนีของการจับคู่แรกที่พบ. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | ค้นหาตัวอักษรใดก็ได้จากที่ส่งผ่านใน substring โดยย้อนหลัง. เปรียบเทียบอักขระสุดท้ายของสตริงกับทุกอักขระใน anyOf, จากนั้นเปรียบเทียบตัวก่อนหน้าและต่อไป. ส่งคืนดัชนีของการจับคู่แรกที่พบ. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | ค้นหาตัวอักษรใดก็ได้จากที่ส่งผ่านใน substring โดยย้อนหลัง. เปรียบเทียบอักขระสุดท้ายของสตริงกับทุกอักขระใน anyOf, จากนั้นเปรียบเทียบตัวก่อนหน้าและต่อไป. ส่งคืนดัชนีของการจับคู่แรกที่พบ. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | ทำให้ string ยูนิโค้ดอยู่ในรูปแบบ normalization ที่ระบุ. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | แปลง string เป็น read only span. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | ตัวดำเนินการเปรียบเทียบที่ไม่เท่ากัน. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | ตรวจสอบว่า string ไม่เป็น null. ใช้ตรรกะเดียวกับการเรียก [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) ตัวดำเนินการต่อสตริง. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) การต่อด้วย string literal หรือ pointer ของ string ตัวอักษร. |
| [String](./) [operator+](./operator_plus/)(char_t) const | เพิ่มอักขระที่ท้ายของสตริง. |
| [String](./) [operator+](./operator_plus/)(int) const | เพิ่มการแสดงค่า integer เป็นสตริงที่ท้ายของสตริง. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | เพิ่มการแสดงค่า unsigned integer เป็นสตริงที่ท้ายของสตริง. |
| [String](./) [operator+](./operator_plus/)(**double**) const | เพิ่มการแสดงค่า floating point เป็นสตริงที่ท้ายของสตริง. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | เพิ่มการแสดงค่า integer เป็นสตริงที่ท้ายของสตริง. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | เพิ่มการแสดงวัตถุแบบอ้างอิงเป็นสตริงที่ท้ายของสตริง. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | เพิ่มการแสดงวัตถุแบบอ้างอิงเป็นสตริงที่ท้ายของสตริง. |
| [String](./) [operator+](./operator_plus/)(T) const | เพิ่มการแสดงค่า boolean เป็นสตริงที่ท้ายของสตริง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | ตัวดำเนินการกำหนดการต่อสตริง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | ตัวดำเนินการกำหนดการต่อสตริง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | ตัวดำเนินการกำหนดการต่อสตริง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | ตัวดำเนินการกำหนดการต่อสตริง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | ตัวดำเนินการกำหนดค่าแบบต่อเนื่อง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | ตัวดำเนินการกำหนดค่าแบบต่อเนื่อง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | ตัวดำเนินการกำหนดค่าแบบต่อเนื่อง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | ตัวดำเนินการกำหนดค่าแบบต่อเนื่อง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | ตัวดำเนินการกำหนดค่าแบบต่อเนื่อง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | ตัวดำเนินการกำหนดค่าแบบต่อเนื่อง. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | ตัวดำเนินการกำหนดค่าแบบต่อเนื่อง. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | เปรียบเทียบลำดับของสตริง. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | ตัวดำเนินการกำหนดค่า. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | ตัวดำเนินการกำหนดค่าแบบย้าย. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | ตัวดำเนินการเปรียบเทียบความเท่าเทียม. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าสตริงเป็นค่า null หรือไม่ ใช้ตรรกะเดียวกับการเรียก [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | เปรียบเทียบลำดับของสตริง. |
| char_t [operator[]](./operator[]/)(int) const | รับอักขระที่ตำแหน่งที่ระบุ. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | เพิ่ม padding ด้านซ้ายของสตริงต้นฉบับ. |
| [String](./) [PadRight](./padright/)(int, char_t) const | เพิ่ม padding ด้านขวาของสตริงต้นฉบับ. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | คืนค่า reverse iterator ไปยังอักขระตัวสุดท้าย (ถ้ามี) ของบัฟเฟอร์สตริงจริง. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | ดึงทุกอย่างยกเว้นส่วนย่อยจากสตริงปัจจุบัน. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | คืนค่า reverse iterator ไปยังตำแหน่งก่อนอักขระแรก (ถ้ามี) ของบัฟเฟอร์สตริงจริง. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | แทนที่อักขระทั้งหมดในสตริง. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | แทนที่การค้นหาทั้งหมดในสตริงนี้. |
| [String](./)\& [reset](./reset/)() | ตั้งค่าสตริงเป็น null. เป็นการทำงานเทียบเท่ากับ 'string_variable_name = null' ใน C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | ตั้งค่าอักขระที่ตำแหน่งที่ระบุ. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | แยกสตริงโดยอักขระ. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | แยกสตริงโดยอักขระ. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | แยกสตริงโดยหนึ่งในสองอักขระ. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | แยกสตริงโดยอักขระที่ระบุ. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | แยกสตริงโดยอักขระที่ระบุ. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | แยกสตริงโดยส่วนย่อย. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | แยกสตริงโดยส่วนย่อย. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | แยกสตริงโดยส่วนย่อย. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | แยกสตริงโดยส่วนย่อย. ปัจจุบัน, รองรับอาร์เรย์ตัวแยกที่มีศูนย์หรือหนึ่งองค์ประกอบเท่านั้น. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | ตรวจสอบว่าสตริงเริ่มต้นด้วยส่วนย่อยที่ระบุ. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | ตรวจสอบว่าสตริงเริ่มต้นด้วยส่วนย่อยที่ระบุ. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | ตรวจสอบว่าสตริงเริ่มต้นด้วยส่วนย่อยที่ระบุ. |
|  [String](./string/)() | คอนสตรัคเตอร์เริ่มต้น. สร้างอ็อบเจกต์สตริงที่ถือว่าเป็น null. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | สร้างสตริงจากสตรี่งลิเทรัล. พิจารณาลิเทรัลเป็นสตริงที่จบด้วย null, คำนวณความยาวของสตริงเป้าหมายตามขนาดของลิเทรัล. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | สร้างสตริงจากตัวชี้สตริงอักขระ. ถือว่าสตริงที่ชี้จบด้วย null, คำนวณความยาวของสตริงเป้าหมายตามอักขระ null. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | สร้างสตริงจากสตรี่งลิเทรัล. พิจารณาลิเทรัลเป็นสตริงที่จบด้วย null ใน UTF8, คำนวณความยาวของสตริงเป้าหมายตามขนาดของลิเทรัล. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | สร้างสตริงจากตัวชี้สตริงอักขระ. ถือว่าสตริงที่ชี้จบด้วย null ใน UTF8, คำนวณความยาวของสตริงเป้าหมายตามอักขระ null. |
|  [String](./string/)(const char16_t *, int) | สร้างสตริงจากตัวชี้สตริงอักขระและความยาวที่ระบุ. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [System.String](./) ด้วยอักขระ Unicode ที่ระบุในสแปนที่อ่านอย่างเดียวที่กำหนด. |
|  [String](./string/)(const char *, int) | สร้างสตริงจากตัวชี้สตริงอักขระและความยาวที่ระบุ. |
|  [String](./string/)(const char16_t *, int, int) | สร้างสตริงจากตัวชี้สตริงอักขระโดยเริ่มจากตำแหน่งที่กำหนดใช้ความยาว. |
| explicit  [String](./string/)(const char16_t, int) | คอนสตรัคเตอร์เติมค่า. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | คอนสตรัคเตอร์ nullptr. ถูกประกาศเป็นเทมเพลตเพื่อแก้ไขลำดับความสำคัญกับคอนสตรัคเตอร์เทมเพลตอื่น. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | สร้างสตริงจากลิเทรัล widestring. พิจารณาลิเทรัลเป็นสตริงที่จบด้วย null, คำนวณความยาวของสตริงเป้าหมายตามขนาดของลิเทรัล. การแปลงจาก **wchar_t** ใช้เวลานานบนบางแพลตฟอร์ม, ดังนั้นไม่อนุญาตการแปลงโดยอัตโนมัติ. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | สร้างสตริงจากตัวชี้สตริง widecharacter. ถือว่าสตริงที่ชี้จบด้วย null, คำนวณความยาวของสตริงเป้าหมายตามอักขระ null. การแปลงจาก **wchar_t** ใช้เวลานานบนบางแพลตฟอร์ม, ดังนั้นไม่อนุญาตการแปลงโดยอัตโนมัติ. |
| explicit  [String](./string/)(const **wchar_t** *, int) | สร้างสตริงจากตัวชี้สตริง widecharacter และความยาวที่ระบุ. การแปลงจาก **wchar_t** ใช้เวลานานบนบางแพลตฟอร์ม, ดังนั้นไม่อนุญาตการแปลงโดยอัตโนมัติ. |
| explicit  [String](./string/)(const **wchar_t**, int) | คอนสตรัคเตอร์เติมค่า. การแปลงจาก **wchar_t** ใช้เวลานานบนบางแพลตฟอร์ม, ดังนั้นไม่อนุญาตการแปลงโดยอัตโนมัติ. |
|  [String](./string/)(const [String](./)\&) | คอนสตรัคเตอร์สำเนา. |
|  [String](./string/)([String](./)\&&) | คอนสตรัคเตอร์ย้าย. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | แปลงอาเรย์อักขระทั้งหมดเป็นสตริง. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | แปลงช่วงย่อยของอาเรย์อักขระเป็นสตริง. หากพารามิเตอร์อยู่นอกขอบเขตของอาเรย์, จะสร้างสตริงว่าง. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | ห่อ UnicodeString ลงใน [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | คอนสตรัคเตอร์ย้าย. |
| explicit  [String](./string/)(const std::wstring\&) | สร้าง [String](./) จาก widestring. |
| explicit  [String](./string/)(const std::u16string\&) | สร้าง [String](./) จากสตริง utf16. |
| explicit  [String](./string/)(const std::string\&) | สร้าง [String](./) จาก std::string ที่แสดงในรูปแบบ UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | สร้าง [String](./) จาก std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | ตัดส่วนย่อยออก. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | ตัดส่วนย่อยออก. |
| std::string [ToAsciiString](./toasciistring/)() const | แปลงสตริงเป็น std::string. ใช้การเข้ารหัส ASCII. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | แปลงสตริงหรือส่วนย่อยเป็นอาร์เรย์ของไบต์. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | แปลงสตริงหรือส่วนย่อยเป็นอาร์เรย์ของอักขระ. |
| [String](./) [ToLower](./tolower/)() const | แปลงอักขระทั้งหมดของสตริงเป็นตัวพิมพ์เล็ก. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | แปลงอักขระทั้งหมดของสตริงเป็นตัวพิมพ์เล็กโดยใช้วัฒนธรรมเฉพาะ. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | แปลงอักขระทั้งหมดของสตริงเป็นตัวพิมพ์เล็กโดยใช้วัฒนธรรมที่ไม่แปรผัน. |
| [String](./) [ToString](./tostring/)() const | ตัวห่อสำหรับจัดการ [String](./) คลาสในบริบทที่ [ToString()](./tostring/) ถูกเรียกบนอ็อบเจกต์ชนิดค่า. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | ตัวห่อสำหรับจัดการ [String](./) คลาสในบริบทที่ [ToString()](./tostring/) ถูกเรียกบนอ็อบเจกต์ชนิดค่า. |
| std::u16string [ToU16Str](./tou16str/)() const | แปลงสตริงเป็น std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | แปลงสตริงเป็น std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | แปลงอักขระทั้งหมดของสตริงเป็นตัวพิมพ์ใหญ่. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | แปลงอักขระทั้งหมดของสตริงเป็นตัวพิมพ์ใหญ่โดยใช้วัฒนธรรมเฉพาะ. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | แปลงอักขระทั้งหมดของสตริงเป็นตัวพิมพ์ใหญ่โดยใช้วัฒนธรรมที่ไม่แปรผัน. |
| std::string [ToUtf8String](./toutf8string/)() const | แปลงสตริงเป็น std::string. ใช้การเข้ารหัส UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | แปลงสตริงเป็น std::wstring. |
| [String](./) [Trim](./trim/)() const | ลบอักขระ whitespace ทั้งหมดจากจุดเริ่มต้นและจุดท้ายของสตริง. |
| [String](./) [Trim](./trim/)(char_t) const | ลบอักขระที่ส่งเข้ามาออกจากจุดเริ่มต้นและจุดท้ายของสตริงทั้งหมด. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | ลบอักขระที่ส่งเข้ามาออกจากจุดเริ่มต้นและจุดท้ายของสตริงทั้งหมด. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | ลบอักขระที่ส่งเข้ามาออกจากจุดเริ่มต้นและจุดท้ายของสตริงทั้งหมด. |
| [String](./) [TrimEnd](./trimend/)() const | ลบอักขระ whitespace ทั้งหมดจากส่วนท้ายของสตริง. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | ลบอักขระที่ส่งเข้ามาออกจากส่วนท้ายของสตริงทั้งหมด. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | ลบอักขระที่ส่งเข้ามาออกจากส่วนท้ายของสตริงทั้งหมด. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | ลบอักขระที่ส่งเข้ามาออกจากส่วนท้ายของสตริงทั้งหมด. |
| [String](./) [TrimStart](./trimstart/)() const | ลบอักขระ whitespace ทั้งหมดจากส่วนต้นของสตริง. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | ลบอักขระที่ส่งเข้ามาออกจากส่วนต้นของสตริงทั้งหมด. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | ลบอักขระที่ส่งเข้ามาออกจากส่วนต้นของสตริงทั้งหมด. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | ลบอักขระที่ส่งเข้ามาออกจากส่วนต้นของสตริงทั้งหมด. |
| const UChar * [u_str](./u_str/)() const | คืนบัฟเฟอร์ที่เป็น null-terminated สไตล์ ICU. อาจทำการจัดสรรใหม่ให้สตริง. |
|  [~String](./~string/)() | เดสทรักเตอร์. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Empty](./empty/) | สตริงว่าง. |
| static [Null](./null/) | สตริง null. |

## ชนิดกำหนดใหม่

| ชนิดกำหนดใหม่ | คำอธิบาย |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | ประเภท reverse iterator. |

## หมายเหตุ



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // สร้างสตริงจากอาร์เรย์ของอักขระและพิมพ์ออก
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // สร้างสตริงจากอาร์เรย์ของไบต์และพิมพ์ออก
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // ตัดส่วนว่างของสตริงด้านล่างและพิมพ์ออก
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // พิมพ์จำนวนคำในสตริง
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
hello
world
"This string contains whitespaces in the beginning and at the end."
จำนวนคำ: 11
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)