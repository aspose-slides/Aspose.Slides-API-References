---
title: BinarySearchImpl()
second_title: Aspose.Slides for C++ API 참조
description: 공통 이진 검색 구현.
type: docs
weight: 118
url: /ko/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) function

공통 이진 검색 구현.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | span에 있는 요소의 타입 |
| TValue | 검색할 값의 타입 |
| TCompareFunc | 비교를 위한 함수 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 검색할 span |
| value | const TValue\& | 검색할 값 |
| compareFunc | TCompareFunc | 값과 span 요소를 비교하고 **int32_t** (-1, 0, 1)을 반환하는 함수 |

### 반환값

[Index](../../system/index/) 검색된 요소 또는 삽입 지점의 비트 보수

## 참고

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 네임스페이스 [System::MemoryExtensions::Details](../)
* 라이브러리 [Aspose.Slides](../../)