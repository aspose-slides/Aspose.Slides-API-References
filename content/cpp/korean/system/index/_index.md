---
title: Index
second_title: Aspose.Slides for C++ API 참조
description: "컬렉션에 대한 인덱스를 나타냅니다. 인덱스는 시작부터이거나 끝부터일 수 있습니다. 이 유형은 스택에 할당하고 값 또는 레퍼런스로 함수에 전달해야 합니다. 절대 System::SmartPtr 클래스를 사용하여 이 유형의 객체를 관리하지 마세요."
type: docs
weight: 1015
url: /ko/system/index/
---
## 인덱스 클래스

컬렉션에 대한 인덱스를 나타냅니다. 인덱스는 시작부터이거나 끝부터일 수 있습니다. 이 유형은 스택에 할당하고 값 또는 레퍼런스로 함수에 전달해야 합니다. 절대 [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마세요.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | 현재 인스턴스와 지정된 [Index](./)가 동일한 위치를 나타내는지 확인합니다. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | 컬렉션의 끝을 기준으로 하는 [Index](./)를 생성합니다. |
| static constexpr [Index](./) [get_End](./get_end/)() | 컬렉션의 끝을 나타내는 [Index](./) 객체를 가져옵니다. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | 인덱스가 끝에서부터인지 여부를 나타내는 값을 가져옵니다. |
| static constexpr [Index](./) [get_Start](./get_start/)() | 컬렉션의 시작을 나타내는 [Index](./) 객체를 가져옵니다. |
| constexpr **int32_t** [get_Value](./get_value/)() const | 인덱스 값을 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const | 현재 인덱스에 대한 해시 코드를 반환합니다. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | 현재 [Index](./)를 지정된 길이의 컬렉션 시작부터의 오프셋으로 변환합니다. |
| constexpr [Index](./index/)() | 컬렉션의 시작을 나타내는 인스턴스를 생성합니다. |
| constexpr [Index](./index/)(**int32_t**) | 컬렉션 시작부터 지정된 위치를 나타내는 인스턴스를 생성합니다. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | 지정된 인덱스를 나타내는 인스턴스를 생성합니다. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)