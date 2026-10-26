---
title: TextWriter
second_title: Aspose.Slides for C++ API 레퍼런스
description: "다양한 대상에 문자 시퀀스를 기록하는 작가를 나타내는 클래스들의 기반 클래스입니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하여 사용하십시오."
type: docs
weight: 443
url: /ko/system.io/textwriter/
---
## TextWriter 클래스

다양한 대상에 문자 시퀀스를 기록하는 작가(writer)를 나타내는 클래스들의 기반 클래스입니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용해서 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하여 사용하십시오.

```cpp
class TextWriter : public System::IDisposable
```

## 메서드

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | 스트림을 닫고 획득된 리소스를 해제합니다. |
| void [Dispose](./dispose/)() override | 현재 객체가 사용한 모든 리소스를 해제하고 기반 스트림을 닫습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual void [Flush](./flush/)() | 버퍼의 내용을 기반 스트림에 플러시합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 현재 사용 중인 인코딩을 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | 현재 사용 중인 [IFormatProvider](../../system/iformatprovider/) 객체를 반환합니다. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | 현재 사용 중인 [IFormatProvider](../../system/iformatprovider/) 객체를 반환합니다. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | 줄 종결자 문자열을 반환합니다. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | 줄 종결자 문자열을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 자료 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 지원합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 락을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 지원합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성하고 모든 내부 자료 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조를 통해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조를 통해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | 줄 종결자 문자열을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 지정된 객체의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](./write/)(**bool**) | 지정된 boolean 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](./write/)(char_t) | 지정된 문자를 스트림에 씁니다. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | 지정된 [Decimal](../../system/decimal/) 객체의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](./write/)(**double**) | 지정된 배정밀도 부동소수점 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](./write/)(int) | 지정된 32비트 정수값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](./write/)(**int64_t**) | 지정된 64비트 정수값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](./write/)(**float**) | 지정된 단정밀도 부동소수점 값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | 지정된 문자열을 스트림에 씁니다. |
| virtual void [Write](./write/)(**uint32_t**) | 지정된 부호 없는 32비트 정수값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](./write/)(**uint64_t**) | 지정된 부호 없는 64비트 정수값의 문자열 표현을 스트림에 씁니다. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 지정된 배열의 모든 문자를 스트림에 씁니다. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 지정된 문자 배열에서 지정된 UTF-16 문자 하위 범위를 스트림에 씁니다. |
| virtual void [Write](./write/)(const char_t *) | 지정된 C 문자열을 스트림에 씁니다. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | 지정된 [TypeInfo](../../system/typeinfo/) 객체의 문자열 표현을 스트림에 씁니다. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | 지정된 형식에 따라 지정된 값을 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)() | 줄 종결자 문자를 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 지정된 객체의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(**bool**) | 지정된 boolean 값의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(char_t) | 지정된 문자를 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | 지정된 [Decimal](../../system/decimal/) 객체의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(**double**) | 지정된 배정밀도 부동소수점 값의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(int) | 지정된 32비트 정수값의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | 지정된 64비트 정수값의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(**float**) | 지정된 단정밀도 부동소수점 값의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | 지정된 문자열을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | 지정된 부호 없는 32비트 정수값의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | 지정된 부호 없는 64비트 정수값의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 지정된 배열의 모든 문자를 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 지정된 문자 배열에서 지정된 UTF-16 문자 하위 범위를 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(const char_t *) | 지정된 C 문자열을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | 지정된 [TypeInfo](../../system/typeinfo/) 객체의 문자열 표현을 줄 종결자 문자와 함께 스트림에 씁니다. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | 지정된 형식에 따라 지정된 값을 줄 종결자 문자와 함께 스트림에 씁니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴하고 모든 내부 자료 구조를 해제합니다. |
| virtual  [~TextWriter](./~textwriter/)() | 소멸자. |

## 타입 별칭

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스에 대한 shared pointer 별칭입니다. |

## 참고

* 클래스 [IDisposable](../../system/idisposable/)
* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)