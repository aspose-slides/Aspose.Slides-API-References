---
title: operator!=()
second_title: Aspose.Slides for C++ API 參考
description: 使用相反的「等於」語意比較兩個鍵值對。
type: docs
weight: 703
url: /zh-hant/system.collections.generic/operator_not_equal/
---
## System::Collections::Generic::operator!=(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) 函式

使用相反的「等於」語意比較兩個鍵值對。

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator!=(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TKey | 鍵類型 |
| TValue | 值類型 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 左側運算元 |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 右側運算元 |

### 返回值

如果鍵和值皆不相符則返回 true，否則返回 false。

## 另見

* 類別 [KeyValuePair](../keyvaluepair/)
* 命名空間 [System::Collections::Generic](../)
* 程式庫 [Aspose.Slides](../../)