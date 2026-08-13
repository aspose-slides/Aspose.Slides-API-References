---
title: IConvertible
second_title: Aspose.Slides for C++ API 레퍼런스
description: "구현된 참조형 또는 값형의 값을 동등한 값을 갖는 공용 언어 런타임 유형으로 변환하는 메서드를 정의합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용해서 생성하지 마십시오. 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하여 사용하십시오."
type: docs
weight: 937
url: /ko/system/iconvertible/
---
## IConvertible 클래스

구현된 참조형 또는 값형의 값을 동등한 값을 갖는 공용 언어 런타임 유형으로 변환하는 메서드를 정의합니다. 이 클래스의 객체는 [System::MakeObject()](../makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용해서 생성하지 마십시오. 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../smartptr/) 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하여 사용하십시오.

```cpp
class IConvertible : public virtual System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 동등하지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 동등하지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출과 유사합니다. |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | 이 인스턴스에 대한 유형 코드를 반환합니다. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../object/lock/)() | C# lock() 문 구문을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자입니다. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 할당 연산자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 레퍼런스로 값 형식 객체를 nullptr와 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 [Boolean](../boolean/) 값으로 변환합니다. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 8비트 uint32_teger 로 변환합니다. |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 유니코드 문자로 변환합니다. |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 [System::DateTime](../datetime/) 로 변환합니다. |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 [System::Decimal](../decimal/) 숫자로 변환합니다. |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 배정밀도 부동소수점 숫자로 변환합니다. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 16비트 signed integer 로 변환합니다. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 32비트 signed integer 로 변환합니다. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 64비트 signed integer 로 변환합니다. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 8비트 signed integer 로 변환합니다. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 단정밀도 부동소수점 숫자로 변환합니다. |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 [System::String](../string/) 로 변환합니다. |
| virtual [String](../string/) [ToString](./tostring/)() const | C# [Object.ToString()](../object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 [System::Object](../object/)(System::Type) 로 변환합니다. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 16비트 uint32_teger 로 변환합니다. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 32비트 uint32_teger 로 변환합니다. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 64비트 uint32_teger 로 변환합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 구문을 구현합니다. |
| void [Unlock](../object/unlock/)() | C# lock() 문 구문 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Object](../object/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)