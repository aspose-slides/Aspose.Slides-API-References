---
title: MakeYieldEnumerable()
second_title: Aspose.Slides for C++ API 參考文件
description: 從 yield 函式建立 IEnumerable。
type: docs
weight: 2419
url: /zh-hant/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction<T>&) 函式

從 yield 函式建立 IEnumerable。

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 序列中元素的類型 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fnc | const Details::YieldFunction<T>& | 要執行的 yield 函式 |

### 返回值

IEnumerable 的共享指標

## 參見

* 型別別名 [SharedPtr](../sharedptr/)
* 類別 [IEnumerable](../../system.collections.generic/ienumerable/)
* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)