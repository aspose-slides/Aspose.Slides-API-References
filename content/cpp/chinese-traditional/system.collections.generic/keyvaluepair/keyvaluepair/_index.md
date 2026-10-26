---
title: KeyValuePair()
second_title: Aspose.Slides for C++ API 參考文件
description: 空鍵值對初始化子。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() 建構子

空鍵值對初始化子。

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) 建構子

建構子。

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | const TKey\& | 鍵。 |
| value | const TValue\& | 值。 |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) 建構子

類型轉換建構子。

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| OtherK | 其他鍵類型。 |
| OtherV | 其他值類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | 配對值。 |

## 另請參閱

* 類別 [KeyValuePair](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)