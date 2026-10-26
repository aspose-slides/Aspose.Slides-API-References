---
title: CollectionAssertHelper
second_title: Aspose.Slides for C++ API 參考
description: 用於集合相關操作的輔助 API。
type: docs
weight: 1548
url: /zh-hant/system/collectionasserthelper/
---
## CollectionAssertHelper 結構


用於集合相關操作的輔助 API。

```cpp
class CollectionAssertHelper
```

## Methods

| Method | Description |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | 檢查所有集合元素是否遵守此謂詞。 |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | 檢查是否有任一集合元素遵守此謂詞。 |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | 將兩個集合序列化為訊息表示。 |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | 將集合轉換為字串，方法是連接元素的字串表示。 |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | 計算兩個集合之間的「diff」。對於每個集合中的每個元素作為鍵，如果該元素在 \"expected\" 集合中出現的次數較多，結果值為正；如果在 \"actual\" 集合中出現的次數較多，結果值為負；如果兩個集合中出現次數相等，結果值為零。 |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | 將字串格式化為訊息文字使用。 |
## See Also

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)