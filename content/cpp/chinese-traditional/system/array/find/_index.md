---
title: Find()
second_title: Aspose.Slides for C++ API 參考
description: 搜尋指定陣列中符合指定謂詞條件的第一個元素。
type: docs
weight: 651
url: /zh-hant/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) 方法

搜尋指定陣列中符合指定謂詞條件的第一個元素。

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 用於搜尋元素 |
| match | [System::Predicate](../../predicate/)\<T\> | 定義匹配陣列元素條件的謂詞 |

### 返回值

陣列中符合謂詞定義條件的第一個元素的副本；如果沒有則為型別 T 的預設值。

## 另請參閱

* 型別定義 [ArrayPtr](../../arrayptr/)
* 型別定義 [Predicate](../../predicate/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)