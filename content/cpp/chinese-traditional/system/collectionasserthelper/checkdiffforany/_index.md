---
title: CheckDiffForAny()
second_title: Aspose.Slides for C++ API 參考
description: 檢查任意集合元素是否符合謂詞。
type: docs
weight: 27
url: /zh-hant/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) 方法

檢查任意集合元素是否符合謂詞。

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | 要檢查的謂詞。 |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | 要檢查的值。 |

### 回傳值

如果任意元素檢查成功則回傳 true，若全部都通過則回傳 false。

## 另請參閱

* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [ICollection](../../../system.collections.generic/icollection/)
* 結構 [CollectionAssertHelper](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)