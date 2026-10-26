---
title: CheckDiffForAny()
second_title: Aspose.Slides for C++ API 参考
description: 检查任意集合元素是否符合谓词。
type: docs
weight: 27
url: /zh/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) 方法

检查任意集合元素是否符合谓词。

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | 要检查的谓词。 |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | 要检查的值。 |

### 返回值

如果任意元素检查成功则返回 true，如果所有元素均通过则返回 false。

## 另见

* Typedef [SharedPtr](../../sharedptr/)
* 类 [ICollection](../../../system.collections.generic/icollection/)
* 结构体 [CollectionAssertHelper](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)