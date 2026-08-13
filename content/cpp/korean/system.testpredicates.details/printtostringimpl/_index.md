---
title: PrintToStringImpl()
second_title: C++용 Aspose.Slides API 레퍼런스
description: "System::Object 하위 클래스를 ToString() 메서드를 사용하여 문자열로 출력합니다."
type: docs
weight: 14
url: /ko/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) 함수

[System::Object](../../system/object/) 하위 클래스를 ToString() 메서드를 사용하여 문자열로 출력합니다.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 최종 클래스 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 출력할 객체에 대한 포인터. |
| s | long long | 이 매개변수의 타입에 따라 함수 오버로드를 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환값

[String](../../system/string/) 객체의 문자열 표현 또는 **value**가 null인 경우 "nullptr".

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) 함수

[System::Object](../../system/object/) 하위 클래스를 ToString() 메서드를 사용하여 문자열로 출력합니다.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 최종 클래스 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | 출력할 객체에 대한 포인터. |
| s | long long | 이 매개변수의 타입에 따라 함수 오버로드를 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환값

[String](../../system/string/) 객체의 문자열 표현 또는 **value**가 null인 경우 "nullptr".

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 함수

객체를 ToString() 메서드를 사용하여 문자열로 출력합니다.

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/)을 출력합니다. |
| s | long long | 이 매개변수의 타입에 따라 함수 오버로드를 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환값

[String](../../system/string/) 객체의 문자열 표현.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 함수

객체를 PrintTo 메서드를 사용하여 문자열로 출력합니다.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/)을 출력합니다. |
| s | long long | 이 매개변수의 타입에 따라 함수 오버로드를 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환값

[String](../../system/string/) 객체의 문자열 표현.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 함수

객체를 PrintTo 메서드를 사용하여 문자열로 출력합니다.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/)을 출력합니다. |
| s | long long | 이 매개변수의 타입에 따라 함수 오버로드를 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환값

[String](../../system/string/) 객체의 문자열 표현.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) 함수

pair를 문자열로 출력합니다.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 첫 번째 pair 타입 인수. |
| T2 | 두 번째 pair 타입 인수. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/)을 출력합니다. |
| s | long long | 이 매개변수의 타입에 따라 함수 오버로드를 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환값

첫 번째와 두 번째 pair 구성요소의 결합된 문자열 표현.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) 함수

pair를 문자열로 출력합니다.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 첫 번째 pair 타입 인수. |
| T2 | 두 번째 pair 타입 인수. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/)을 출력합니다. |
| s | long long | 이 매개변수의 타입에 따라 함수 오버로드를 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환값

첫 번째와 두 번째 pair 구성요소의 결합된 문자열 표현.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 함수

STL 스타일 컨테이너를 요소를 (최대 32개) 출력하여 문자열로 변환합니다.

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/)을 출력합니다. |
| s | long long | 이 매개변수의 타입에 따라 함수 오버로드를 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환값

포함된 요소들의 결합된 문자열 표현.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) 함수

다른 타입을 gtest에서 제공하는 함수를 사용하여 문자열로 출력합니다.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../system/object/) 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/)을 출력합니다. |
| s | int | 이 매개변수의 타입에 따라 함수 오버로드를 선택하는 서비스 매개변수이며, 매개변수의 값은 무시됩니다. |

### 반환값

[String](../../system/string/) 객체의 문자열 표현.

## 참고

* 타입 정의 [SharedPtr](../../system/sharedptr/)
* 클래스 [WeakPtr](../../system/weakptr/)
* 클래스 [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* 클래스 [Object](../../system/object/)
* 구조체 [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* 구조체 [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* 구조체 [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* 네임스페이스 [System::TestPredicates::Details](../)
* 라이브러리 [Aspose.Slides](../../)