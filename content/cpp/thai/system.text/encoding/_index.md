---
title: Encoding
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: บริการการเข้ารหัส.
type: docs
weight: 222
url: /th/system.text/encoding/
---
## คลาส Encoding

[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | ทำสำเนาวัตถุการเข้ารหัส. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบการเข้ารหัส. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุด้วยตรรกะของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงแบบสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมสไตล์ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | ดึงการเข้ารหัส ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | ดึงวัตถุการเข้ารหัส Unicode แบบบิ๊กเอนด์มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | ดึงวัตถุการเข้ารหัส UTF-32 แบบบิ๊กเอนด์มาตรฐาน. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | ดึงชื่อการเข้ารหัสที่เข้ากันได้กับเนื้อหาจดหมาย. |
| virtual int [get_CodePage](./get_codepage/)() | ดึง ID codepage ของ [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | ดึง fallback ของตัวถอดรหัส. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | ดึงการเข้ารหัสเริ่มต้น. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | ดึง fallback ของตัวเข้ารหัส. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | ดึงชื่อการเข้ารหัสที่อ่านง่าย. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | ดึงชื่อการเข้ารหัสที่เข้ากันได้กับส่วนหัวของจดหมาย. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในเบราว์เซอร์เพื่อแสดงเนื้อหาได้หรือไม่. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในเบราว์เซอร์เพื่อบันทึกเนื้อหาได้หรือไม่. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในไคลเอนต์เมลเพื่อแสดงเนื้อหาได้หรือไม่. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในไคลเอนต์เมลเพื่อบันทึกเนื้อหาได้หรือไม่. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | ตรวจสอบว่าการเข้ารหัสเป็นแบบอ่านอย่างเดียวหรือไม่. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | ตรวจสอบว่าการเข้ารหัสเป็นแบบไบต์เดียวหรือไม่. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | ดึงการเข้ารหัส Latin1. FOR INTERNAL USE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | ดึงวัตถุการเข้ารหัส Unicode มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | ดึงวัตถุการเข้ารหัส UTF-7 มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | ดึงวัตถุการเข้ารหัส UTF-8 มาตรฐาน. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | ใช้ภายในเท่านั้น, สำหรับไลบรารีคลาส: ไม่ทำเครื่องหมายและไม่ตรวจสอบความถูกต้องของอินพุต. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | ดึงชื่อการเข้ารหัสที่เข้ากันได้กับ IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | ดึง ID codepage ของ [Windows](../../system.windows/). |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | รับจำนวนตัวอักษรที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | รับจำนวนตัวอักษรที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์อักขระ. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | รับจำนวนตัวอักษรที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | รับจำนวนตัวอักษรที่ต้องการเพื่อเข้ารหัสสตริง. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | รับจำนวนตัวอักษรที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์อักขระ. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | รับจำนวนตัวอักษรที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์อักขระ. |
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
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับจำนวนตัวอักษรที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับจำนวนตัวอักษรที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | รับจำนวนตัวอักษรที่ต้องการเพื่อถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | ดึงตัวถอดรหัสที่ส่งต่อคำขอไปยังวัตถุนี้. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | ดึงตัวเข้ารหัสที่ส่งต่อคำขอไปยังวัตถุนี้. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | ดึงการเข้ารหัสตามชื่อ. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | ดึงการเข้ารหัสตาม codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | ดึงการเข้ารหัสตาม codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | ดึงการเข้ารหัสตามชื่อ. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | ดึงรายการการเข้ารหัสที่ทราบ. |
| int [GetHashCode](./gethashcode/)() const override | ทำแฮชการเข้ารหัส. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | รับจำนวนไบต์สูงสุดที่ต้องการเพื่อเข้ารหัสอักขระที่ระบุจำนวน. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | รับจำนวนอักขระสูงสุดที่ต้องการเพื่อถอดรหัสไบต์ที่ระบุจำนวน. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | ส่งกลับลำดับไบต์ที่ระบุการเข้ารหัส (เช่น BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของวัตถุ. ตรงข้ามกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. ตรงข้ามกับโอเปอเรเตอร์ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# การล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ตรงข้ามกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการสำเนา subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการสำเนา subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบแบบอ้างอิงวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงเชื่อมต่อที่แชร์ลงตามค่าที่ระบุ. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | ตั้งค่า fallback ของตัวถอดรหัส. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | ตั้งค่า fallback ของตัวเข้ารหัส. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ตรงข้ามกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคอนสตรัคต์ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# การปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | ค่ารหัสหน้าเริ่มต้น. |

## การกำหนดประเภท

| การกำหนดประเภท | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Text](../)
* ไลบรารี [Aspose.Slides](../../)