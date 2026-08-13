---
title: PrintToString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 적절한 직렬화 함수를 선택하여 객체를 문자열로 출력합니다.
type: docs
weight: 1
url: /ko/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) 함수

Prints object to string by selecting proper serializer function.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 출력. |

### 반환 값

[String](../../system/string/) 전달된 객체의 표현.

## System::TestPredicates::Details::PrintToString(const T\&) 함수

Prints ICollection-style containers to string by printing their elements (not more than 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 출력. |

### 반환 값

포함된 요소들의 결합된 문자열 표현.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) 함수

Prints nullptr to string.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### 반환 값

"nullptr" 문자열.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) 함수

Prints [IEnumerable<bool>](../../system.collections.generic/ienumerable/) collections to string by printing their elements (not more than 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) 출력. |

### 반환 값

포함된 요소들의 결합된 문자열 표현.

## 참고

* 클래스 [IEnumerable](../../system.collections.generic/ienumerable/)
* 구조체 [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* 네임스페이스 [System::TestPredicates::Details](../)
* 라이브러리 [Aspose.Slides](../../)