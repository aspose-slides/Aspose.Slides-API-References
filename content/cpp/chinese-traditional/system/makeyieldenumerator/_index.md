---
title: MakeYieldEnumerator()
second_title: Aspose.Slides for C++ API 參考文件
description: 從 yield 函式建立 IEnumerator。
type: docs
weight: 2432
url: /zh-hant/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) 函式


從 yield 函式建立 IEnumerator。

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 序列中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | 要執行的 yield 函式 |

### 返回值

對 IEnumerator 的共享指標

## 另請參閱

* 型別定義 [SharedPtr](../sharedptr/)
* 類別 [IEnumerator](../../system.collections.generic/ienumerator/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)