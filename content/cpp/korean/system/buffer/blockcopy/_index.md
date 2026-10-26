---
title: BlockCopy()
second_title: Aspose.Slides for C++ API 참조
description: 소스 버퍼에서 지정된 바이트 수를 대상 버퍼로 복사합니다.
type: docs
weight: 1
url: /ko/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) 메서드

지정된 바이트 수를 소스 버퍼에서 대상 버퍼로 복사합니다.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const **uint8_t** * | 소스 버퍼에 대한 포인터 |
| srcOffset | int | 복사가 시작되는 소스 버퍼의 바이트 오프셋 |
| dst | **uint8_t** * | 대상 버퍼에 대한 포인터 |
| dstOffset | int | 데이터를 삽입하기 시작하는 대상 버퍼의 바이트 오프셋 |
| count | int | 복사할 바이트 수 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) 메서드

두 개의 지정된 타입 배열을 바이트의 원시 배열로 해석하고, 그 중 하나에서 다른 하나로 데이터를 복사합니다.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TSrc | 소스 배열 요소의 타입 |
| TDst | 대상 배열 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | 소스 배열 |
| srcOffset | int | 복사가 시작되는 소스 배열의 바이트 오프셋 |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | 대상 배열 |
| dstOffset | int | 데이터를 삽입하기 시작하는 대상 배열의 바이트 오프셋 |
| count | int | 복사할 바이트 수 |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) 메서드

두 개의 지정된 배열을 바이트의 원시 배열로 해석하고, 그 중 하나에서 다른 하나로 데이터를 복사합니다.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | 소스 배열 |
| srcOffset | int | 복사가 시작되는 소스 배열의 바이트 오프셋 |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | 대상 배열 |
| dstOffset | int | 데이터를 삽입하기 시작하는 대상 배열의 바이트 오프셋 |
| count | int | 복사할 바이트 수 |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) 메서드

두 개의 지정된 타입 배열을 바이트의 원시 배열로 해석하고, 그 중 하나에서 다른 하나로 데이터를 복사합니다.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TSrc | 소스 배열 뷰 요소의 타입 |
| TDst | 대상 배열 뷰 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | 소스 배열 뷰 |
| srcOffset | int | 복사가 시작되는 소스 배열 뷰의 바이트 오프셋 |
| dst | const System::Details::ArrayView\<TDst\>\& | 대상 배열 뷰 |
| dstOffset | int | 데이터를 삽입하기 시작하는 대상 배열 뷰의 바이트 오프셋 |
| count | int | 복사할 바이트 수 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) 메서드

두 개의 지정된 타입 배열을 바이트의 원시 배열로 해석하고, 그 중 하나에서 다른 하나로 데이터를 복사합니다.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TSrc | 소스 배열 요소의 타입 |
| TDst | 대상 배열 뷰 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | 소스 배열 |
| srcOffset | int | 복사가 시작되는 소스 배열의 바이트 오프셋 |
| dst | const System::Details::ArrayView\<TDst\>\& | 대상 배열 뷰 |
| dstOffset | int | 데이터를 삽입하기 시작하는 대상 배열 뷰의 바이트 오프셋 |
| count | int | 복사할 바이트 수 |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) 메서드

두 개의 지정된 타입 배열을 바이트의 원시 배열로 해석하고, 그 중 하나에서 다른 하나로 데이터를 복사합니다.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TSrc | 소스 배열 뷰 요소의 타입 |
| TDst | 대상 배열 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | 소스 배열 뷰 |
| srcOffset | int | 복사가 시작되는 소스 배열 뷰의 바이트 오프셋 |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | 대상 배열 |
| dstOffset | int | 데이터를 삽입하기 시작하는 대상 배열의 바이트 오프셋 |
| count | int | 복사할 바이트 수 |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) 메서드

두 개의 지정된 타입 배열을 바이트의 원시 배열로 해석하고, 그 중 하나에서 다른 하나로 데이터를 복사합니다.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TSrc | 소스 스택 배열 요소의 타입 |
| NS | 소스 스택 배열의 크기 |
| TDst | 대상 스택 배열 요소의 타입 |
| ND | 대상 스택 배열의 크기 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | 소스 스택 배열 |
| srcOffset | int | 복사가 시작되는 소스 스택 배열의 바이트 오프셋 |
| dst | const System::Details::StackArray\<TDst, ND\>\& | 대상 스택 배열 |
| dstOffset | int | 데이터를 삽입하기 시작하는 대상 스택 배열의 바이트 오프셋 |
| count | int | 복사할 바이트 수 |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) 메서드

두 개의 지정된 타입 배열을 바이트의 원시 배열로 해석하고, 그 중 하나에서 다른 하나로 데이터를 복사합니다.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TSrc | 소스 배열 요소의 타입 |
| TDst | 대상 스택 배열 요소의 타입 |
| ND | 대상 스택 배열의 크기 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | 소스 배열 |
| srcOffset | int | 복사가 시작되는 소스 배열의 바이트 오프셋 |
| dst | const System::Details::StackArray\<TDst, ND\>\& | 대상 스택 배열 |
| dstOffset | int | 데이터를 삽입하기 시작하는 대상 스택 배열의 바이트 오프셋 |
| count | int | 복사할 바이트 수 |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) 메서드

두 개의 지정된 타입 배열을 바이트의 원시 배열로 해석하고, 그 중 하나에서 다른 하나로 데이터를 복사합니다.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TSrc | 소스 스택 배열 요소의 타입 |
| NS | 소스 스택 배열의 크기 |
| TDst | 대상 배열 요소의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | 소스 스택 배열 |
| srcOffset | int | 복사가 시작되는 소스 스택 배열의 바이트 오프셋 |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | 대상 배열 |
| dstOffset | int | 데이터를 삽입하기 시작하는 대상 배열의 바이트 오프셋 |
| count | int | 복사할 바이트 수 |

## 참조

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [Buffer](../)
* 클래스 [Array](../../array/)
* 클래스 [ArrayBase](../../arraybase/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)