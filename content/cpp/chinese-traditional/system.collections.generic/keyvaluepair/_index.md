---
title: KeyValuePair
second_title: Aspose.Slides for C++ API 參考
description: "鍵和值的配對。此類型應在堆疊上分配，並以值或參照方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 378
url: /zh-hant/system.collections.generic/keyvaluepair/
---
## KeyValuePair 類別


鍵和值的配對。此類型應在堆疊上分配，並以值或引用方式傳遞給函式。切勿使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此類型的物件。

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## 方法

| 方法 | 說明 |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | 取得鍵。 |
| const TValue\& [get_Value](./get_value/)() const | 取得值。 |
| int [GetHashCode](./gethashcode/)() const | 計算鍵值配對的雜湊，方式是將鍵與值的雜湊值進行 XOR。 |
| **bool** [IsNull](./isnull/)() const | 永遠回傳 false。 |
|  [KeyValuePair](./keyvaluepair/)() | 空的鍵值配對初始化子。 |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | 建構子。 |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | 型別轉換建構子。 |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | 針對繼承自 IComparer<KeyValuePair<TKey, TValue>> 類別的補丁，什麼也不比較。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 將鍵值配對轉換為字串。 |

## 另見

* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)