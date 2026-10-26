---
title: ExceptionWrapper
second_title: C++용 Aspose.Slides API 레퍼런스
description: Exception 클래스에서 파생된 예외를 래핑하는 템플릿입니다.
type: docs
weight: 833
url: /ko/system/exceptionwrapper/
---
## ExceptionWrapper 클래스

Template that represents wrapper of exceptions that are derived from Exception 클래스.

```cpp
template<typename T>class ExceptionWrapper
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | [ExceptionWrapper](./) 클래스의 null 인스턴스를 생성합니다. 이 인스턴스는 예외를 나타내지 않습니다. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | 전달된 포인터를 포함하는 [ExceptionWrapper](./) 클래스의 인스턴스를 생성합니다. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | 복사 생성자. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | 이동 생성자. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | 파라미터를 Exception 클래스의 생성자에게 전달하고 새 Exception 클래스 인스턴스를 보유하는 스마트 포인터를 생성하는 생성자. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | SharedPtr<Object> 로의 암시적 형변환 연산자 |
| T * [operator->](./operator_minus_greater/)() const | Exception 객체의 멤버에 접근할 수 있습니다. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | 대입 연산자. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | 이동 대입 연산자. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Exception 타입에 대한 [System::TypeInfo](../typeinfo/) 객체를 얻는 단축키. |

## 형식정의

| 타입정의 | 설명 |
| --- | --- |
| [ExceptionType](./exceptiontype/) | 캐스팅 함수에 사용됩니다. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)