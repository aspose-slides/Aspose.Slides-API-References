---
title: CollectionAssertHelper
second_title: Aspose.Slides C++ API 参考
description: 用于集合相关操作的 Heler API。
type: docs
weight: 1522
url: /zh/system/collectionasserthelper/
---
## CollectionAssertHelper 结构体

用于集合相关操作的 Heler API。

```cpp
class CollectionAssertHelper
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | 检查所有集合元素是否满足谓词。 |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | 检查任意集合元素是否满足谓词。 |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | 序列化两个集合以用于消息表示。 |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | 通过连接元素的字符串表示将集合转换为字符串。 |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | 计算两个集合之间的“diff”。对于每个集合中的每个元素作为键，若该元素在\"expected\"集合中出现次数更多，则结果值为正；若在\"actual\"集合中出现次数更多，则为负；如果两者出现次数相等，则为零。 |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | 将字符串格式化为消息文本。 |
## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)