---
title: HtmlEncode()
second_title: Aspose.Slides for C++ API 參考文件
description: 編碼 Html 片段。
type: docs
weight: 40
url: /zh-hant/system.web/httputility/htmlencode/
---
## HttpUtility::HtmlEncode(const String\&) 方法

編碼 Html 片段。

```cpp
static String System::Web::HttpUtility::HtmlEncode(const String &str)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要編碼的 Html 片段。 |

### 返回值

已編碼的 Html 片段。

## HttpUtility::HtmlEncode(const SharedPtr\<Object\>\&) 方法

編碼 Html 片段。

```cpp
static String System::Web::HttpUtility::HtmlEncode(const SharedPtr<Object> &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要編碼的 Html 片段。 |

### 返回值

已編碼的 Html 片段。

## HttpUtility::HtmlEncode(const String\&, const SharedPtr\<IO::TextWriter\>\&) 方法

編碼 Html 片段。

```cpp
static void System::Web::HttpUtility::HtmlEncode(const String &str, const SharedPtr<IO::TextWriter> &output)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要編碼的 Html 片段。 |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 用於輸出的 TextWriter 物件。 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [HttpUtility](../)
* 類別 [Object](../../../system/object/)
* 類別 [TextWriter](../../../system.io/textwriter/)
* 命名空間 [System::Web](../../)
* Library [Aspose.Slides](../../../)