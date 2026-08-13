---
title: Random
second_title: Aspose.Slides for C++ API 레퍼런스
description: "가짜 난수 생성기를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 이 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 1184
url: /ko/system/random/
---
## Random 클래스

가짜 난수 생성기를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../smartptr/) 포인터로 감싸고, 이 포인터를 함수 인자로 전달하십시오.

```cpp
class Random : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 포함, 같지 않음에도 불구하고 동등하게 간주되는 C#-style 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 포함, 같지 않음에도 불구하고 동등하게 간주되는 C#-style 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) 메서드의 유사체입니다. 사용자 정의 객체의 해시화를 가능하게 합니다. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| **bool** [IsNull](./isnull/)() const | 항상 false를 반환합니다. |
| void [Lock](../object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
| virtual **int32_t** [Next](./next/)() | int32 최대값보다 작은 음수가 아닌 난수를 반환합니다. |
| virtual **int32_t** [Next](./next/)(**int32_t**) | 지정된 최대값보다 작은 음수가 아닌 난수를 반환합니다. |
| virtual **int32_t** [Next](./next/)(**int32_t**, **int32_t**) | 지정된 범위 내에서 난수를 반환합니다. |
| virtual void [NextBytes](./nextbytes/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | 지정된 바이트 배열의 요소들을 난수로 채웁니다. |
| virtual **double** [NextDouble](./nextdouble/)() | 0.0과 1.0 사이의 난수를 반환합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
|  [Random](./random/)() | 시간에 따라 변하는 기본 시드 값을 사용하여 새 인스턴스를 초기화합니다. |
|  [Random](./random/)(**int32_t**) | [System.Random](./) 클래스의 새 인스턴스를 지정된 시드 값으로 초기화합니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | string과 nullptr 경우에 대한 [Object::ReferenceEquals](../object/referenceequals/)의 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../object/referenceequals/)의 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 구문을 구현합니다. |
| void [Unlock](../object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // 무작위 월 번호를 가져와 출력합니다.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // 배열을 무작위 숫자로 채웁니다.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // 배열을 출력합니다.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
이 코드 예제는 다음 출력 결과를 생성합니다:
월: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## 참고

* 클래스 [Object](../object/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)