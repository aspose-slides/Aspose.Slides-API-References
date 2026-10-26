---
title: operator<<()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用 UTF-8 編碼將資料插入串流。
type: docs
weight: 716
url: /zh-hant/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) function

使用 UTF-8 編碼將資料插入串流。

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| TKey | 鍵類型。 |
| TValue | 值類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::ostream\& | 輸出串流，用於插入資料。 |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) 插入。 |

### 返回值

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) function

將資料插入串流。

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| TKey | 鍵類型。 |
| TValue | 值類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::wostream\& | 輸出串流，用於插入資料。 |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) 插入。 |

### 返回值

**stream**.

## 另見

* 類別 [KeyValuePair](../keyvaluepair/)
* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)