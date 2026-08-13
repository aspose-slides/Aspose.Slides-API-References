---
title: Interlocked
second_title: Aspose.Slides for C++ API 참조
description: 스레드 안전 연산을 위한 API를 제공합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 131
url: /ko/system.threading/interlocked/
---
## Interlocked 클래스

스레드 안전 연산을 위한 API를 제공합니다. 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class Interlocked
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | 값을 원자적으로 증가시킵니다. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | 값을 원자적으로 증가시킵니다. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | 변수의 값을 비교-교환합니다: 변수가 특정 값과 같은지 확인하고, 저장된 값이 기대값과 일치할 때만 새 값을 저장합니다. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | 변수의 값을 비교-교환합니다: 변수가 특정 값과 같은지 확인하고, 저장된 값이 기대값과 일치할 때만 새 값을 저장합니다. 구현되지 않음. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | 변수의 값을 비교-교환합니다: 변수가 특정 값과 같은지 확인하고, 저장된 값이 기대값과 일치할 때만 새 값을 저장합니다. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | 값을 원자적으로 감소시킵니다. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | 값을 원자적으로 감소시킵니다. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | 변수의 값을 교환합니다: 새 값을 저장하고, 저장하기 직전 변수에 있던 값을 반환합니다. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | 변수의 값을 교환합니다: 새 값을 저장하고, 저장하기 직전 변수에 있던 값을 반환합니다. 구현되지 않음. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | 교환-덧셈 절차를 통해 값을 원자적으로 증가시킵니다. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | 교환-덧셈 절차를 통해 값을 원자적으로 증가시킵니다. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | 값을 원자적으로 증가시킵니다. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | 값을 원자적으로 증가시킵니다. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | 64비트 값을 반환합니다. 원자적 연산으로 로드됩니다. |
## 참조

* 네임스페이스 [System::Threading](../)
* 라이브러리 [Aspose.Slides](../../)