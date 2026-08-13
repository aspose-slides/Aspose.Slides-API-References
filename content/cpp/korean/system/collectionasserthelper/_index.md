---
title: CollectionAssertHelper
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션 관련 작업을 위한 Heler API.
type: docs
weight: 1548
url: /ko/system/collectionasserthelper/
---
## CollectionAssertHelper struct

컬렉션 관련 작업을 위한 Heler API.

```cpp
class CollectionAssertHelper
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | 모든 컬렉션 요소가 해당 프레디케이트를 만족하는지 확인합니다. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | 어떤 컬렉션 요소든 해당 프레디케이트를 만족하는지 확인합니다. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | 두 컬렉션을 메시지 표현을 위해 직렬화합니다. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | 컬렉션을 요소들의 문자열 표현을 연결하여 문자열로 변환합니다. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | 두 컬렉션 사이의 'diff'를 계산합니다. 각 컬렉션의 각 요소를 키로 하여, 요소가 \"expected\" 컬렉션에 더 많이 등장하면 결과값이 양수가 되고, \"actual\" 컬렉션에 더 많이 등장하면 결과값이 음수가 되며, 두 컬렉션에서 등장 횟수가 동일하면 결과값이 0이 됩니다. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | 메시지 텍스트로 사용할 문자열을 포맷합니다. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)