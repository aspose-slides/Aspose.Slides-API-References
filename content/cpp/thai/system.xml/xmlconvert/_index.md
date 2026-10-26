---
title: XmlConvert
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เข้ารหัสและถอดรหัสชื่อ XML, และมีเมธอดสำหรับการแปลงระหว่างประเภทที่ทำงานและประเภทของภาษาอธิบายสคีมา XML (XSD). เมื่อแปลงประเภทข้อมูล, ค่าที่คืนจะไม่ขึ้นกับโลคัล.
type: docs
weight: 157
url: /th/system.xml/xmlconvert/
---
## XmlConvert คลาส

ทำการเข้ารหัสและถอดรหัสชื่อ XML, และให้เมธอดสำหรับการแปลงระหว่างประเภทที่ทำงานและประเภทของ XML [Schema](../../system.xml.schema/) ภาษาอธิบาย (XSD) types. เมื่อแปลงประเภทข้อมูล, ค่าที่คืนจะไม่ขึ้นกับโลคัล.

```cpp
class XmlConvert : public System::Object
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | ถอดรหัสชื่อ. เมธอดนี้ทำการย้อนกลับของเมธอด XmlConvert::EncodeName(String) และ XmlConvert::EncodeLocalName(String). |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | แปลงชื่อให้เป็นชื่อ XML local ที่ถูกต้อง. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | แปลงชื่อให้เป็นชื่อ XML ที่ถูกต้อง. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | ตรวจสอบว่าชื่อเป็นไปตามข้อกำหนดของ XML. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมสไตล์ C# ที่ NaN สองค่าเทียบเท่ากัน แม้ว่า IEC 60559:1989 จะระบุว่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมสไตล์ C# ที่ NaN สองค่าเทียบเท่ากัน แม้ว่า IEC 60559:1989 จะระบุว่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อการภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถทำแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์. เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เทียบเคียงกับโอเปอเรเตอร์ 'is' ของ C#. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | ตรวจสอบว่าตัวอักษรที่ส่งเข้ามาเป็นประเภทอักขระที่ไม่มีเครื่องหมาย ':' ที่ถูกต้องหรือไม่. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | คืนค่าตัวอักษรที่ส่งเข้ามาหากอักขระในอาร์กิวเมนต์เป็นอักขระ public id ที่ถูกต้อง, มิฉะนั้นจะคืน **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | ตรวจสอบว่าตัวอักษรที่ส่งเข้ามาเป็นประเภทอักขระเริ่มต้นชื่อที่ถูกต้องหรือไม่. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | ตรวจสอบว่าตัวอักษรที่ส่งเข้ามาเป็นอักขระ whitespace ของ XML ที่ถูกต้องหรือไม่. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | ตรวจสอบว่าตัวอักษรที่ส่งเข้ามาเป็นอักขระ XML ที่ถูกต้องหรือไม่. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | ตรวจสอบว่าคู่ซอร์เกเตตที่ส่งเข้ามาเป็นอักขระ XML ที่ถูกต้องหรือไม่. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถคล cloning ประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกเพื่อสร้างคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกเพื่อสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงแบบแชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่เป็น shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงแบบแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Boolean](../../system/boolean/). |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Byte](../../system/byte/). |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Char](../../system/char/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | แปลง [String](../../system/string/) ให้เป็น [DateTime](../../system/datetime/) โดยใช้ XmlDateTimeSerializationMode ที่ระบุ. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ที่ให้มาให้เป็นเทียบเท่า [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ที่ให้มาให้เป็นเทียบเท่า [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | แปลง [String](../../system/string/) ที่ให้มาให้เป็นเทียบเท่า [DateTimeOffset](../../system/datetimeoffset/). |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Decimal](../../system/decimal/). |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Double](../../system/double/). |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Guid](../../system/guid/). |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Int16](../../system/int16/). |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Int32](../../system/int32/). |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Int64](../../system/int64/). |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [SByte](../../system/sbyte/). |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [Single](../../system/single/). |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | แปลง [Boolean](../../system/boolean/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | แปลง [Char](../../system/char/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | แปลง [Decimal](../../system/decimal/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | แปลง [SByte](../../system/sbyte/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | แปลง [Int16](../../system/int16/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | แปลง [Int32](../../system/int32/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | แปลง [Int64](../../system/int64/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | แปลง [Byte](../../system/byte/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | แปลง [UInt16](../../system/uint16/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | แปลง [UInt32](../../system/uint32/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | แปลง [UInt64](../../system/uint64/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | แปลง [Single](../../system/single/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | แปลง [Double](../../system/double/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | แปลง [TimeSpan](../../system/timespan/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | แปลง [DateTime](../../system/datetime/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | แปลง [DateTime](../../system/datetime/) ให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | แปลง [DateTime](../../system/datetime/) ให้เป็น [String](../../system/string/) โดยใช้ XmlDateTimeSerializationMode ที่ระบุ. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | แปลง [DateTimeOffset](../../system/datetimeoffset/) ที่ให้มาให้เป็น [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | แปลง [DateTimeOffset](../../system/datetimeoffset/) ที่ให้มาให้เป็น [String](../../system/string/) ในรูปแบบที่ระบุ. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | แปลง [Guid](../../system/guid/) ให้เป็น [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [TimeSpan](../../system/timespan/). |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [UInt16](../../system/uint16/). |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [UInt32](../../system/uint32/). |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | แปลง [String](../../system/string/) ให้เป็นเทียบเท่า [UInt64](../../system/uint64/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการดำเนินการ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | ตรวจสอบว่าชื่อเป็นชื่อที่ถูกต้องตามข้อแนะนำของ W3C Extended Markup Language. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | ตรวจสอบว่าชื่อเป็น **NCName** ที่ถูกต้องตามข้อแนะนำของ W3C Extended Markup Language. **NCName** คือชื่อที่ไม่สามารถมีเครื่องหมาย ':' ได้. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | ตรวจสอบว่าสตริงเป็น NMTOKEN ที่ถูกต้องตามข้อแนะนำ W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | คืนค่าสตริงที่ส่งเข้ามาหากอักขระทั้งหมดในอาร์กิวเมนต์เป็นอักขระ public id ที่ถูกต้อง. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | ตรวจสอบว่าสตริงเป็นโทเคนที่ถูกต้องตามข้อแนะนำ W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | คืนค่าสตริงที่ส่งเข้ามาหากอักขระทั้งหมดในอาร์กิวเมนต์เป็นอักขระ whitespace ที่ถูกต้อง. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | คืนสตริงที่ส่งเข้ามาหากอักขระและคู่ surrogate ทั้งหมดในอาร์กิวเมนต์เป็นอักขระ XML ที่ถูกต้อง, มิฉะนั้นจะทำการโยน XmlException พร้อมข้อมูลของอักขระที่ไม่ถูกต้องตัวแรก. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## นิยามประเภท

| นิยามประเภท | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)