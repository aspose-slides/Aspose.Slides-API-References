---
title: HasFlag()
second_title: Aspose.Slides for C++ API 參考
description: 判斷在指定的 enum 值的位元表示中，是否已設定指定的位元。
type: docs
weight: 14
url: /zh-hant/system/enum/hasflag/
---
## Enum::HasFlag(E, E) 方法


判斷在指定的 enum 值的位元表示中，是否已設定指定的位元。

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | E | 測試的 enum 值 |
| mask | E | 用於檢查 value 位元的遮罩 |

### 返回值

若 **mask** 中已設定的位元也在 **value** 中設定，則為 true，否則為 false

## 另請參閱

* Struct [Enum](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)