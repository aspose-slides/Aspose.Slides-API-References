---
title: SetByte()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 형식화된 배열을 원시 바이트 배열로 해석하고 지정된 바이트 오프셋에 지정된 바이트 값을 설정합니다.
type: docs
weight: 40
url: /ko/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) method

지정된 형식화된 배열을 원시 바이트 배열로 해석하고 지정된 바이트 오프셋에 지정된 바이트 값을 설정합니다.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements of the array |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | 대상 배열 |
| index | int | 설정할 바이트의 0 기반 오프셋 |
| value | **uint8_t** | 설정할 바이트 값 |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) method

지정된 형식화된 배열을 원시 바이트 배열로 해석하고 지정된 바이트 오프셋에 지정된 바이트 값을 설정합니다.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements of the array |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | 대상 배열 보기 |
| index | int | 설정할 바이트의 0 기반 오프셋 |
| value | **uint8_t** | 설정할 바이트 값 |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) method

지정된 형식화된 배열을 원시 바이트 배열로 해석하고 지정된 바이트 오프셋에 지정된 바이트 값을 설정합니다.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | The type of elements of the array |
| N | The size of the stack array |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | 대상 스택 배열 |
| index | int | 설정할 바이트의 0 기반 오프셋 |
| value | **uint8_t** | 설정할 바이트 값 |

## 참조

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [Array](../../array/)
* 클래스 [Buffer](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)