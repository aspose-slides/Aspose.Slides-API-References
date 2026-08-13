---
title: Encoding
second_title: Aspose.Slides for C++ API 참조
description: 인코딩 서비스.
type: docs
weight: 222
url: /ko/system.text/encoding/
---
## 인코딩 클래스


[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | 인코딩 객체를 복제합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 두 인코딩 간에 바이트를 변환합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 두 인코딩 간에 바이트를 변환합니다. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 인코딩을 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일한 것으로 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일한 것으로 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | ASCII 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | 표준 빅 엔디안 Unicode 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | 표준 빅 엔디안 UTF-32 인코딩 객체를 가져옵니다. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | 메일 에이전트 본문과 호환되는 인코딩 이름을 가져옵니다. |
| virtual int [get_CodePage](./get_codepage/)() | [Windows](../../system.windows/) 코드 페이지 ID를 가져옵니다. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | 디코더 폴백을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | 기본 인코딩을 가져옵니다. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | 엔코더 폴백을 가져옵니다. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | 사람이 읽을 수 있는 인코딩 이름을 가져옵니다. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | 메일 에이전트 헤더와 호환되는 인코딩 이름을 가져옵니다. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | 인코딩을 브라우저에서 콘텐츠 표시용으로 사용할 수 있는지 확인합니다. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | 인코딩을 브라우저에서 콘텐츠 저장용으로 사용할 수 있는지 확인합니다. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | 인코딩을 메일 클라이언트에서 콘텐츠 표시용으로 사용할 수 있는지 확인합니다. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | 인코딩을 메일 클라이언트에서 콘텐츠 저장용으로 사용할 수 있는지 확인합니다. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | 인코딩이 읽기 전용인지 확인합니다. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | 인코딩이 단일 바이트인지 확인합니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Latin1 인코딩을 가져옵니다. 내부 사용 전용. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | 표준 Unicode 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | 표준 UTF-7 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | 표준 UTF-8 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | 클래스 라이브러리에서만 사용되는 내부 전용: 마크되지 않았으며 입력 검증을 수행하지 않습니다. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | IANA와 호환되는 인코딩 이름을 가져옵니다. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | [Windows](../../system.windows/) 코드 페이지 ID를 가져옵니다. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 문자 버퍼를 인코딩하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | 문자 버퍼를 인코딩하는 데 필요한 문자 수를 반환합니다. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 문자 버퍼를 인코딩하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | 문자열을 인코딩하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 문자 버퍼를 인코딩하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | 문자 버퍼를 인코딩하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 바이트 버퍼를 디코드하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 바이트 버퍼를 디코드하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | 바이트 버퍼를 디코드하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | 바이트 버퍼를 디코드한 결과 문자를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 바이트 버퍼를 디코드한 결과 문자를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 바이트 버퍼를 디코드한 결과 문자를 반환합니다. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | 바이트 버퍼를 디코드한 결과 문자를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | 요청을 이 객체에 전달하는 디코더를 가져옵니다. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | 요청을 이 객체에 전달하는 엔코더를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | 이름으로 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | 코드 페이지로 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 코드 페이지로 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 이름으로 인코딩을 가져옵니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | 알려진 인코딩 목록을 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const override | 인코딩을 해시합니다. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | 지정된 문자 수를 인코딩하는 데 필요한 최대 바이트 수를 반환합니다. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | 지정된 바이트 수를 디코드하는 데 필요한 최대 문자 수를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | 인코딩을 나타내는 바이트 시퀀스(예: BOM)를 반환합니다. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | 바이트 버퍼를 문자열로 디코드합니다. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 바이트 버퍼를 문자열로 디코드합니다. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 바이트 버퍼를 문자열로 디코드합니다. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 바이트 버퍼를 문자열로 디코드합니다. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 바이트 버퍼를 문자열로 디코드합니다. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 바이트 버퍼를 문자열로 디코드합니다. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | 바이트 버퍼를 문자열로 디코드합니다. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | 바이트 버퍼를 문자열로 디코드합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사체. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사체. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사체. 사용자 정의 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 디코더 폴백을 설정합니다. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | 엔코더 폴백을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사체. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | 기본 코드 페이지 값. |

## 타입정의

| 타입별칭 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Text](../)
* 라이브러리 [Aspose.Slides](../../)