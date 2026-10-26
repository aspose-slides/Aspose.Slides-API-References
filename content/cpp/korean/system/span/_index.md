---
title: Span
second_title: Aspose.Slides for C++ API 참조
description: "C++20의 std::span과 유사한 임의 메모리의 연속 영역을 나타냅니다."
type: docs
weight: 1262
url: /ko/system/span/
---
## Span 클래스

임의 메모리의 연속 영역을 나타내며 C++20의 std::span과 유사합니다.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | 이 클래스는 객체들의 연속 시퀀스를 안전하게 작업할 수 있는 타입-안전 방식을 제공합니다. 배열, 스택 배열 또는 원시 포인터를 래핑하면서 경계 검사를 유지할 수 있습니다. [Span](./)는 가리키는 메모리를 소유하지 않으며 기존 메모리에 대한 뷰일 뿐입니다. |

## 메서드

| Method | Description |
| --- | --- |
| void [Clear](./clear/)() const | span의 내용을 모든 요소를 기본값으로 설정하여 지웁니다. |
| void [Fill](./fill/)(const T\&) const | 지정된 값으로 span을 채웁니다. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | 배열을 [Span](./) 로 변환합니다. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)