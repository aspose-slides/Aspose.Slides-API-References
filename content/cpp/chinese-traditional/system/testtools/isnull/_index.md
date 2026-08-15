---
title: IsNull()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查特定值是否為 null。適用於算術和列舉類型的版本。
type: docs
weight: 1
url: /zh-hant/system/testtools/isnull/
---
## TestTools::IsNull(T) 方法

檢查特定值是否為 null。[Version](../../version/) 用於算術和列舉類型。

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 被檢查值的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | T | 要檢查是否為 null 的值。 |

### 傳回值

永遠回傳 false。

## TestTools::IsNull(const T\&) 方法

檢查特定值是否為 null。[Version](../../version/) 用於非算術和非列舉值型別。

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 被檢查值的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | 要檢查是否為 null 的值。 |

### 傳回值

如果物件與 nullptr 比較結果為 true，則回傳 true，否則回傳 false。

## TestTools::IsNull(const SharedPtr\<T\>\&) 方法

檢查特定值是否為 null。[Version](../../version/) 用於非算術值型別。

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 被檢查值的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | 要檢查是否為 null 的值。 |

### 傳回值

如果物件與 nullptr 比較結果為 true，則回傳 true，否則回傳 false。

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) 方法

檢查特定值是否為 null。[Version](../../version/) 用於鍵值配對。

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| K | 鍵的型別。 |
| V | 值的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | 配對物件。 |

### 傳回值

如果配對被視為 null，則回傳 true，否則回傳 false。

## TestTools::IsNull(const System::String\&) 方法

檢查 string 是否為 null。

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) 用於檢查。 |

### 傳回值

如果字串被視為 null，則回傳 true，否則回傳 false。

## 另請參閱

* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* 類別 [String](../../string/)
* 結構 [TestTools](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)