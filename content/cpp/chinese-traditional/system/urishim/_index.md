---
title: UriShim
second_title: Aspose.Slides for C++ API 參考
description: 服務類別。
type: docs
weight: 1431
url: /zh-hant/system/urishim/
---
## UriShim 類別


服務類別。

```cpp
class UriShim
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static void [EscapeAsciiChar](./escapeasciichar/)(char16_t, const [System::ArrayPtr](../arrayptr/)\<char16_t\>\&, **int32_t**\&) | 將字元轉換為已轉義的十六進位表示形式。 |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | 將字元轉換為已轉義的十六進位表示形式。 |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | 從已轉義的十六進位表示形式還原字元。 |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | 檢查給定的模式是否為已轉義的十六進位形式。 |
## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)