---
title: ASCIIEncoding
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "แสดงถึงการเข้ารหัส ASCII. วัตถุของคลาสนี้ควรสร้างเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด. ควรหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 1
url: /th/system.text/asciiencoding/
---
## ASCIIEncoding คลาส

แสดงถึงการเข้ารหัส ASCII. วัตถุของคลาสนี้ควรสร้างเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [ASCIIEncoding](./asciiencoding/)() | คอนสตรัคเตอร์. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | ทำสำเนาวัตถุการเข้ารหัส. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบการเข้ารหัส. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าลอยตัวแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าลอยตัวแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | รับการเข้ารหัส ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | รับวัตถุการเข้ารหัส Unicode แบบ big-endian มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | รับวัตถุการเข้ารหัส UTF-32 แบบ big-endian มาตรฐาน. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับเนื้อหาเมลเอเจนท์. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | รับรหัสหน้าโค้ด [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | รับ fallback ของ decoder. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | รับการเข้ารหัสค่าเริ่มต้น. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | รับ fallback ของ encoder. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | รับชื่อการเข้ารหัสที่อ่านได้โดยมนุษย์. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับส่วนหัวเมลเอเจนท์. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | ตรวจสอบว่าการเข้ารหัสนี้สามารถใช้ในเบราว์เซอร์เพื่อแสดงเนื้อหาได้หรือไม่. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | ตรวจสอบว่าการเข้ารหัสนี้สามารถใช้ในเบราว์เซอร์เพื่อบันทึกเนื้อหาได้หรือไม่. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | ตรวจสอบว่าการเข้ารหัสนี้สามารถใช้ในไคลเอนท์เมลเพื่อแสดงเนื้อหาได้หรือไม่. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | ตรวจสอบว่าการเข้ารหัสนี้สามารถใช้ในไคลเอนท์เมลเพื่อบันทึกเนื้อหาได้หรือไม่. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | ตรวจสอบว่าการเข้ารหัสนี้เป็นแบบอ่านอย่างเดียวหรือไม่. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | ตรวจสอบว่าการเข้ารหัสนี้เป็นแบบไบต์เดียวหรือไม่. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | รับการเข้ารหัส Latin1. ใช้ภายในเท่านั้น. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | รับวัตถุการเข้ารหัส Unicode มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | รับวัตถุการเข้ารหัส UTF-7 มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | รับวัตถุการเข้ารหัส UTF-8 มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | ใช้ภายในเท่านั้น, สำหรับไลบรารีคลาส: ไม่ระบุและไม่มีการตรวจสอบอินพุต. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับ IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | รับรหัสหน้าโค้ด [Windows](../../system.windows/). |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | รับจำนวนอักขระที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | รับ decoder ที่ส่งต่อคำขอไปยังวัตถุนี้. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | รับ encoder ที่ส่งต่อคำขอไปยังวัตถุนี้. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | รับการเข้ารหัสตามชื่อ. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | รับการเข้ารหัสตามหน้าโค้ด. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | รับการเข้ารหัสตามหน้าโค้ด. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | รับการเข้ารหัสตามชื่อ. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | รับรายการของการเข้ารหัสที่รู้จัก. |
| int [GetHashCode](../encoding/gethashcode/)() const override | สร้างแฮชของการเข้ารหัส. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | รับจำนวนไบต์สูงสุดที่สามารถเก็บสตริงที่มีจำนวนอักขระที่ทราบได้. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | รับจำนวนอักขระสูงสุดที่ต้องการเพื่อถอดรหัสไบต์ที่ระบุ. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | ส่งคืนลำดับของไบต์ที่ระบุการเข้ารหัส (เช่น BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของวัตถุ. เป็นแนวคิดคล้ายการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C#. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | คอนสตรัคเตอร์. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุแสดงถึงอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวทำงาน 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็น lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นทุกโครงสร้างข้อมูลภายใน. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกในคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกในคลาสย่อย. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | เปรียบเทียบการเข้ารหัสโดยใช้หน้าโค้ด. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ชนิดค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | ตั้งค่า fallback ของ decoder. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | ตั้งค่า fallback ของ encoder. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตการสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. เปิดใช้งานการแปลงวัตถุกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็น C# lock() ปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยทุกโครงสร้างข้อมูลภายใน. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | ค่าหน้าโค้ดเริ่มต้น. |

## ดูเพิ่มเติม

* คลาส [ICUEncoding](../icuencoding/)
* เนมสเปซ [System::Text](../)
* ไลบรารี [Aspose.Slides](../../)