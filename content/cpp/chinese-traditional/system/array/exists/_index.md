---
title: Exists()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷指定的 Array 物件是否包含符合指定謂詞要求的元素。
type: docs
weight: 781
url: /zh-hant/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) method


判斷指定的 [Array](../) 物件是否包含符合指定謂詞要求的元素。

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | 要在其中搜尋元素的陣列 |
| match | std::function\<**bool**(T)> | 定義需求並檢查元素是否符合的函式物件 |

### 傳回值

如果 **arr** 包含符合 **match** 所定義需求的元素，則返回 True

## 參見

* 型別定義 [ArrayPtr](../../arrayptr/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)