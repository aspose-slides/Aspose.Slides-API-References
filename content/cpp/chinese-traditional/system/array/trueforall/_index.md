---
title: TrueForAll()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定陣列中的所有元素是否符合指定謂詞所定義的條件。
type: docs
weight: 677
url: /zh-hant/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) method

判斷指定陣列中的所有元素是否符合指定謂詞所定義的條件。

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) 元素，用於匹配條件 |
| match | [System::Predicate](../../predicate/)\<T\> | 用於定義匹配陣列元素之條件的謂詞 |

### 返回值

如果陣列 arr 的所有元素符合謂詞 match 定義的條件，則返回 true；否則返回 false

## 另請參閱

* 類型別名 [ArrayPtr](../../arrayptr/)
* 類型別名 [Predicate](../../predicate/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)