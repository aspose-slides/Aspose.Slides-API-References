---
title: NumberFormatInfo
second_title: Aspose.Slides for C++ API 레퍼런스
description: "숫자를 형식화하는 방법에 대한 정보를 보유합니다. 설정 연산은 읽기 전용이 아닌 객체에서만 사용할 수 있습니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 248
url: /ko/system.globalization/numberformatinfo/
---
## NumberFormatInfo 클래스

숫자를 형식화하는 방법에 대한 정보를 보유합니다. 설정 연산은 읽기 전용이 아닌 객체에서만 사용할 수 있습니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수로만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고 해당 포인터를 함수 인자로 전달하십시오.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 형식 정보를 복제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | 통화 소수 자리 수를 가져옵니다. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | 통화 소수 구분 기호를 가져옵니다. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | 통화 그룹 구분 기호를 가져옵니다. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | 그룹당 통화 소수 자리 수를 가져옵니다. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | 통화 음수 패턴을 가져옵니다. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | 통화 양수 패턴을 가져옵니다. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | 통화 기호를 가져옵니다. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | 현재 스레드 문화에 정의된 숫자 형식 정보를 가져옵니다. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | 숫자 형태를 표시하는 방법을 지정하는 값을 가져옵니다. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | 불변 문화에 정의된 숫자 형식 정보를 가져옵니다. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 형식이 읽기 전용인지 확인합니다. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Not-a-Number 기호를 가져옵니다. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | 숫자 기호(0~9)를 가져옵니다. |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | 음의 무한대 기호를 가져옵니다. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | 음수 부호를 가져옵니다. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | 소수 자리 수를 가져옵니다. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | 소수 구분 기호를 가져옵니다. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | 숫자 그룹 구분 기호를 가져옵니다. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | 그룹당 자리 수를 가져옵니다. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | 숫자 음수 패턴을 가져옵니다. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | 백분율 값의 소수 자리 수를 가져옵니다. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | 백분율 값의 소수 구분 기호를 가져옵니다. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | 백분율 값의 그룹 구분 기호를 가져옵니다. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | 백분율 값 그룹당 자리 수를 가져옵니다. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | 백분율 음수 패턴을 가져옵니다. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | 백분율 양수 패턴을 가져옵니다. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | 백분율 기호를 가져옵니다. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | 천분율 기호를 가져옵니다. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | 양의 무한대 기호를 가져옵니다. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | 양수 부호를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | 특정 유형의 포매터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 포맷 제공자와 연결된 포매터를 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [NumberFormatInfo](./numberformatinfo/)() | 기본 생성자 (불변 [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | 포매터의 읽기 전용 버전을 가져옵니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | 통화 소수 자리 수를 설정합니다. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | 통화 소수 구분 기호를 설정합니다. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | 통화 그룹 구분 기호를 설정합니다. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | 그룹당 통화 소수 자리 수를 설정합니다. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | 통화 음수 패턴을 설정합니다. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | 통화 양수 패턴을 설정합니다. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | 통화 기호를 설정합니다. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | 숫자 형태를 표시하는 방법을 지정하는 값을 설정합니다. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Not-a-Number 기호를 설정합니다. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 숫자 기호(0~9)를 설정합니다. |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | 음의 무한대 기호를 설정합니다. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | 음수 부호를 설정합니다. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | 소수 자리 수를 설정합니다. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | 소수 구분 기호를 설정합니다. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | 숫자 그룹 구분 기호를 설정합니다. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | 그룹당 자리 수를 설정합니다. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | 숫자 음수 패턴을 설정합니다. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | 백분율 값의 소수 자리 수를 설정합니다. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | 백분율 값의 소수 구분 기호를 설정합니다. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | 백분율 값의 그룹 구분 기호를 설정합니다. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | 백분율 값 그룹당 자리 수를 설정합니다. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | 백분율 음수 패턴을 설정합니다. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | 백분율 양수 패턴을 설정합니다. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | 백분율 기호를 설정합니다. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | 천분율 기호를 설정합니다. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | 양의 무한대 기호를 설정합니다. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | 양수 부호를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아니라 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 관련 항목

* 클래스 [Object](../../system/object/)
* 클래스 [IFormatProvider](../../system/iformatprovider/)
* 클래스 [ICloneable](../../system/icloneable/)
* 네임스페이스 [System::Globalization](../)
* 라이브러리 [Aspose.Slides](../../)