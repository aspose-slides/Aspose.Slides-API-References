---
title: Is()
second_title: Aspose.Slides for C++ API 참조
description: "'is' 선언 패턴 변환을 구현합니다."
type: docs
weight: 2302
url: /ko/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) 함수

Implements 'is' declaration pattern translation.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| PatternT | 검사할 타입. |
| ExpressionT | 왼쪽 표현식 타입. |
| ResultT | 결과 표현식의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | const ExpressionT\& | 검사될 표현식. |
| result | ResultT\& | 검사된 타입에 할당될 변수. |

### 반환 값

true if type check is successful, false otherwise.

## System::Is(const ExpressionT\&, const ConstantT\&) 함수

Implements 'is' constant pattern translation.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ExpressionT | 왼쪽 표현식 타입. |
| ConstantT | 상수 표현식의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | const ExpressionT\& | 검사될 표현식. |
| constant | const ConstantT\& | 왼쪽 표현식과 비교될 표현식. |

### 반환 값

true if type check is successful, false otherwise.

## System::Is(const E\&, const A\&) 함수

Top-level matching function. Applies a pattern to a value.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| A | Pattern type (must inherit from Details::Pattern). |
| E | Type of the value to match. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| e | const E\& | 매치할 값. |
| a | const A\& | 적용할 패턴. |

### 반환 값

true if the pattern matches the value.

## 관련 항목

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)