---
title: AddRange()
second_title: Aspose.Slides for C++ API 參考
description: 將 'Range' 標頭加入目前的請求。
type: docs
weight: 690
url: /zh-hant/system.net/httpwebrequest/addrange/
---
## HttpWebRequest::AddRange(int32_t) 方法

將 '[Range](../../../system/range/)' 標頭加入目前的請求。

```cpp
virtual void System::Net::HttpWebRequest::AddRange(int32_t range)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| range | **int32_t** | 請求範圍的開始或結束。 |

## HttpWebRequest::AddRange(System::String, int32_t, int32_t) 方法

將 '[Range](../../../system/range/)' 標頭加入目前的請求。

```cpp
virtual void System::Net::HttpWebRequest::AddRange(System::String rangeSpecifier, int32_t from, int32_t to)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rangeSpecifier | [System::String](../../../system/string/) | 指定範圍的單位。 |
| from | **int32_t** | 請求範圍的開始。 |
| to | **int32_t** | 請求範圍的結束。 |

## 參見

* 類別 [HttpWebRequest](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)