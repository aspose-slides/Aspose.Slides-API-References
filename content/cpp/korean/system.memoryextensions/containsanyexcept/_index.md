---
title: ContainsAnyExcept()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 읽기 전용 스팬에 세 개의 지정된 값을 제외한 요소가 있는지 확인합니다.
type: docs
weight: 66
url: /ko/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 함수


읽기 전용 스팬에 세 개의 지정된 값을 제외한 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 타입 |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| value0 | const T\& | 제외할 첫 번째 값 |
| value1 | const T\& | 제외할 두 번째 값 |
| value2 | const T\& | 제외할 세 번째 값 |

### 반환값

지정된 값과 다른 요소가 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) 함수


변경 가능한 스팬에 세 개의 지정된 값을 제외한 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 타입 |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 변경 가능한 스팬 |
| value0 | const T\& | 제외할 첫 번째 값 |
| value1 | const T\& | 제외할 두 번째 값 |
| value2 | const T\& | 제외할 세 번째 값 |

### 반환값

지정된 값과 다른 요소가 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 함수


읽기 전용 스팬에 두 개의 지정된 값을 제외한 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 타입 |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| value0 | const T\& | 제외할 첫 번째 값 |
| value1 | const T\& | 제외할 두 번째 값 |

### 반환값

지정된 값과 다른 요소가 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) 함수


변경 가능한 스팬에 두 개의 지정된 값을 제외한 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 타입 |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 변경 가능한 스팬 |
| value0 | const T\& | 제외할 첫 번째 값 |
| value1 | const T\& | 제외할 두 번째 값 |

### 반환값

지정된 값과 다른 요소가 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) 함수


읽기 전용 스팬에 지정된 값을 제외한 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 타입 |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| value | const T\& | 제외할 값 |

### 반환값

지정된 값과 다른 요소가 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) 함수


변경 가능한 스팬에 지정된 값을 제외한 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 타입 |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 변경 가능한 스팬 |
| value | const T\& | 제외할 값 |

### 반환값

지정된 값과 다른 요소가 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 함수


읽기 전용 스팬에 다른 스팬에 있는 값을 제외한 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 타입 |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 스팬 |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 제외할 값이 들어 있는 스팬 |

### 반환값

values에 포함되지 않은 요소가 발견되면 true, 그렇지 않으면 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 함수


변경 가능한 스팬에 읽기 전용 스팬에 있는 값을 제외한 요소가 있는지 확인합니다.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스팬에 있는 요소의 타입 |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 검색할 변경 가능한 스팬 |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 제외할 값이 들어 있는 읽기 전용 스팬 |

### 반환값

values에 포함되지 않은 요소가 발견되면 true, 그렇지 않으면 false

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)