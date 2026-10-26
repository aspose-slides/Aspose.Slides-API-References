---
title: Get()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 주어진 튜플의 N번째 요소를 가져오는 함수입니다. 기본 객체에 대한 오버로드입니다.
type: docs
weight: 2406
url: /ko/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) 함수

주어진 튜플의 N번째 요소를 가져오는 함수입니다. 기본 객체에 대한 오버로드입니다.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| N | 요소 인덱스입니다. |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | 검사할 객체입니다. |

### 반환값

객체로 캐스팅된 N번째 튜플 요소의 값입니다.

## System::Get(const T\&) 함수

주어진 튜플의 N번째 요소를 가져오는 함수입니다. Deconstruct 메서드를 가진 객체에 대한 오버로드입니다.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| N | 요소 인덱스입니다. |
| T | 검사할 객체의 형식입니다. |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| object | const T\& | 검사할 객체입니다. |

### 반환값

N번째 튜플 요소의 값입니다.

## System::Get(const SharedPtr\<T\>\&) 함수

주어진 튜플의 N번째 요소를 가져오는 함수입니다. 공유 포인터에 대한 오버로드입니다.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| N | 요소 인덱스입니다. |
| T | 검사할 객체의 형식입니다. |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | 검사할 객체입니다. |

### 반환값

N번째 튜플 요소의 값입니다.

## System::Get(T\&, const Index\&) 함수

컬렉션[index] 표현식에 대한 구현입니다.

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 컬렉션 형식입니다. |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| collection | T\& | 컬렉션 객체입니다. |
| index | const [Index](../index/)\& | [System.Index](../index/) 형식의 요소 인덱스입니다. |

### 반환값

계산된 오프셋에 있는 컬렉션 요소입니다.

## System::Get(T\&, const Range\&) 함수

지정된 범위에 의해 정의된 컬렉션의 슬라이스를 반환합니다.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| collection | T\& | 슬라이스할 컬렉션입니다. |
| range | const [Range](../range/)\& | 슬라이스 경계를 지정하는 범위입니다. |

### 반환값

계산된 시작 오프셋과 길이에서 컬렉션의 뷰 또는 슬라이스입니다.

## System::Get(const ValueTuple\<Args...\>\&) 함수

값 튜플의 N번째 요소를 가져옵니다.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| N | 요소 인덱스입니다. |
| Args | 튜플 요소들입니다. |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | 요소를 가져올 튜플입니다. |

### 반환값

N번째 튜플 요소의 값입니다.

## 참고

* Typedef [SharedPtr](../sharedptr/)
* 클래스 [Object](../object/)
* 클래스 [Index](../index/)
* 클래스 [Range](../range/)
* 클래스 [ValueTuple](../valuetuple/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)