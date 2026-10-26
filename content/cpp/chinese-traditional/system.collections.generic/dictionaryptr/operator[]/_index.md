---
title: operator[]()
second_title: Aspose.Slides for C++ API 參考文件
description: 存取運算子以處理鍵類型轉換。
type: docs
weight: 14
url: /zh-hant/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const X\&) const method

存取運算子以處理鍵類型轉換。

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| X | 來源鍵類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) key. |

### 返回值

傳回與提供的鍵相對應的值的參考，若不存在則新建。

## DictionaryPtr::operator[](const T\&) const method

存取運算子。

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) key. |

### 返回值

傳回與提供的鍵相對應的值的參考，若不存在則新建。

## 另請參閱

* 類別 [DictionaryPtr](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)