---
title: operator==()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用「equals」語意比較兩個鍵值對。對鍵和值皆使用 operator == 或 EqualsTo 方法（取決於哪一個已定義）。
type: docs
weight: 690
url: /zh-hant/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) 函式

比較兩個鍵值對，使用「equals」語意。對鍵和值皆使用 operator == 或 EqualsTo 方法（取決於哪一個已定義）。

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TKey | 鍵類型。 |
| TValue | 值類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 左側運算元。 |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 右側運算元。 |

### 返回值

如果鍵和值皆相同則回傳 true，否則回傳 false。

## 另請參閱

* 類別 [KeyValuePair](../keyvaluepair/)
* 命名空間 [System::Collections::Generic](../)
* 程式庫 [Aspose.Slides](../../)