---
title: Latin1Encoding
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Latin1 인코딩 지원. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 이 유형의 인스턴스를 생성하거나 operator new를 사용하지 마세요. 그렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 313
url: /ko/system.text/latin1encoding/
---
## Latin1Encoding 클래스

Latin1 인코딩 지원. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수로만 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터에 감싸고, 해당 포인터를 함수 인자로 전달하십시오.

```cpp
class Latin1Encoding : public System::Text::ICUEncoding
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
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 취급하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | ASCII 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | 표준 빅 엔디안 Unicode 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | 표준 빅 엔디안 UTF-32 인코딩 객체를 가져옵니다. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | 메일 에이전트 본문과 호환되는 인코딩 이름을 가져옵니다. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | [Windows](../../system.windows/) 코드페이지 ID를 가져옵니다. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | 디코더 폴백을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | 기본 인코딩을 가져옵니다. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | 인코더 폴백을 가져옵니다. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | 인간이 읽을 수 있는 인코딩 이름을 가져옵니다. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | 메일 에이전트 헤더와 호환되는 인코딩 이름을 가져옵니다. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | 인코딩을 브라우저에서 콘텐츠를 표시하는 데 사용할 수 있는지 확인합니다. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | 인코딩을 브라우저에서 콘텐츠를 저장하는 데 사용할 수 있는지 확인합니다. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | 인코딩을 메일 클라이언트에서 콘텐츠를 표시하는 데 사용할 수 있는지 확인합니다. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | 인코딩을 메일 클라이언트에서 콘텐츠를 저장하는 데 사용할 수 있는지 확인합니다. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | 인코딩이 읽기 전용인지 확인합니다. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | 인코딩이 단일 바이트인지 확인합니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Latin1 인코딩을 가져옵니다. INTERNAL USE 전용. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | 표준 Unicode 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | 표준 UTF-7 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | 표준 UTF-8 인코딩 객체를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | 클래스 라이브러리에서만 사용되는 내부용: 표시되지 않으며 입력 검증을 하지 않음. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | IANA 호환 인코딩 이름을 가져옵니다. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | [Windows](../../system.windows/) 코드페이지 ID를 가져옵니다. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | 문자 버퍼를 인코딩하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | 문자 버퍼를 인코딩한 결과 바이트를 반환합니다. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | 바이트 버퍼를 디코딩한 결과 문자를 반환합니다. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | 바이트 버퍼를 디코딩한 결과 문자를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 바이트 버퍼를 디코딩한 결과 문자를 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 바이트 버퍼를 디코딩한 결과 문자를 반환합니다. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | 바이트 버퍼를 디코딩한 결과 문자를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | 이 객체로 요청을 전달하는 디코더를 가져옵니다. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | 이 객체로 요청을 전달하는 인코더를 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | 이름으로 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | 코드페이지로 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 코드페이지로 인코딩을 가져옵니다. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 이름으로 인코딩을 가져옵니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | 알려진 인코딩 목록을 가져옵니다. |
| int [GetHashCode](../encoding/gethashcode/)() const override | 인코딩을 해시합니다. |
| int [GetMaxByteCount](../icuencoding/getmaxbytecount/)(int) override | 지정된 문자 수를 인코딩하는 데 필요한 최대 바이트 수를 반환합니다. |
| int [GetMaxCharCount](../icuencoding/getmaxcharcount/)(int) override | 지정된 바이트 수를 디코딩하는 데 필요한 최대 문자 수를 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | 인코딩을 나타내는 바이트 시퀀스를 반환합니다(예: BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | 바이트 버퍼를 문자열로 디코딩합니다. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 바이트 버퍼를 문자열로 디코딩합니다. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | 바이트 버퍼를 문자열로 디코딩합니다. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | 바이트 버퍼를 문자열로 디코딩합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | 생성자. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
|  [Latin1Encoding](./latin1encoding/)() | 생성자. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | 코드페이지를 사용하여 인코딩을 비교합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | 디코더 폴백을 설정합니다. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | 인코더 폴백을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 강한 포인터 대신 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | 기본 코드페이지 값. |
| static constexpr [LATIN1_CODE_PAGE](./latin1_code_page/) | 코드페이지. |

## 참조

* 클래스 [ICUEncoding](../icuencoding/)
* 네임스페이스 [System::Text](../)
* 라이브러리 [Aspose.Slides](../../)