---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試將指定的字串轉換為 Guid 物件。
type: docs
weight: 157
url: /zh-hant/system/guid/tryparse/
---
## Guid::TryParse(const String\&, Guid\&) 方法


嘗試將指定的字串轉換為 [Guid](../) 物件。

```cpp
static bool System::Guid::TryParse(const String &input, Guid &g)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 要轉換的字串 |
| g | [Guid](../)\& | 若成功，輸出的 [Guid](../) 物件。 |

### 回傳值

若輸入字串代表有效的 [Guid](../)，則回傳 True，否則回傳 false。

## 另見

* 類別 [String](../../string/)
* 類別 [Guid](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)