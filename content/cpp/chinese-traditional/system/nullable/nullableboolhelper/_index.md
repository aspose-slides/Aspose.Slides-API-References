---
title: NullableBoolHelper()
second_title: Aspose.Slides for C++ API 參考文件
description: 輔助函式，用於檢查 this 與 other 是否皆非 null，若是則呼叫 lambda。用於 implementation.s。
type: docs
weight: 105
url: /zh-hant/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method

輔助函式，用於檢查 **this** 與 **other** 是否皆非 null，若是則呼叫 lambda。用於 implementation.s。

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 其他可為 null 的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| other | const T1\& | 需比較的其他可為 null 值。 |
| f | const std::function\<**bool**()>\& | 若 **this** 與 **other** 皆非 null 時要呼叫的 lambda。 |
| default_if_both_are_null | **bool** | 若兩個值皆為 null 時的返回值。 |

### 返回值

若 **this** 或 **other** 任一為 null，則返回 false；若兩者皆為 null，則返回 **default_if_both_are_null**；若兩者皆非 null，則返回 **f** 呼叫的結果。

## 相關參考

* 類別 [Nullable](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)