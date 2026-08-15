---
title: IsWeakPtr
second_title: Aspose.Slides for C++ API 參考文件
description: "Traits 類別，用於檢查特定類別是否為 System::WeakPtr 的特殊化。 不會檢查實例是否真的處於弱模式。"
type: docs
weight: 1756
url: /zh-hant/system/isweakptr/
---
## IsWeakPtr 結構


Traits 類別 用於檢查特定類別是否為 [System::WeakPtr](../weakptr/) 的特殊化。 不會檢查實例是否真的處於弱模式。

```cpp
template<class T>class IsWeakPtr : public System::detail::is_a<T, System::WeakPtr>
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 被測試的型別。 |

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)