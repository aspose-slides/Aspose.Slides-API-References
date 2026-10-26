---
title: MakeDiff()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 컬렉션 간의 'diff' 를 계산합니다. 각 컬렉션의 각 요소를 키로 사용하여, 요소가 \"expected\" 컬렉션에 더 많이 나타나면 양수, \"actual\" 컬렉션에 더 많이 나타나면 음수, 두 컬렉션에 같은 횟수로 나타나면 0이 됩니다.
type: docs
weight: 1
url: /ko/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method


두 컬렉션 간의 'diff' 를 계산합니다. 각 컬렉션의 각 요소를 키로 하여, 요소가 “expected” 컬렉션에 더 많이 나타나면 양수, “actual” 컬렉션에 더 많이 나타나면 음수, 두 컬렉션에 같은 횟수로 나타나면 0이 됩니다.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T1 | Expected 컬렉션 요소 유형. |
| T2 | Actual 컬렉션 요소 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Expected 컬렉션. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Actual 컬렉션. |

### 반환 값

위 규칙에 따라 각 값 비교 결과를 매핑한 결과.

## 관련 항목

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [Dictionary](../../../system.collections.generic/dictionary/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 구조체 [CollectionAssertHelper](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)