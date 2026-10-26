---
title: Range
second_title: Aspose.Slides for C++ API 참조
description: "시작 인덱스와 끝 인덱스로 범위를 나타냅니다. 이 타입은 스택에 할당하고 값을 복사하거나 참조로 함수에 전달해야 합니다. 절대로 System::SmartPtr 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오."
type: docs
weight: 1197
url: /ko/system/range/
---
## Range 클래스

컬렉션의 시작과 끝 인덱스로 범위를 나타냅니다. 이 타입은 스택에 할당하고 값을 복사하거나 참조로 함수에 전달해야 합니다. 절대로 [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | 컬렉션의 시작에서 지정된 끝 인덱스까지 시작하는 범위를 생성합니다. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | 현재 범위가 지정된 범위와 동일한지 확인합니다. |
| static constexpr [Range](./) [get_All](./get_all/)() | 전체 컬렉션을 나타내는 [Range](./)를 반환합니다. |
| const [Index](../index/)\& [get_End](./get_end/)() const | End 인덱스를 가져옵니다. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Start 인덱스를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const | 현재 범위에 대한 해시 코드를 반환합니다. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | 지정된 컬렉션 길이에 대한 0 기반 시작 오프셋과 길이를 계산합니다. |
| constexpr [Range](./range/)() | 빈 범위를 생성합니다. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | 지정된 시작 및 끝 인덱스로 [Range](./)를 생성합니다. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | 지정된 시작 인덱스에서 컬렉션 끝까지 범위를 생성합니다. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)