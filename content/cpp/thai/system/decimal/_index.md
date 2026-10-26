---
title: Decimal
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แทนค่าตัวเลขทศนิยม ชนิดนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง อย่าใช้คลาส System::SmartPtr ในการจัดการออบเจ็กต์ของชนิดนี้."
type: docs
weight: 261
url: /th/system/decimal/
---
## คลาส Decimal

Represents a decimal number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Decimal
```

## Methods

| Method | คำอธิบาย |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | เพิ่มสองค่า [Decimal](./) ที่ระบุ |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | คืนค่าจำนวนเต็มที่เล็กที่สุดที่มากกว่าหรือเท่ากับค่าที่ระบุ |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ [Decimal](./) ตัวแรกน้อยกว่า เท่ากับ หรือ มากกว่าค่าที่แสดงโดยอ็อบเจ็กต์ [Decimal](./) ตัวที่สอง |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันน้อยกว่า เท่ากับ หรือ มากกว่าค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุ |
| [Decimal](./decimal/)() | สร้างอินสแตนซ์ที่แสดงค่า 0 |
| [Decimal](./decimal/)(std::int8_t) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| [Decimal](./decimal/)(std::int16_t) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| [Decimal](./decimal/)(std::int32_t) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| [Decimal](./decimal/)(std::int64_t) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| [Decimal](./decimal/)(std::uint8_t) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| [Decimal](./decimal/)(std::uint16_t) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| [Decimal](./decimal/)(std::uint32_t) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| [Decimal](./decimal/)(std::uint64_t) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| [Decimal](./decimal/)(**float**) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| [Decimal](./decimal/)(**double**) | สร้างอินสแตนซ์ที่แสดงค่าที่ระบุ |
| explicit  [Decimal](./decimal/)(const std::string\&) | สร้างอินสแตนซ์ที่แสดงค่าที่มีการแสดงผลเป็นสตริงโดยระบุเป็นอินสแตนซ์ของคลาส std::string |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | สร้างอ็อบเจ็กต์ [Decimal](./) จากส่วนประกอบที่ระบุ |
| [Decimal](./decimal/)(const [Decimal](./)\&) | สร้างอินสแตนซ์ของคลาส [Decimal](./) ที่แสดงเลขเดียวกับอ็อบเจ็กต์ [Decimal](./) ที่ระบุ |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | สร้างอินสแตนซ์ของคลาส [Decimal](./) จากอาร์เรย์จำนวนเต็มที่บรรจุการแทนค่าทวิภาค |
| [Decimal](./decimal/)(std::nullptr_t) | จะโยน ArgumentNullException เสมอ |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | สร้างอินสแตนซ์ของคลาส [Decimal](./) ที่แสดงค่าที่ระบุ |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | หารสองค่า [Decimal](./) ที่ระบุ |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุเท่ากันหรือไม่ |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุเท่ากันหรือไม่ |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุเท่ากันหรือไม่ |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | คืนค่าจำนวนเต็มที่ใหญ่ที่สุดที่น้อยกว่าหรือเท่ากับค่าที่ระบุ |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) ค่าครองชีพ OLE ที่ระบุเป็นค่า [Decimal](./) ที่เทียบเท่า. ยังไม่ได้ทำ |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | แปลงอ็อบเจ็กต์ [Decimal](./) ที่ระบุเป็นการแทนค่าทวิภาคของค่าที่มันแสดง |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) ค่าที่ระบุ [Decimal](./) เป็นอาร์เรย์ของไบต์ |
| int [GetHashCode](./gethashcode/)() const | คืนค่าแฮชโค้ดสำหรับอ็อบเจ็กต์ปัจจุบัน |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | รับรหัสประเภทอ็อบเจ็กต์ |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | คูณสองค่า [Decimal](./) ที่ระบุ |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./) ที่แสดงค่าที่ได้จากการทำลบค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุ |
| explicit  [operator bool](./operator_bool/)() const | แปลงค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นค่าบูลีน |
| explicit  [operator double](./operator_double/)() const | แปลงค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นค่าจุดลอยแบบความแม่นยำสองเท่า |
| explicit  [operator float](./operator_float/)() const | แปลงค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นค่าจุดลอยแบบความแม่นยำเดี่ยว |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุไม่เท่ากัน |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันแตกต่างจาก 0 |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./) ที่แสดงค่าผลจากการดำเนินการโมดูลัสกับค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | กำหนดค่าใหม่ให้กับอ็อบเจ็กต์ปัจจุบันที่เป็นผลของการดำเนินการโมดูลัสกับค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./) ที่แสดงค่าผลจากการคูณค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | กำหนดค่าใหม่ให้กับอ็อบเจ็กต์ปัจจุบันที่เป็นผลของการคูณค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./) ที่แสดงค่าผลบวกของค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | เพิ่มค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | กำหนดค่าใหม่ให้กับอ็อบเจ็กต์ปัจจุบันที่เป็นผลบวกของค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./) ที่แสดงค่าผลจากการลบค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุออกจากค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [Decimal](./) [operator-](./operator_minus/)() const | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./) ที่แสดงค่าที่ได้จากการทำลบค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | ลดค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | กำหนดค่าใหม่ให้กับอ็อบเจ็กต์ปัจจุบันที่เป็นผลจากการลบค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุออกจากค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./) ที่แสดงค่าผลจากการหารค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุ |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | กำหนดค่าใหม่ให้กับอ็อบเจ็กต์ปัจจุบันที่เป็นผลจากการหารค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันด้วยค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุ |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันน้อยกว่าค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุ |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันน้อยกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุ |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | กำหนดค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุให้กับอ็อบเจ็กต์ปัจจุบัน |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุเท่ากันหรือไม่ |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็น 0 หรือไม่ |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันมากกว่าค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุ |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | ตรวจสอบว่าค่าที่แสดงโดยอ็อบเจ็กต์ปัจจุบันมากกว่าหรือเท่ากับค่าที่แสดงโดยอ็อบเจ็กต์ที่ระบุ |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | แปลงการแสดงสตริงของจำนวนทศนิยมเป็นอินสแตนซ์ที่เทียบเท่าของคลาส [Decimal](./) |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | แปลงการแสดงสตริงของจำนวนทศนิยมเป็นอินสแตนซ์ที่เทียบเท่าของคลาส [Decimal](./) โดยใช้รูปแบบที่ระบุ |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงการแสดงสตริงของจำนวนทศนิยมเป็นอินสแตนซ์ที่เทียบเท่ของคลาส [Decimal](./) โดยใช้ผู้ให้รูปแบบที่ระบุ |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | แปลงการแสดงสตริงของจำนวนทศนิยมเป็นอินสแตนซ์ที่เทียบเท่าของคลาส [Decimal](./) โดยใช้รูปแบบและผู้ให้รูปแบบที่ระบุ |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | คำนวณส่วนเหลือหลังจากหารสองค่า [Decimal](./) |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | ปัดค่าที่ระบุให้เป็นจำนวนเต็มที่ใกล้ที่สุด พารามิเตอร์หนึ่งระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุห่างเท่า ๆ กันจากสองจำนวนที่ใกล้ที่สุด |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดที่มีจำนวนตำแหน่งทศนิยมตามที่ระบุ พารามิเตอร์หนึ่งระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุห่างเท่า ๆ กันจากสองค่าที่ใกล้ที่สุด |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | ลบค่าที่ระบุ [Decimal](./) หนึ่งค่าออกจากอีกค่าหนึ่ง |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | แปลงค่า [Decimal](./) ให้เป็นจำนวนเต็มบิต 8 ที่ไม่มีเครื่องหมาย |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | แปลงค่าที่ [Decimal](./) ให้เป็นเลขทศนิยมแบบความแม่นยำสองเท่า |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | แปลงค่าที่ [Decimal](./) ให้เป็นจำนวนเต็ม 16 บิตแบบมีเครื่องหมาย |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | แปลงค่าที่ [Decimal](./) ให้เป็นจำนวนเต็ม 32 บิตแบบมีเครื่องหมาย |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | แปลงค่าที่ [Decimal](./) ให้เป็นจำนวนเต็ม 64 บิตแบบมีเครื่องหมาย |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) ค่าที่ระบุ [Decimal](./) ให้เป็นค่า OLE currency ที่เทียบเท่า. ยังไม่ได้ทำ |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | แปลงค่าที่ [Decimal](./) ให้เป็นจำนวนเต็ม 8 บิตแบบมีเครื่องหมาย |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | แปลงค่าที่ [Decimal](./) ให้เป็นเลขทศนิยมแบบความแม่นยำเดี่ยว |
| std::string [ToStdString](./tostdstring/)() const | คืนอินสแตนซ์ของ std::string ที่บรรจุการแสดงสตริงของค่าที่อ็อบเจ็กต์แสดง |
| [String](../string/) [ToString](./tostring/)() const | คืนการแสดงสตริงของค่าที่อ็อบเจ็กต์แสดง |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | แปลงอ็อบเจ็กต์ปัจจุบันเป็นสตริงโดยใช้ข้อมูลรูปแบบเฉพาะวัฒนธรรม |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | แปลงอ็อบเจ็กต์ปัจจุบันเป็นการแสดงสตริงของมันโดยใช้รูปแบบสตริงที่ระบุและข้อมูลรูปแบบเฉพาะวัฒนธรรมที่ให้โดยอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/) ที่ระบุ |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | คืนการแสดงสตริงของค่าที่อ็อบเจ็กต์แสดง สำหรับการใช้งานภายใน |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | แปลงค่า [Decimal](./) ให้เป็นจำนวนเต็มบิต 16 ที่ไม่มีเครื่องหมาย |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | แปลงค่า [Decimal](./) ให้เป็นจำนวนเต็มบิต 32 ที่ไม่มีเครื่องหมาย |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | แปลงค่า [Decimal](./) ให้เป็นจำนวนเต็มบิต 64 ที่ไม่มีเครื่องหมาย |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | คืนอ็อบเจ็กต์ [Decimal](./) ที่แสดงค่าที่มีส่วนจำนวนเต็มเท่ากับค่าที่อ็อบเจ็กต์ [Decimal](./) ที่ระบุแสดง โดยตัดทอนส่วนทศนิยมทั้งหมด |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | แปลงสตริงที่ระบุซึ่งบรรจุการแสดงสตริงของตัวเลขเป็นค่า [Decimal](./) ที่เทียบเท่า |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | แปลงสตริงที่ระบุซึ่งบรรจุการแสดงสตริงของตัวเลขเป็นค่า [Decimal](./) ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบและสไตล์ตัวเลขที่ระบุ |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | คืนการอ้างอิงถึงอ็อบเจ็กต์ [TypeInfo](../typeinfo/) ที่แสดงข้อมูลประเภทของคลาส [Decimal](./) |
|  [~Decimal](./~decimal/)() | ตัวทำลาย |
## Fields

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [MaxValue](./maxvalue/) | แสดงจำนวนที่ใหญ่ที่สุดที่สามารถแสดงได้โดยคลาส [Decimal](./) |
| static [MinusOne](./minusone/) | แสดงจำนวน -1 |
| static [MinValue](./minvalue/) | แสดงจำนวนที่เล็กที่สุดที่สามารถแสดงได้โดยคลาส [Decimal](./) |
| static [One](./one/) | แสดงจำนวน 1 |
| static [Zero](./zero/) | แสดงจำนวน 0 |
## Typedefs

| Typedef | คำอธิบาย |
| --- | --- |
| [number_type](./number_type/) | ชื่อแทนสำหรับ Detail::decimal_number_type |
## Remarks



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)