---
title: FindIndex()
second_title: Aspose.Slides for C++ API 參考
description: 搜尋指定陣列中符合指定謂詞條件的第一個元素。
type: docs
weight: 638
url: /zh-hant/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) 方法

搜尋指定陣列中符合指定謂詞條件的第一個元素。

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 用於在其中搜尋元素 |
| match | [System::Predicate](../../predicate/)\<T\> | 一個定義用於匹配陣列元素條件的謂詞 |

### 返回值

陣列中符合謂詞定義條件的第一個元素的索引，若無則為 -1

## 另請參閱

* 型別定義 [ArrayPtr](../../arrayptr/)
* 型別定義 [Predicate](../../predicate/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)