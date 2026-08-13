---
title: MakeScopeGuard()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ScopedGuard 클래스의 인스턴스를 생성하는 팩터리 함수입니다.
type: docs
weight: 2809
url: /ko/system/makescopeguard/
---
## System::MakeScopeGuard(F) 함수

ScopedGuard 클래스의 인스턴스를 생성하는 팩토리 함수입니다.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| 그 | 구성된 ScopedGuard 객체에 의해 호출될 함수 객체의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| f | F | ScopedGuard 클래스 생성자에 전달할 함수 객체 |

### 반환값

새로운 ScopedGuard 클래스 인스턴스

## 참고

* 구조체 [ScopeGuard](../scopeguard/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)