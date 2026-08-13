---
title: Func()
second_title: Aspose.Slides for C++ API 레퍼런스
description: null-Func 를 생성하는 기본 생성자.
type: docs
weight: 1
url: /ko/system/func/func/
---
## Func::Func() 생성자

null-Func 를 생성하는 기본 생성자.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) 생성자

[Func](../) 객체를 생성하고 값(실제 콜백 또는 nullptr)을 할당하는 생성자.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 인수 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg | T\&& | 인수. |

## Func::Func(const Func\&) 생성자

복사 생성자.

```cpp
System::Func<Args>::Func(const Func &func)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) 로부터 데이터를 복사하기 위해. |

## Func::Func(Func\&&) 생성자

이동 생성자.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) 로부터 데이터를 이동하기 위해. |

## 참조

* 클래스 [Func](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)