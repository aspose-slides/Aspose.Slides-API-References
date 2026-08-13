---
title: PickPivotAndPartition()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 퀵소트를 위해 피벗을 선택하고 키-값 쌍을 분할합니다.
type: docs
weight: 105
url: /ko/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 함수


퀵소트를 위해 피벗을 선택하고 키-값 쌍을 분할합니다.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키의 유형 |
| TValue | 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 분할할 키의 스팬 |
| values | [Span](../../system/span/)\<TValue\>\& | 분할할 값의 스팬 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 함수 (키용) |

### 반환값

분할 후 피벗 인덱스

## 참조

* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions::Details](../)
* 라이브러리 [Aspose.Slides](../../)