---
title: FindAll()
second_title: Aspose.Slides C++ API 參考
description: 檢索所有符合指定謂詞所定義條件的元素。
type: docs
weight: 664
url: /zh-hant/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) 方法


檢索所有符合指定謂詞所定義條件的元素。

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 用於搜尋元素 |
| match | [System::Predicate](../../predicate/)\<T\> | 用於定義匹配陣列元素之條件的謂詞 |

### 返回值

一個 [Array](../)，其中包含所有符合指定謂詞所定義條件的元素（若有找到）；否則，為空的 [Array](../)。

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)