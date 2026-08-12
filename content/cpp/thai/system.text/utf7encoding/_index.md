---
title: UTF7Encoding
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "การเข้ารหัส UTF-7. วัตถุของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr แล้วใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 365
url: /th/system.text/utf7encoding/
---
## UTF7Encoding คลาส

การเข้ารหัส UTF-7. วัตถุของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) แล้วใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## เมธอด

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ทำสำเนาวัตถุการเข้ารหัส. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบกับวัตถุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | รับการเข้ารหัส ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | รับวัตถุการเข้ารหัส Unicode แบบบิ๊กเอนด์แอนด์มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | รับวัตถุการเข้ารหัส UTF-32 แบบบิ๊กเอนด์แอนด์มาตรฐาน. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับเนื้อหาเมลเอเจนท์. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | รับรหัส codepage ของ [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | รับค่า fallback ของตัวถอดรหัส. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | รับการเข้ารหัสเริ่มต้น. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | รับค่า fallback ของตัวเข้ารหัส. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | รับชื่อการเข้ารหัสที่อ่านง่าย. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับส่วนหัวเมลเอเจนท์. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | ตรวจสอบว่าการเข้ารหัสนี้สามารถใช้ในเบราว์เซอร์เพื่อแสดงเนื้อหาได้หรือไม่. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | ตรวจสอบว่าการเข้ารหัสนี้สามารถใช้ในเบราว์เซอร์เพื่อบันทึกเนื้อหาได้หรือไม่. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | ตรวจสอบว่าการเข้ารหัสนี้สามารถใช้ในไคลเอนต์เมลเพื่อแสดงเนื้อหาได้หรือไม่. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | ตรวจสอบว่าการเข้ารหัสนี้สามารถใช้ในไคลเอนต์เมลเพื่อบันทึกเนื้อหาได้หรือไม่. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | ตรวจสอบว่าการเข้ารหัสนี้เป็นอ่านอย่างเดียวหรือไม่. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | ตรวจสอบว่าการเข้ารหัสนี้เป็นแบบไบต์เดียวหรือไม่. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | รับการเข้ารหัส Latin1. เพื่อการใช้ภายในเท่านั้น. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | รับวัตถุการเข้ารหัส Unicode มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | รับวัตถุการเข้ารหัส UTF-7 มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | รับวัตถุการเข้ารหัส UTF-8 มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | ใช้ภายในเท่านั้น เพื่อใช้โดยไลบรารีคลาส: ไม่ทำเครื่องหมายและไม่ตรวจสอบความถูกต้องของอินพุต. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับ IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | รับรหัส codepage ของ [Windows](../../system.windows/). |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | รับจำนวนอักขระที่จำเป็นสำหรับเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | รับจำนวนอักขระที่จำเป็นสำหรับเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | รับจำนวนอักขระที่จำเป็นสำหรับเข้ารหัสบัฟเฟอร์อักขระ. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | รับจำนวนอักขระที่จำเป็นสำหรับเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | รับจำนวนอักขระที่จำเป็นสำหรับเข้ารหัสสตริง. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | รับจำนวนอักขระที่จำเป็นสำหรับเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | รับจำนวนอักขระที่จำเป็นสำหรับเข้ารหัสบัฟเฟอร์อักขระ. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | รับจำนวนอักขระที่จำเป็นสำหรับถอดรหัสบัฟเฟอร์ไบต์. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | รับจำนวนอักขระที่จำเป็นสำหรับถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับจำนวนอักขระที่จำเป็นสำหรับถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับจำนวนอักขระที่จำเป็นสำหรับถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | รับจำนวนอักขระที่จำเป็นสำหรับถอดรหัสบัฟเฟอร์ไบต์. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | รับตัวถอดรหัสที่ส่งต่อคำขอไปยังวัตถุนี้. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | รับตัวเข้ารหัสที่ส่งต่อคำขอไปยังวัตถุนี้. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | รับการเข้ารหัสตามชื่อ. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | รับการเข้ารหัสตาม codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | รับการเข้ารหัสตาม codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | รับการเข้ารหัสตามชื่อ. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | รับรายการการเข้ารหัสที่ทราบ. |
| int [GetHashCode](./gethashcode/)() const override | รับค่าแฮชของการเข้ารหัส. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | รับจำนวนไบต์สูงสุดที่จำเป็นสำหรับเข้ารหัสจำนวนอักขระที่กำหนด. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | รับจำนวนอักขระสูงสุดที่จำเป็นสำหรับถอดรหัสจำนวนไบต์ที่กำหนด. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | ส่งคืนลำดับไบต์ที่บ่งบอกการเข้ารหัส (เช่น BOM). |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. ตรงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุแสดงถึงอินสแตนซ์ของประเภทที่อธิบายโดย targetType. ตรงกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำคลอนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างคัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | เปรียบเทียบพารามิเตอร์ของการเข้ารหัส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมลงตามค่าที่ระบุ. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | ตั้งค่า fallback ของตัวถอดรหัส. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | ตั้งค่า fallback ของตัวเข้ารหัส. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
|  [UTF7Encoding](./utf7encoding/)() | ตัวสร้าง. |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | ตัวสร้าง. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | ค่าค่าเริ่มต้นของ codepage. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | เลขเมจิกที่ [Windows](../../system.windows/) ใช้สำหรับรหัส codepage UTF-7. |

## ดูเพิ่มเติม

* คลาส [Encoding](../encoding/)
* เนมสเปซ [System::Text](../)
* ไลบรารี [Aspose.Slides](../../)