---
title: UTF32Encoding
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "การเข้ารหัส UTF-32. อ็อบเจ็กต์ของคลาสนี้ควรสร้างได้เฉพาะโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 352
url: /th/system.text/utf32encoding/
---
## UTF32Encoding คลาส

การเข้ารหัส UTF-32. อ็อบเจ็กต์ของคลาสนี้ควรสร้างได้เฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าให้สร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาทำงานและ/หรือการอ้างอิงที่ผิดพลาด. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class UTF32Encoding : public System::Text::ICUEncoding
```

## เมธอด

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | คัดลอกอ็อบเจ็กต์การเข้ารหัส |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตามสไตล์ C# ซึ่ง NaN สองค่า ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตามสไตล์ C# ซึ่ง NaN สองค่า ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | รับการเข้ารหัส ASCII |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | รับอ็อบเจ็กต์การเข้ารหัส Unicode แบบ big-endian มาตรฐาน |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | รับอ็อบเจ็กต์การเข้ารหัส UTF-32 แบบ big-endian มาตรฐาน |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับเนื้อหาเมลเอเจนต์ |
| virtual int [get_CodePage](../encoding/get_codepage/)() | รับรหัส codepage ของ [Windows](../../system.windows/) |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | รับ decoder fallback |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | รับการเข้ารหัสค่าเริ่มต้น |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | รับ encoder fallback |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | รับชื่อการเข้ารหัสที่อ่านได้ง่าย |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับหัวเมลเอเจนต์ |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในเบราว์เซอร์เพื่อแสดงเนื้อหาได้หรือไม่ |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในเบราว์เซอร์เพื่อบันทึกเนื้อหาได้หรือไม่ |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในไคลเอนต์อีเมลเพื่อแสดงเนื้อหาได้หรือไม่ |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในไคลเอนต์อีเมลเพื่อบันทึกเนื้อหาได้หรือไม่ |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | ตรวจสอบว่าการเข้ารหัสเป็นแบบอ่านอย่างเดียวหรือไม่ |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | ตรวจสอบว่าการเข้ารหัสเป็นแบบไบต์เดียวหรือไม่ |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | รับการเข้ารหัส Latin1. ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | รับอ็อบเจ็กต์การเข้ารหัส Unicode มาตรฐาน |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | รับอ็อบเจ็กต์การเข้ารหัส UTF-7 มาตรฐาน |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | รับอ็อบเจ็กต์การเข้ารหัส UTF-8 มาตรฐาน |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | ใช้ภายในเท่านั้น, ใช้โดยไลบรารีคลาส: ไม่ทำเครื่องหมายและไม่ตรวจสอบความถูกต้องของอินพุต |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับ IANA |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | รับรหัส codepage ของ [Windows](../../system.windows/) |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | รับจำนวนอักขระที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์ |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์ |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | รับตัวถอดรหัสที่ส่งต่อคำขอไปยังอ็อบเจ็กต์นี้ |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | รับตัวเข้ารหัสที่ส่งต่อคำขอไปยังอ็อบเจ็กต์นี้ |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | รับการเข้ารหัสตามชื่อ |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | รับการเข้ารหัสตาม codepage |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | รับการเข้ารหัสตาม codepage |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | รับการเข้ารหัสตามชื่อ |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | รับรายการของการเข้ารหัสที่รู้จัก |
| int [GetHashCode](./gethashcode/)() const override | รับรหัสแฮชของการเข้ารหัส |
| int [GetMaxByteCount](../icuencoding/getmaxbytecount/)(int) override | รับจำนวนไบต์สูงสุดที่ต้องการเพื่อเข้ารหัสจำนวนอักขระที่ระบุ |
| int [GetMaxCharCount](../icuencoding/getmaxcharcount/)(int) override | รับจำนวนอักขระสูงสุดที่ต้องการเพื่อถอดรหัสจำนวนไบต์ที่ระบุ |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | รับ preamble ของ codepage |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. ตรงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | คอนสตรัคเตอร์. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. ตรงกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำให้การล็อกตามคำสั่ง lock() ของ C# ทำงาน. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ตรงกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการคัดลอกประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. กำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่กำหนดค่าอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่กำหนดค่าอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| **bool** [operator==](./operator_equal_equal/)(const [UTF32Encoding](./)\&) const | เปรียบเทียบพารามิเตอร์ของการเข้ารหัส |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | เปรียบเทียบการเข้ารหัสโดยใช้ codepage |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่า กับ nullptr ตามการอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | กำหนด decoder fallback |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | กำหนด encoder fallback |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะแชร์). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ตรงกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำให้โครงสร้าง typeof([System.Object](../../system/object/)) ของ C# ทำงาน |
| void [Unlock](../../system/object/unlock/)() | ทำให้การปลดล็อกตามคำสั่ง lock() ของ C# ทำงาน. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
|  [UTF32Encoding](./utf32encoding/)() | คอนสตรัคเตอร์. |
|  [UTF32Encoding](./utf32encoding/)(**bool**, **bool**) | คอนสตรัคเตอร์. |
|  [UTF32Encoding](./utf32encoding/)(**bool**, **bool**, **bool**) | คอนสตรัคเตอร์. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| Field | Description |
| --- | --- |
| static constexpr [BIG_UTF32_CODE_PAGE](./big_utf32_code_page/) | หมายเลขมหัศจรรย์ที่ใช้โดย [Windows](../../system.windows/) สำหรับรหัส codepage UTF-32 แบบ big endian |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | ค่ารหัส codepage เริ่มต้น |
| static constexpr [UTF32_CODE_PAGE](./utf32_code_page/) | หมายเลขมหัศจรรย์ที่ใช้โดย [Windows](../../system.windows/) สำหรับรหัส codepage UTF-32 แบบ little endian |

## ดูเพิ่มเติม

* คลาส [ICUEncoding](../icuencoding/)
* เนมสเปซ [System::Text](../)
* ไลบรารี [Aspose.Slides](../../)