---
title: ICUEncoding
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "การทำงานเข้ารหัสแบบอิง ICU. สำหรับการใช้ภายใน. ควรสร้างออบเจ็กต์ของคลาสนี้โดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการละเมิดการอ้างอิง. ให้ห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 300
url: /th/system.text/icuencoding/
---
## ICUEncoding คลาส

การทำงานเข้ารหัสแบบอิง ICU. สำหรับการใช้ภายใน. ควรสร้างออบเจ็กต์ของคลาสนี้โดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการละเมิดการอ้างอิง. ให้วนคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
class ICUEncoding : public System::Text::Encoding
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | สร้างสำเนาวัตถุการเข้ารหัส |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | แปลงไบต์ระหว่างการเข้ารหัสสองแบบ |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบการเข้ารหัส |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | รับการเข้ารหัส ASCII |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | รับวัตถุการเข้ารหัส Unicode แบบ big-endian มาตรฐาน |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | รับวัตถุการเข้ารหัส UTF-32 แบบ big-endian มาตรฐาน |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับส่วนเนื้อหาเมลเอเจนท์ |
| virtual int [get_CodePage](../encoding/get_codepage/)() | รับรหัส codepage ของ [Windows](../../system.windows/) |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | รับ fallback ของ decoder |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | รับการเข้ารหัสเริ่มต้น |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | รับ fallback ของ encoder |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | รับชื่อการเข้ารหัสที่อ่านง่ายสำหรับมนุษย์ |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับส่วนหัวเมลเอเจนท์ |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในเบราว์เซอร์เพื่อแสดงเนื้อหาได้หรือไม่ |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในเบราว์เซอร์เพื่อบันทึกเนื้อหาได้หรือไม่ |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในไคลเอนต์เมลเพื่อแสดงเนื้อหาได้หรือไม่ |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | ตรวจสอบว่าการเข้ารหัสสามารถใช้ในไคลเอนต์เมลเพื่อบันทึกเนื้อหาได้หรือไม่ |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | ตรวจสอบว่าการเข้ารหัสเป็นแบบอ่านอย่างเดียวหรือไม่ |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | ตรวจสอบว่าการเข้ารหัสเป็นแบบ single byte หรือไม่ |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | รับการเข้ารหัส Latin1. สำหรับการใช้ภายใน |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | รับวัตถุการเข้ารหัส Unicode มาตรฐาน |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | รับวัตถุการเข้ารหัส UTF-7 มาตรฐาน |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | รับวัตถุการเข้ารหัส UTF-8 มาตรฐาน |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | ใช้เฉพาะภายใน, เพื่อใช้โดยไลบรารีคลาส: ไม่ทำเครื่องหมายและไม่ตรวจสอบความถูกต้องของอินพุต |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | รับชื่อการเข้ารหัสที่เข้ากันได้กับ IANA |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | รับรหัส codepage ของ [Windows](../../system.windows/) |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | รับจำนวนอักขระที่ต้องการสำหรับเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | รับจำนวนอักขระที่ต้องการสำหรับเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | รับจำนวนอักขระที่ต้องการสำหรับถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับจำนวนอักขระที่ต้องการสำหรับถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับจำนวนอักขระที่ต้องการสำหรับถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | รับจำนวนอักขระที่ต้องการสำหรับถอดรหัสบัฟเฟอร์ไบต์ |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | รับ decoder ที่ส่งต่อคำขอไปยังออบเจ็กต์นี้ |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | รับ encoder ที่ส่งต่อคำขอไปยังออบเจ็กต์นี้ |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | รับการเข้ารหัสตามชื่อ |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | รับการเข้ารหัสตาม codepage |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | รับการเข้ารหัสตาม codepage |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | รับการเข้ารหัสตามชื่อ |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | รับรายการการเข้ารหัสที่รู้จัก |
| int [GetHashCode](../encoding/gethashcode/)() const override | ทำแฮชการเข้ารหัส |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | รับจำนวนไบต์สูงสุดที่ต้องการสำหรับเข้ารหัสจำนวนอักขระที่ระบุ |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | รับจำนวนอักขระสูงสุดที่ต้องการสำหรับถอดรหัสจำนวนไบต์ที่ระบุ |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | ส่งคืนลำดับไบต์ที่บ่งบอกการเข้ารหัส (เช่น BOM) |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | ถอดรหัสบัฟเฟอร์ไบต์เป็นสตริง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
|  [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | Constructor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| **bool** [operator==](./operator_equal_equal/)(const [ICUEncoding](./)\&) const | เปรียบเทียบการเข้ารหัสโดยใช้ codepages |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Sets decoder fallback. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Sets encoder fallback. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | ค่ารหัส codepage เริ่มต้น |

## ดูเพิ่มเติม

* คลาส [Encoding](../encoding/)
* เนมสเปซ [System::Text](../)
* ไลบรารี [Aspose.Slides](../../)