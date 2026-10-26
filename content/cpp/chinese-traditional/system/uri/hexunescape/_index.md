---
title: HexUnescape()
second_title: Aspose.Slides C++ API 參考
description: 將指定的十六進位字元表示法轉換為字元。
type: docs
weight: 443
url: /zh-hant/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) 方法


將指定的十六進位字元表示法轉換為字元。

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | 包含字元十六進位表示法的字串 |
| index | **int32_t**\& | **pattern** 中字元十六進位表示法開始的位置 |

### 返回值

在 **index** 位置由十六進位編碼所表示的字元。若 **index** 處的字元未以十六進位編碼，則返回 **index** 處的字元。**index** 的值會遞增，以指向返回的字元之後的字元。

## 另請參閱

* 類別 [String](../../string/)
* 類別 [Uri](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)