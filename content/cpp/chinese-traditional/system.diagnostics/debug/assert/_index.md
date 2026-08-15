---
title: Assert()
second_title: Aspose.Slides for C++ API 參考文件
description: 斷言條件並在失敗時傳送資訊。
type: docs
weight: 14
url: /zh-hant/system.diagnostics/debug/assert/
---
## Debug::Assert(bool) 方法

斷言條件並在失敗時傳送資訊。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| condition | **bool** | 條件值。 |

## Debug::Assert(bool, const String\&) 方法

斷言條件並在失敗時傳送資訊。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| condition | **bool** | 條件值。 |
| message | const [String](../../../system/string/)\& | 在斷言失敗時填入的訊息。 |

## Debug::Assert(bool, const char *) 方法

斷言條件並在失敗時傳送資訊。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const char *message)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| condition | **bool** | 條件值。 |
| message | const char * | 在斷言失敗時填入的訊息。 |

## Debug::Assert(bool, const String\&, const String\&) 方法

斷言條件並在失敗時傳送資訊。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message, const String &detailMessage)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| condition | **bool** | 條件值。 |
| message | const [String](../../../system/string/)\& | 在斷言失敗時填入的訊息。 |
| detailMessage | const [String](../../../system/string/)\& | 在斷言失敗時填入的詳細訊息。 |

## 另請參見

* 類別 [String](../../../system/string/)
* 結構 [Debug](../)
* 命名空間 [System::Diagnostics](../../)
* 函式庫 [Aspose.Slides](../../../)