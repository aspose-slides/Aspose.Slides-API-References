---
title: CheckDiffForAll()
second_title: Aspose.Slides for C++ API 參考
description: 檢查所有集合元素是否符合該謂詞。
type: docs
weight: 14
url: /zh-hant/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method

檢查所有集合元素是否符合該謂詞。

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | 要檢查的謂詞。 |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | 要檢查的值。 |

### 返回值

如果任何元素檢查失敗則返回 false，全部通過則返回 true。

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)