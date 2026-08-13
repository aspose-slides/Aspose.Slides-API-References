---
title: Object
second_title: Aspose.Slides for C++ API 레퍼런스
description: C#에서 System.Object 클래스에서 사용할 수 있는 메서드를 이용할 수 있게 해 주는 기본 클래스입니다. 변환된 환경에서 사용되는 모든 비정형 클래스는 이를 상속해야 합니다.
type: docs
weight: 1132
url: /ko/system/object/
---
## 객체 클래스

C#의 [System.Object](./) 클래스에서 사용할 수 있는 메서드를 이용할 수 있게 해 주는 기본 클래스입니다. 변환된 환경에서 사용되는 모든 비정형 클래스는 이를 상속해야 합니다.

```cpp
class Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | C# [Object.Equals](./equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 구현합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음에도 불구하고. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 구현합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음에도 불구하고. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 반환합니다. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | C# [Object.GetHashCode()](./gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | 객체의 실제 유형을 반환합니다. C# [System.Object.GetType()](./gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](./lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | C# [Object.MemberwiseClone()](./memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](./object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](./object/)([Object](./) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](./referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](./referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](./sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 반환합니다. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../string/) [ToString](./tostring/)() const | C# [Object.ToString()](./tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | C# typeof([System.Object](./)) 구문을 구현합니다. |
| void [Unlock](./unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](./weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](./~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [ptr](./ptr/) | 스마트 포인터 유형의 별명입니다. |

## 비고

C# [System.Object](./) 클래스에서 사용할 수 있는 메서드와 함께, 변환된 코드 환경에 특화된 몇몇 개념도 지원합니다. 여기에는 스마트 포인터 클래스([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/))에서 사용되는 레퍼런스 카운팅 및 메모리 관리, 디버그 등과 관련된 기타 서비스가 포함됩니다.

각 [Object](./)는 두 개의 레퍼런스 카운터를 갖습니다: 공유 레퍼런스 카운터와 약한 레퍼런스 카운터. 약한 레퍼런스 카운터는 항상 [Object](./) 자체가 아니라 분리된 데이터 구조에 저장되어 약한 포인터가 참조된 객체보다 오래 살아남을 수 있게 합니다. 스마트 레퍼런스 카운터는 ENABLE_EXTERNAL_REFCOUNT 매크로 상태에 따라 객체 자체에 저장되거나 동일한 분리 구조에 저장됩니다. 기본적으로 디버그 빌드에서는 활성화되고 릴리스 빌드에서는 비활성화됩니다. 스마트 포인터 카운터가 객체 자체에 저장되는 경우, 약한 포인터가 존재할 때만 분리된 데이터 구조가 생성됩니다. 그렇지 않으면 객체와 함께 생성됩니다.

모든 스마트 포인터는 이 두 레퍼런스 카운터를 사용하며 동일하고 유일한 소유 그룹에 기여합니다.

[Object](./) 서브클래스가 스택에 생성되면, 해당 객체에 대한 스마트 포인터를 만들 수 없으며, 그렇지 않으면 스택 삭제 문제가 발생합니다.

이 유형은 값 타입으로 스택에 할당하거나 [System::MakeObject()](../makeobject/) 함수를 사용하여 힙에 할당할 수 있습니다. 객체가 할당된 후에는 이 두 사용 사례를 혼용해서는 안 됩니다: 스택에 할당된 객체에 [SmartPtr](../smartptr/) 포인터를 가지는 것은 엄격히 금지됩니다.

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)