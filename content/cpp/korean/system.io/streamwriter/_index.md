---
title: StreamWriter
second_title: Aspose.Slides for C++ API 레퍼런스
description: "문자를 바이트 스트림에 쓰는 라이터를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 해당 포인터를 함수에 인수로 전달하세요."
type: docs
weight: 391
url: /ko/system.io/streamwriter/
---
## StreamWriter 클래스

Represents a writer that writes characters to a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## 메서드

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | 스트림을 닫고 획득한 리소스를 해제합니다. |
| void [Dispose](./dispose/)() override | 현재 객체가 사용한 모든 리소스를 해제하고 기본 스트림을 닫습니다. |
| virtual void [Dispose](./dispose/)(**bool**) | 현재 객체가 사용한 모든 리소스를 해제하고 기본 스트림을 닫습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부용으로만 사용됩니다. |
| void [Flush](./flush/)() override | 버퍼의 내용을 기본 스트림에 플러시하고 그 후 기본 스트림을 플러시합니다. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | [StreamWriter](./)가 메서드 [StreamWriter::Write](./write/)가 호출될 때마다 데이터를 기본 스트림에 플러시할지 여부를 나타내는 값을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | 기본 스트림을 나타내는 객체에 대한 공유 포인터를 반환합니다. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | 현재 사용 중인 인코딩을 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | 현재 사용 중인 [IFormatProvider](../../system/iformatprovider/) 객체를 반환합니다. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | 현재 사용 중인 [IFormatProvider](../../system/iformatprovider/) 객체를 반환합니다. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | 줄 구분자 문자열을 반환합니다. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | 줄 구분자 문자열을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | [StreamWriter](./)가 메서드 [StreamWriter::Write](./write/)가 호출될 때마다 데이터를 기본 스트림에 플러시할지 여부를 지정하는 값을 반환합니다. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | 줄 구분자 문자열을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | [StreamWriter](./) 객체의 인스턴스를 구성합니다. 지정된 기본 스트림에 UTF-8 인코딩과 기본 크기 1024바이트 버퍼를 사용하여 문자를 씁니다. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | [StreamWriter](./) 객체의 인스턴스를 구성합니다. 지정된 인코딩과 기본 크기 1024바이트 버퍼를 사용하여 지정된 기본 스트림에 문자를 씁니다. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | [StreamWriter](./) 객체의 인스턴스를 구성합니다. 지정된 인코딩과 지정된 크기의 버퍼를 사용하여 지정된 기본 스트림에 문자를 씁니다. 매개변수는 [StreamWriter](./) 객체가 해제될 때 기본 스트림을 닫을지 여부를 지정합니다. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | [StreamWriter](./) 객체의 인스턴스를 구성합니다. UTF-8 인코딩과 기본 크기 1024바이트 버퍼를 사용하여 지정된 파일에 문자를 씁니다. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | [StreamWriter](./) 객체의 인스턴스를 구성합니다. 지정된 인코딩과 기본 크기 1024바이트 버퍼를 사용하여 지정된 파일에 문자를 씁니다. 매개변수는 데이터를 파일에 추가할지, 파일을 덮어쓸지를 지정합니다. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | [StreamWriter](./) 객체의 인스턴스를 구성합니다. 지정된 인코딩과 버퍼 크기를 사용하여 지정된 파일에 문자를 씁니다. 매개변수는 데이터를 파일에 추가할지, 파일을 덮어쓸지를 지정합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하면 안 되며, 스마트 포인터나 ThisProtector를 사용하세요. |
| void [Write](./write/)(char_t) override | 지정된 문자를 스트림에 씁니다. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | 지정된 문자열을 스트림에 씁니다. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | 지정된 객체의 문자열 표현을 스트림에 씁니다. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | 지정된 배열의 모든 문자를 스트림에 씁니다. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 지정된 문자 배열에서 지정된 UTF-16 문자 서브범위를 스트림에 씁니다. |
| void [Write](./write/)(const char_t *) override | 지정된 C 문자열을 스트림에 씁니다. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | 지정된 객체의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](../textwriter/write/)(**bool**) | 지정된 부울 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | 지정된 [Decimal](../../system/decimal/) 객체의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](../textwriter/write/)(**double**) | 지정된 배정밀도 부동소수점 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](../textwriter/write/)(int) | 지정된 32비트 정수 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | 지정된 64비트 정수 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](../textwriter/write/)(**float**) | 지정된 단정밀도 부동소수점 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | 지정된 부호 없는 32비트 정수 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | 지정된 부호 없는 64비트 정수 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | 지정된 [TypeInfo](../../system/typeinfo/) 객체의 문자열 표현을 스트림에 씁니다. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | 지정된 형식에 따라 포맷된 값을 스트림에 씁니다. |
| void [WriteLine](./writeline/)() override | 줄 구분자 문자를 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | 지정된 문자열과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | 지정된 객체의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | 지정된 배열의 모든 문자를 줄 구분자 문자와 함께 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 지정된 문자 배열에서 지정된 UTF-16 문자 서브범위를 줄 구분자 문자와 함께 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const char_t *) override | 지정된 C 문자열과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | 지정된 객체의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | 지정된 부울 값의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | 지정된 문자를 줄 구분자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | 지정된 [Decimal](../../system/decimal/) 객체의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | 지정된 배정밀도 부동소수점 값의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | 지정된 32비트 정수 값의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | 지정된 64비트 정수 값의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | 지정된 단정밀도 부동소수점 값의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | 지정된 부호 없는 32비트 정수 값의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | 지정된 부호 없는 64비트 정수 값의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | 지정된 [TypeInfo](../../system/typeinfo/) 객체의 문자열 표현과 줄 구분자 문자를 이어서 스트림에 씁니다. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | 지정된 형식에 따라 포맷된 값을 줄 구분자 문자와 함께 스트림에 씁니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
|  [~StreamWriter](./~streamwriter/)() | 소멸자. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | 소멸자. |

## 참고

* 클래스 [TextWriter](../textwriter/)
* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)