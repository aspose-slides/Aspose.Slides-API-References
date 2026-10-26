---
title: GetByte()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 형식화된 배열을 원시 바이트 배열로 해석하고 지정된 바이트 오프셋에서 바이트 값을 검색합니다.
type: docs
weight: 27
url: /ko/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) 메서드


지정된 형식화된 배열을 원시 바이트 배열로 해석하고 지정된 바이트 오프셋에서 바이트 값을 검색합니다.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 배열 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 대상 배열 |
| index | int | 검색할 바이트의 0 기반 오프셋 |

### 반환값

지정된 인덱스에 있는 바이트 값

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) 메서드


지정된 형식화된 배열을 원시 바이트 배열로 해석하고 지정된 바이트 오프셋에서 바이트 값을 검색합니다.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 배열 뷰 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 대상 배열 뷰 |
| index | int | 검색할 바이트의 0 기반 오프셋 |

### 반환값

지정된 인덱스에 있는 바이트 값

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) 메서드


지정된 형식화된 배열을 원시 바이트 배열로 해석하고 지정된 바이트 오프셋에서 바이트 값을 검색합니다.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스택 배열 요소의 타입 |
| N | 스택 배열의 크기 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | 대상 스택 배열 |
| index | int | 검색할 바이트의 0 기반 오프셋 |

### 반환값

지정된 인덱스에 있는 바이트 값

## 참고

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [Array](../../array/)
* 클래스 [Buffer](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)