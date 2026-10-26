---
title: HtmlDecode()
second_title: Aspose.Slides C++ API 參考
description: 解碼 Html 片段。
type: docs
weight: 27
url: /zh-hant/system.web/httputility/htmldecode/
---
## HttpUtility::HtmlDecode(const String\&) 方法

解碼 Html 片段。

```cpp
static String System::Web::HttpUtility::HtmlDecode(const String &str)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要解碼的 Html 片段。 |

### 返回值

已解碼 Html 片段。

## HttpUtility::HtmlDecode(const String\&, const SharedPtr\<IO::TextWriter\>\&) 方法

解碼 Html 片段。

```cpp
static void System::Web::HttpUtility::HtmlDecode(const String &str, const SharedPtr<IO::TextWriter> &output)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要解碼的 Html 片段。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 輸出用的 TextWriter 物件。 |

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [HttpUtility](../)
* 類別 [TextWriter](../../../system.io/textwriter/)
* 命名空間 [System::Web](../../)
* 函式庫 [Aspose.Slides](../../../)