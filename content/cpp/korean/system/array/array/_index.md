---
title: Array()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빈 배열을 생성합니다.
type: docs
weight: 1
url: /ko/system/array/array/
---
## Array::Array() constructor

빈 배열을 생성합니다.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) constructor

채우는 생성자.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| count | int | 배열의 초기 크기 |
| init | const T\& | 배열을 채우는 데 사용되는 초기값 |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) constructor

채우는 생성자.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ValueType | 초기값의 타입 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | 배열의 초기 크기 |
| init | [ValueType](../valuetype/) | 배열을 채우는 데 사용되는 초기값 |

## Array::Array(int, const T) constructor

채우는 생성자.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| count | int | 배열의 초기 크기 |
| inits | const T | 배열을 채우는 값들 |

## Array::Array(vector_t\&&) constructor

이동 생성자.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | **vector_t**\&& | 배열이 요소를 획득하는 std::vector |

## Array::Array(const vector_t\&) constructor

복사 생성자.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| assgn | const **vector_t**\& | 값을 복사할 std::vector |

## Array::Array(const std::vector\<Q\>\&) constructor

[Array](../) 객체를 생성하고, 값의 타입이 **T**와 동일하지만 **UnderlyingType**와 다른 std::vector 객체에서 복사된 값으로 채웁니다.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 복사할 std::vector 객체 요소들의 타입 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | 값을 복사할 std::vector |

## Array::Array(std::vector\<Q\>\&&) constructor

[Array](../) 객체를 생성하고, 값의 타입이 **T**와 동일하지만 **UnderlyingType**와 다른 std::vector 객체에서 이동된 값으로 채웁니다.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 이동할 std::vector 객체 요소들의 타입 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | 값을 복사할 std::vector |

## Array::Array(std::initializer_list\<UnderlyingType\>) constructor

[Array](../) 객체를 생성하고, 지정된 **UnderlyingType** 요소를 포함하는 초기화 목록에서 값으로 채웁니다.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | 배열을 채우는 요소를 포함하는 초기화 목록 |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) constructor

[Array](../) 객체를 생성하고, 지정된 **UnderlyingType** 요소를 포함하는 배열에서 값으로 채웁니다.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| InitArraySize | **init** 배열의 요소 개수. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../)를 생성되는 배열에 복사합니다. |

## Array::Array(std::initializer_list\<bool\>, int) constructor

[Array](../) 객체를 생성하고, bool 타입 요소를 포함하는 지정된 초기화 목록에서 값으로 채웁니다.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | 배열을 채우는 요소를 포함하는 초기화 목록 |

## 참고

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)