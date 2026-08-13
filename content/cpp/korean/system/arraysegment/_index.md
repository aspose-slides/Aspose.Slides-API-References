---
title: ArraySegment
second_title: Aspose.Slides for C++ API 레퍼런스
description: "일차원 배열의 구간을 나타냅니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 절대 사용하지 마세요."
type: docs
weight: 40
url: /ko/system/arraysegment/
---
## ArraySegment 클래스

일차원 배열의 구간을 나타냅니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. 이 유형의 객체를 관리하기 위해 [System::SmartPtr](../smartptr/) 클래스를 절대 사용하지 마세요.

```cpp
template<typename T>class ArraySegment : public System::Object
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 배열 구간 요소의 유형. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>) |  |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>, **int32_t**, **int32_t**) |  |
|  [ArraySegment](./arraysegment/)() |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([ArraySegment](./)\<T\>) |  |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 시맨틱을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 동일하게 간주하여 C# 스타일의 부동 소수점 비교를 에뮬레이션합니다(IEC 60559:1989에 따르면 NaN은 NaN을 포함한 어떤 값과도 동일하지 않지만). |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 동일하게 간주하여 C# 스타일의 부동 소수점 비교를 에뮬레이션합니다(IEC 60559:1989에 따르면 NaN은 NaN을 포함한 어떤 값과도 동일하지 않지만). |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::ArrayPtr](../arrayptr/)\<T\> [get_Array](./get_array/)() const |  |
| **int32_t** [get_Count](./get_count/)() const |  |
| **int32_t** [get_Offset](./get_offset/)() const |  |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| T\& [operator[]](./operator[]/)(**int32_t**) const |  |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| [ArraySegment](./)\<T\> [Slice](./slice/)(**int32_t**, **int32_t**) |  |
| [System::ArrayPtr](../arrayptr/)\<T\> [ToArray](./toarray/)() const |  |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 구문을 구현합니다. |
| void [Unlock](../object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하세요. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // 배열을 생성하고 채웁니다.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // 전체 배열을 포함하는 배열 구간을 생성합니다.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // 배열 구간 항목을 출력합니다.
  Print(fullArray);

  // 배열 구간을 생성합니다.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // 배열 구간 항목을 출력합니다.
  Print(segment);

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
First Second Third
Second Third
*/
```

## 참고

* 클래스 [Object](../object/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)