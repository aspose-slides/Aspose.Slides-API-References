---
title: PrintTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.
type: docs
weight: 2146
url: /ko/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) 함수

지정된 객체가 나타내는 값을 지정된 출력 스트림에 씁니다.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | 스트림에 출력할 [Decimal](../decimal/) 객체 |
| os | ::std::ostream * | 지정된 객체를 출력할 스트림 |

## System::PrintTo(const Details_Exception\&, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) 함수

문자열을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::String](../string/)\& | 출력할 값. |
| os | std::ostream * | 대상 ostream. |

## System::PrintTo(TimeSpan, std::ostream *) 함수

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) function

값을 ostream에 출력합니다. 주로 디버그에 사용됩니다.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## 참조

* 클래스 [DateTime](../datetime/)
* 클래스 [DateTimeOffset](../datetimeoffset/)
* 클래스 [Decimal](../decimal/)
* 클래스 [Details_Exception](../details_exception/)
* 클래스 [ExceptionWrapper](../exceptionwrapper/)
* 클래스 [Guid](../guid/)
* 클래스 [Nullable](../nullable/)
* 클래스 [Object](../object/)
* 클래스 [SmartPtr](../smartptr/)
* 클래스 [String](../string/)
* 클래스 [TimeSpan](../timespan/)
* 클래스 [WeakPtr](../weakptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)