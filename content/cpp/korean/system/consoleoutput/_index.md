---
title: ConsoleOutput
second_title: Aspose.Slides for C++ API 참조
description: "표준 출력 스트림을 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 209
url: /ko/system/consoleoutput/
---
## ConsoleOutput 클래스

표준 출력 스트림을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../makeobject/) 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하지 마십시오. 그렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../smartptr/) 포인터로 감싸고 해당 포인터를 함수 인수로 전달하십시오.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | 스트림을 닫고 획득한 리소스를 해제합니다. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | 현재 객체가 사용한 모든 리소스를 해제하고 기본 스트림을 닫습니다. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교에서는 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교에서는 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | 버퍼의 내용을 기본 스트림으로 플러시합니다. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | 항상 ASCII 인코딩을 반환합니다. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | 현재 사용 중인 [IFormatProvider](../iformatprovider/) 객체를 반환합니다. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | 현재 사용 중인 [IFormatProvider](../iformatprovider/) 객체를 반환합니다. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | 줄 구분자 문자열을 반환합니다. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | 줄 구분자 문자열을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) 메서드와 동일합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출과 동일합니다. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 대상 타입에 의해 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# ‘is’ 연산자와 동일합니다. |
| void [Lock](../object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드와 동일합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | 줄 구분자 문자열을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터로 설정합니다(공유 포인터가 아닌). 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) 메서드와 동일합니다. 사용자 정의 객체를 문자열로 변환합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 구문을 구현합니다. |
| void [Unlock](../object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [Write](./write/)(**bool**) override | 지정된 bool 값의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | 지정된 객체의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(char_t) override | 지정된 문자 값을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)([Decimal](../decimal/)) override | [Decimal](../decimal/) 값의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(**double**) override | double 정밀 부동소수점 값의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(**int32_t**) override | 32비트 정수 값의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(**int64_t**) override | 64비트 정수 값의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(**float**) override | 단정밀 부동소수점 값의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(const [String](../string/)\&) override | 지정된 문자열 객체를 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(**uint32_t**) override | 부호 없는 32비트 정수 값의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(**uint64_t**) override | 부호 없는 64비트 정수 값의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | 지정된 문자 배열의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 지정된 문자 배열의 값 범위에 대한 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(const char_t *) override | 지정된 C 문자열을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | 지정된 [TypeInfo](../typeinfo/) 객체의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 씁니다. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | 지정된 32비트 정수 값의 문자열 표현을 스트림에 씁니다. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | 지정된 형식에 따라 지정된 값을 스트림에 씁니다. |
| void [WriteLine](./writeline/)() override | 현재 줄 구분자를 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | 지정된 객체의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(**bool**) override | 지정된 bool 값의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(char_t) override | 지정된 문자 값을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | [Decimal](../decimal/) 값의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(**double**) override | double 정밀 부동소수점 값의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(int) override | 32비트 정수 값의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(**int64_t**) override | 64비트 정수 값의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(**float**) override | 단정밀 부동소수점 값의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | 지정된 문자열 객체를 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(**uint32_t**) override | 부호 없는 32비트 정수 값의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(**uint64_t**) override | 부호 없는 64비트 정수 값의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | 지정된 문자 배열의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 지정된 문자 배열의 값 범위에 대한 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const char_t *) override | 지정된 C 문자열을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | 지정된 [TypeInfo](../typeinfo/) 객체의 문자열 표현을 현재 줄 구분자와 함께 출력 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | 지정된 값을 지정된 형식에 따라 줄 구분 문자와 함께 스트림에 씁니다. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | 소멸자입니다. |

## 참조

* 클래스 [TextWriter](../../system.io/textwriter/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)