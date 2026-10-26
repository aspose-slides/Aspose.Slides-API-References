---
title: ByteLength()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 배열의 모든 요소가 차지하는 바이트 수를 결정합니다.
type: docs
weight: 14
url: /ko/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) method


지정된 배열의 모든 요소가 차지하는 바이트 수를 결정합니다.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | 배열 요소의 유형 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 배열 |

### 반환값

지정된 배열의 모든 요소가 차지하는 바이트 수

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) method


지정된 배열의 모든 요소가 차지하는 바이트 수를 결정합니다.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | 배열 뷰 요소의 유형 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 배열 뷰 |

### 반환값

지정된 배열 뷰의 모든 요소가 차지하는 바이트 수

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) method


지정된 배열의 모든 요소가 차지하는 바이트 수를 결정합니다.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | 스택 배열 요소의 유형 |
| N | 스택 배열의 크기 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | 스택 배열 |

### 반환값

지정된 스택 배열의 모든 요소가 차지하는 바이트 수

## See Also

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [Array](../../array/)
* 클래스 [Buffer](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)