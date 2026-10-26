---
title: ConstrainedCopy()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 소스에서 시작하여 System.Array에서 요소 범위를 복사합니다.
type: docs
weight: 716
url: /ko/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) 메서드

지정된 소스에서 시작하여 [System.Array](../)의 요소 범위를 복사합니다.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| SrcType | 소스 배열의 요소 형식 |
| DstType | 대상 배열의 요소 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | 소스 배열 |
| srcIndex | **int64_t** | [Index](../../index/)은 복사할 항목 범위의 시작을 지정하는 소스 배열의 인덱스입니다 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 대상 배열 |
| dstIndex | **int64_t** | [Index](../../index/)은 복사된 항목을 삽입하기 시작하는 대상 배열의 인덱스입니다 |
| count | **int64_t** | 복사할 요소 수 |

## 비고

임시 원시 구현, 미완료 항목 없음!

## 관련 항목

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [Array](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)