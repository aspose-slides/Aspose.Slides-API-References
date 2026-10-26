---
title: ScopeGuard
second_title: Aspose.Slides for C++ API 참조
description: 클래스 인스턴스가 범위를 벗어날 때 특정 함수 객체를 실행하는 서비스를 제공하는 서비스 클래스입니다.
type: docs
weight: 1886
url: /ko/system/scopeguard/
---
## ScopeGuard 구조체

클래스 인스턴스가 범위를 벗어날 때 특정 함수 객체를 실행하는 서비스를 제공하는 서비스 클래스입니다.

```cpp
template<typename F>class ScopeGuard
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| F | ScopedGuard 클래스 인스턴스에 의해 호출되는 함수 객체의 유형 |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [Disable](./disable/)() | 가드 호출을 비활성화합니다. |
| [ScopeGuard](./scopeguard/)(F) | 지정된 함수 객체를 호출하도록 설정된 인스턴스를 생성합니다. |
| [~ScopeGuard](./~scopeguard/)() | 생성자에 전달된 함수 객체를 호출합니다. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)