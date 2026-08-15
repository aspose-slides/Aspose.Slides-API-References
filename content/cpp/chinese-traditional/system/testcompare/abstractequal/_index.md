---
title: AbstractEqual()
second_title: Aspose.Slides for C++ API 參考
description: 比較兩個未知類型的集合。
type: docs
weight: 14
url: /zh-hant/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) method

比較兩個未知類型的集合。

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | 集合元素類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | 左側集合。 |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | 右側集合。 |

### Return Value

若集合相符（例如兩者皆為 null），或尺寸相同且元素相符，則返回 true，否則返回 false。

## See Also

* 類別 [ICollection](../../../system.collections.generic/icollection/)
* 結構體 [TestCompare](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)