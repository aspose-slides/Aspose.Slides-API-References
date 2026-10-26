---
title: CheckDiffForAll()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 모든 컬렉션 요소가 조건을 만족하는지 확인합니다.
type: docs
weight: 14
url: /ko/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) 메서드

모든 컬렉션 요소가 조건을 만족하는지 확인합니다.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | 확인할 조건식. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | 확인할 값. |

### 반환 값

어떤 요소에서라도 확인이 실패하면 false, 모두 성공하면 true를 반환합니다.

## 참조

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)