---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考文件
description: 嘗試將指定的字串轉換為等效的列舉常數。
type: docs
weight: 79
url: /zh-hant/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) 方法

嘗試將指定的字串轉換為等效的列舉常數。

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) 被解釋為包含列舉常數的名稱 |
| result | E\& | 輸出參數；如果轉換成功，則包含函式的轉換結果 |

### 傳回值

如果轉換成功則返回 true，否則為 false

## Enum::TryParse(const String\&, bool, E\&) 方法

嘗試將指定的字串轉換為等效的列舉常數。

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) 被解釋為包含列舉常數的名稱 |
| ignoreCase | **bool** | 指定在解釋字串時是否忽略大小寫 |
| result | E\& | 輸出參數；如果轉換成功，則包含函式返回的轉換結果 |

### 傳回值

如果轉換成功則返回 true，否則為 false

## 相關參考

* 類別 [String](../../string/)
* 結構 [Enum](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)