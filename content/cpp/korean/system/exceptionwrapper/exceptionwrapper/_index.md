---
title: ExceptionWrapper()
second_title: Aspose.Slides for C++ API 참조
description: ExceptionWrapper 클래스의 null 인스턴스를 생성합니다. 이 인스턴스는 어떤 예외도 나타내지 않습니다.
type: docs
weight: 14
url: /ko/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) 생성자

[ExceptionWrapper](../) 클래스의 null 인스턴스를 생성합니다. 이 인스턴스는 예외를 나타내지 않습니다.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) 생성자

전달된 포인터를 포함하는 [ExceptionWrapper](../) 클래스의 인스턴스를 생성합니다.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Exception 클래스 인스턴스에 대한 스마트 포인터. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) 생성자

복사 생성자.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | 복사해야 하는 래퍼 클래스의 다른 인스턴스. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) 생성자

이동 생성자.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | 이동해야 하는 래퍼 클래스의 다른 인스턴스. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) 생성자

파라미터를 Exception 클래스 생성자에 전달하고 새로운 Exception 클래스 인스턴스를 보유하는 스마트 포인터를 생성하는 생성자.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## 참조

* Typedef [ExceptionPtr](../../exceptionptr/)
* 클래스 [ExceptionWrapper](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)