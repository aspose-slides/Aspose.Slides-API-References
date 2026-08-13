---
title: ICUEncoding
second_title: "Aspose.Slides for C++ API 레퍼런스"
description: "ICU 기반 인코딩 구현. 내부 전용. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용하지 마십시오. 그렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 300
url: /ko/system.text/icuencoding/
---
## ICUEncoding 클래스

ICU 기반 인코딩 구현. 내부 전용. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 래핑하고, 해당 포인터를 함수 인자로 전달하십시오.

```cpp
class ICUEncoding : public System::Text::Encoding
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | 인코딩 객체를 복제합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 두 인코딩 간에 바이트를 변환합니다. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 두 인코딩 간에 바이트를 변환합니다. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 인코딩을 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | 표준 빅 엔디언 Unicode 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | 표준 빅 엔디언 UTF-32 인코딩 객체를 가져옵니다. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | 메일 에이전트 본문과 호환되는 인코딩 이름을 가져옵니다. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | [Windows](../../system.windows/) 코드 페이지 ID를 가져옵니다. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | 디코더 폴백을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | 기본 인코딩을 가져옵니다. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | 인코더 폴백을 가져옵니다. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | 사람에게 읽기 쉬운 인코딩 이름을 가져옵니다. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | 메일 에이전트 헤더와 호환되는 인코딩 이름을 가져옵니다. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | 인코딩이 브라우저에서 콘텐츠를 표시하는 데 사용할 수 있는지 확인합니다. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | 인코딩이 브라우저에서 콘텐츠를 저장하는 데 사용할 수 있는지 확인합니다. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | 인코딩이 메일 클라이언트에서 콘텐츠를 표시하는 데 사용할 수 있는지 확인합니다. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | 인코딩이 메일 클라이언트에서 콘텐츠를 저장하는 데 사용할 수 있는지 확인합니다. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | 인코딩이 읽기 전용인지 확인합니다. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | 인코딩이 단일 바이트인지 확인합니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 인코딩을 가져옵니다. 내부 전용. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | 표준 Unicode 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | 표준 UTF-7 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | 표준 UTF-8 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | 클래스 라이브러리에서만 내부적으로 사용됩니다: 마크되지 않았으며 입력 검증을 수행하지 않습니다. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA와 호환되는 인코딩 이름을 가져옵니다. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | [Windows](../../system.windows/) 코드 페이지 ID를 가져옵니다. |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | 문자 버퍼를 인코딩하는 데 필요한 문자 수를 가져옵니다. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 런타임 타입 정보. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | 런타임 타입 정보. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 런타임 타입 정보. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | 런타임 타입 정보. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 런타임 타입 정보. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | 런타임 타입 정보. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | 바이트 버퍼를 디코딩한 결과 문자를 가져옵니다. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | 바이트 버퍼를 디코딩한 결과 문자를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 바이트 버퍼를 디코딩한 결과 문자를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 바이트 버퍼를 디코딩한 결과 문자를 가져옵니다. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | 바이트 버퍼를 디코딩한 결과 문자를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | 이 객체에 요청을 전달하는 디코더를 가져옵니다. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | 이 객체에 요청을 전달하는 인코더를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | 이름으로 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | 코드 페이지로 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 코드 페이지로 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 이름으로 인코딩을 가져옵니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | 알려진 인코딩 목록을 가져옵니다. |
| int [GetHashCode](../encoding/gethashcode/)() const override | 인코딩을 해시합니다. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | 지정된 문자 수를 인코딩하는 데 필요한 최대 바이트 수를 가져옵니다. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | 지정된 바이트 수를 디코딩하는 데 필요한 최대 문자 수를 가져옵니다. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | 인코딩을 나타내는 바이트 시퀀스(예: BOM)를 반환합니다. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | 바이트 버퍼를 문자열로 디코딩합니다. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 바이트 버퍼를 문자열로 디코딩합니다. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | 바이트 버퍼를 문자열로 디코딩합니다. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
|  [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | 생성자. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [ICUEncoding](./)\&) const | 코드페이지를 사용하여 인코딩을 비교합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 디코더 폴백을 설정합니다. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | 인코더 폴백을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | 기본 코드 페이지 값. |

## 참조

* 클래스 [Encoding](../encoding/)
* 네임스페이스 [System::Text](../)
* 라이브러리 [Aspose.Slides](../../)