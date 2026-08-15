---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考文件
description: 嘗試將指定的字串轉換為 DateTimeOffset 物件。
type: docs
weight: 729
url: /zh-hant/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) 方法


嘗試將指定的字串轉換為 [DateTimeOffset](../) 物件。

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 要轉換。 |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) 等於 **input**。 |

### 回傳值

若 **input** 轉換成功則回傳 true，否則回傳 false。

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) 方法


嘗試將指定的字串轉換為 [DateTimeOffset](../) 物件，使用指定的格式提供者和格式樣式。

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 要轉換。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供者。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 日期與時間的格式樣式。 |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) 等於 **input**。 |

### 回傳值

若 **input** 轉換成功則回傳 true，否則回傳 false。

## 另見

* 列舉 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [DateTimeOffset](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)