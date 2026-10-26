---
title: MemoryMarshal
second_title: Aspose.Slides for C++ API 참조
description: 메모리 마샬링 구현을 제공합니다. 번역된 코드와의 호환성을 위해서만 사용되며, C++ 측에서는 관리 코드를 지원하지 않습니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 27
url: /ko/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal 클래스

메모리 마샬링 구현을 제공합니다. 번역된 코드와의 호환성을 위해서만 사용되며, C++ 측에서는 관리 코드를 지원하지 않습니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class MemoryMarshal
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | [Span](../../system/span/) 하나의 원시 타입 T를 바이트인 [Span](../../system/span/)로 변환합니다. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | [Span](../../system/span/) 하나의 원시 타입 TFrom를 다른 원시 타입 TTo로 변환합니다. |

## 참고

* 네임스페이스 [System::Runtime::InteropServices](../)
* 라이브러리 [Aspose.Slides](../../)