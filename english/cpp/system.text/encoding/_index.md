---
title: Encoding
second_title: Aspose.Slides for C++ API Reference
description: Encoding services.
type: docs
weight: 222
url: /cpp/system.text/encoding/
---
## Encoding class


[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Clones encoding object. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Converts bytes between two encodings. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Converts bytes between two encodings. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compares encodings. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Gets ASCII encoding. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Gets the standard big-endian Unicode encoding object. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Gets the standard big-endian UTF-32 encoding object. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Gets mail agent body compatible encoding name. |
| virtual int [get_CodePage](./get_codepage/)() | Gets [Windows](../../system.windows/) codepage ID. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Gets decoder fallback. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Gets default encoding. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Gets encoder fallback. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Gets human-readable encoding name. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Gets mail agent header compatible encoding name. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Checks whether encoding can be used in browser to display content. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Checks whether encoding can be used in browser to save content. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Checks whether encoding can be used in mail client to display content. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Checks whether encoding can be used in mail client to save content. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Checks whether encoding is read-only. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Checks whether encoding is single byte. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Gets Latin1 encoding. FOR INTERNAL USE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Gets the standard Unicode encoding object. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Gets the standard UTF-7 encoding object. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Gets the standard UTF-8 encoding object. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Only internal, to be used by the class libraries: Unmarked and non-input-validating. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Gets IANA-compatible encoding name. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Gets [Windows](../../system.windows/) codepage ID. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Get the number of characters needed to encode a character buffer. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Get the number of characters needed to encode a character buffer. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Get the number of characters needed to encode a character buffer. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Get the number of characters needed to encode a string. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Get the number of characters needed to encode a character buffer. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Get the number of characters needed to encode a character buffer. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Get the bytes that result from encoding a character buffer. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Get the bytes that result from encoding a character buffer. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Get the bytes that result from encoding a character buffer. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Get the bytes that result from encoding a character buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Get the bytes that result from encoding a character buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Get the bytes that result from encoding a character buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Get the bytes that result from encoding a character buffer. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Get the bytes that result from encoding a character buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Get the bytes that result from encoding a character buffer. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Get the bytes that result from encoding a character buffer. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Get the number of characters needed to decode a byte buffer. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Get the number of characters needed to decode a byte buffer. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Get the number of characters needed to decode a byte buffer. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Get the characters that result from decoding a byte buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Get the characters that result from decoding a byte buffer. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Get the characters that result from decoding a byte buffer. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Get the characters that result from decoding a byte buffer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Get a decoder that forwards requests to this object. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Get an encoder that forwards requests to this object. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Gets encoding by name. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Gets encoding by codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Gets encoding by codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Gets encoding by name. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Gets list of known encodings. |
| int [GetHashCode](./gethashcode/)() const override | Hashes encoding. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Get the maximum number of bytes needed to encode a specified number of characters. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Get the maximum number of characters needed to decode a specified number of bytes. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Returns a sequence of bytes that denotes the encoding (e. g. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Decodes a buffer of bytes into a string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Decodes a buffer of bytes into a string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Decodes a buffer of bytes into a string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Decodes a buffer of bytes into a string. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Decodes a buffer of bytes into a string. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Decodes a buffer of bytes into a string. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Decodes a buffer of bytes into a string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Sets decoder fallback. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Sets encoder fallback. |
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
## Fields

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Default codepage value. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.Slides](../../)