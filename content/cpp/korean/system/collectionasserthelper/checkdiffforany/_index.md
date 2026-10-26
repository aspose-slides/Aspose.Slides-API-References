---
title: CheckDiffForAny()
second_title: Aspose.Slides C++ API 레퍼런스
description: 컬렉션의 어떤 요소가 해당 술어를 만족하는지 확인합니다.
type: docs
weight: 27
url: /ko/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method

컬렉션의 어떤 요소가 해당 술어를 만족하는지 확인합니다.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | 검사할 술어. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | 검사할 값들. |

### 반환값

어떤 요소라도 검사에 성공하면 true, 모두 통과하면 false.

## 참고

* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [ICollection](../../../system.collections.generic/icollection/)
* 구조체 [CollectionAssertHelper](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)