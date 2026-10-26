---
title: DoTryFinally()
second_title: C++용 Aspose.Slides API 레퍼런스
description: C#의 try[-catch]-finally 문문의 동작을 에뮬레이트하는 단일 함수입니다. 번역기 옵션 finally_statement_as_lambda를 true로 설정하여 C#의 try[-catch]-finally 문장을 번역하면 이 메서드의 호출로 변환됩니다.
type: docs
weight: 2445
url: /ko/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) 함수

C#의 try[-catch]-finally 구문의 동작을 에뮬레이트하는 단일 함수입니다. 번역기 옵션 finally_statement_as_lambda를 true로 설정하여 C#의 try[-catch]-finally 구문을 번역하면 이 메서드의 호출로 변환됩니다.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 에뮬레이트되는 try[-catch]-finally 구문의 try[-catch] 부분을 구현하는 함수 객체의 유형 |
| F | 에뮬레이트되는 try[-catch]-finally 구문의 finally 부분을 구현하는 함수 객체의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tryBlock | T\&& | 에뮬레이트되는 try[-catch]-finally statemet의 try[-catch] 부분 구현을 포함하는 본문을 가진 함수 객체 |
| finallyBlock | F\&& | 에뮬레이트되는 try[-catch]-finally 구문의 finally 부분 구현을 포함하는 본문을 가진 함수 객체 |

## System::DoTryFinally(T\&&, F\&&) 함수

C#의 try[-catch]-finally 구문의 동작을 에뮬레이트하는 단일 함수입니다. 번역기 옵션 finally_statement_as_lambda를 true로 설정하여 C#의 try[-catch]-finally 구문을 번역하면 이 메서드의 호출로 변환됩니다. 이 오버로드는 try[-catch]-finally 구문의 try[-catch] 부분을 구현하는 함수 객체의 반환값이 bool인 경우를 처리합니다.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 에뮬레이트되는 try[-catch]-finally 구문의 try[-catch] 부분을 구현하는 함수 객체의 유형 |
| F | 에뮬레이트되는 try[-catch]-finally 구문의 finally 부분을 구현하는 함수 객체의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tryBlock | T\&& | 에뮬레이트되는 try[-catch]-finally statemet의 try[-catch] 부분 구현을 포함하는 본문을 가진 함수 객체 |
| finallyBlock | F\&& | 에뮬레이트되는 try[-catch]-finally 구문의 finally 부분 구현을 포함하는 본문을 가진 함수 객체 |

## System::DoTryFinally(T\&&, F\&&) 함수

C#의 try[-catch]-finally 구문의 동작을 에뮬레이트하는 단일 함수입니다. 번역기 옵션 finally_statement_as_lambda를 true로 설정하여 C#의 try[-catch]-finally 구문을 번역하면 이 메서드의 호출로 변환됩니다. 이 오버로드는 try[-catch]-finally 구문의 try[-catch] 부분을 구현하는 함수 객체의 반환값이 bool&인 경우를 처리합니다.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 에뮬레이트되는 try[-catch]-finally 구문의 try[-catch] 부분을 구현하는 함수 객체의 유형 |
| F | 에뮬레이트되는 try[-catch]-finally 구문의 finally 부분을 구현하는 함수 객체의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tryBlock | T\&& | 에뮬레이트되는 try[-catch]-finally statemet의 try[-catch] 부분 구현을 포함하는 본문을 가진 함수 객체 |
| finallyBlock | F\&& | 에뮬레이트되는 try[-catch]-finally 구문의 finally 부분 구현을 포함하는 본문을 가진 함수 객체 |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)