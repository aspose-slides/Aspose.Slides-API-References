---
title: MakeScopeGuard()
second_title: Aspose.Slides for C++ API 參考
description: 一個用於建立 ScopedGuard 類別實例的工廠函式。
type: docs
weight: 2809
url: /zh-hant/system/makescopeguard/
---
## System::MakeScopeGuard(F) 函式


一個工廠函式，用於建立 ScopedGuard 類別的實例。

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| The | 構造的 ScopedGuard 物件將要呼叫的函式物件的類型 |

### 引數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| f | F | 用於傳遞至 ScopedGuard 類別建構式的函式物件 |

### 傳回值

一個新的 ScopedGuard 類別實例

## 另請參閱

* 結構 [ScopeGuard](../scopeguard/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)