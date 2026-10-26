---
title: TieTuple()
second_title: Aspose.Slides for C++ API 參考
description: 建立與某些值綁定的元組。
type: docs
weight: 3056
url: /zh-hant/system/tietuple/
---
## System::TieTuple(Args\&&...) 函式

建立與某些值綁定的元組。

```cpp
template<typename...> ValueTuple<Args...> System::TieTuple(Args &&... args)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| Args | [Tuple](../tuple/) 成員類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| args | Args\&&... | [Tuple](../tuple/) 要綁定的值。 |

### 返回值

新建立的元組已綁定至給定的值。

## 另請參閱

* 類別 [ValueTuple](../valuetuple/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)