---
title: Compare()
second_title: Aspose.Slides C++ API 參考
description: 比較兩個排序鍵。
type: docs
weight: 92
url: /zh-hant/system.globalization/sortkey/compare/
---
## SortKey::Compare(const SortKeyPtr&, const SortKeyPtr&) method


比較兩個排序鍵。

```cpp
static int System::Globalization::SortKey::Compare(const SortKeyPtr &sortkey1, const SortKeyPtr &sortkey2)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| sortkey1 | const [SortKeyPtr](../../sortkeyptr/)\& | 第一個排序鍵。 |
| sortkey2 | const [SortKeyPtr](../../sortkeyptr/)\& | 第二個排序鍵。 |

### 回傳值

- 1 如果 **sortkey1** 小於 **sortkey2**，1 - 如果 **sortkey1** 大於 **sortkey2**，0 - 如果 **sortkey1** 等於 **sortkey2**。

## 參見

* Typedef [SortKeyPtr](../../sortkeyptr/)
* Class [SortKey](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)