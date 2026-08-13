---
title: IsNull()
second_title: Aspose.Slides for C++ API 참조
description: 특정 값이 null인지 확인합니다. 산술 및 열거형 타입에 대한 버전입니다.
type: docs
weight: 1
url: /ko/system/testtools/isnull/
---
## TestTools::IsNull(T) 메서드

특정 값이 null인지 확인합니다. [Version](../../version/) 산술 및 열거형 타입에 대해.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 확인되는 값의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | T | null을 확인할 값. |

### 반환값

항상 false를 반환합니다.

## TestTools::IsNull(const T\&) 메서드

특정 값이 null인지 확인합니다. [Version](../../version/) 비산술 및 비열거형 값 유형에 대해.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 확인되는 값의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | null을 확인할 값. |

### 반환값

객체가 nullptr와 비교될 때 true, 그렇지 않으면 false를 반환합니다.

## TestTools::IsNull(const SharedPtr\<T\>\&) 메서드

특정 값이 null인지 확인합니다. [Version](../../version/) 비산술 값 유형에 대해.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 확인되는 값의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | null을 확인할 값. |

### 반환값

객체가 nullptr와 비교될 때 true, 그렇지 않으면 false를 반환합니다.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) 메서드

특정 값이 null인지 확인합니다. [Version](../../version/) 키-값 쌍에 대해.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| K | 키 타입. |
| V | 값 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | 쌍 객체. |

### 반환값

쌍이 null로 간주될 경우 true, 그렇지 않으면 false를 반환합니다.

## TestTools::IsNull(const System::String\&) 메서드

문자열이 null인지 확인합니다.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) 확인할. |

### 반환값

문자열이 null로 간주될 경우 true, 그렇지 않으면 false를 반환합니다.

## 관련 항목

* typedef [SharedPtr](../../sharedptr/)
* 클래스 [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* 클래스 [String](../../string/)
* 구조체 [TestTools](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)