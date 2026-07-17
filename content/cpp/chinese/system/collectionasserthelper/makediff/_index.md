---
title: MakeDiff()
second_title: Aspose.Slides for C++ API 参考
description: 计算两个集合之间的“diff”。对于每个集合的每个元素作为键，如果元素在 \"expected\" 集合中出现的次数更多，则结果值为正；如果元素在 \"actual\" 集合中出现的次数更多，则为负；如果两者出现次数相等，则为零。
type: docs
weight: 1
url: /zh/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) 方法

计算两个集合之间的“diff”。对于每个集合的每个元素作为键，如果元素在 \"expected\" 集合中出现的次数更多，则结果值为正；如果元素在 \"actual\" 集合中出现的次数更多，则为负；如果两者出现次数相等，则为零。

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | Expected collection element type. |
| T2 | Actual collection element type. |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Expected collection. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Actual collecion. |

### 返回值

Map of per-value comparison results as per rules above.

## 参见

* Typedef [SharedPtr](../../sharedptr/)
* 类 [Dictionary](../../../system.collections.generic/dictionary/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 结构体 [CollectionAssertHelper](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)