---
title: FromAscii()
second_title: Aspose.Slides C++ API 參考
description: 從 ASCII 字串建立 String。
type: docs
weight: 950
url: /zh-hant/system/string/fromascii/
---
## String::FromAscii(const char *) 方法

從 ASCII 字串建立 [String](../)。

```cpp
static String System::String::FromAscii(const char *asciiStr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asciiStr | const char * | 指向使用 ASCII 代碼頁編碼的以 null 結尾字串的指標。 |

### 返回值

代表傳入字串的 [String](../) 物件。

## String::FromAscii(const char *, int) 方法

從 ASCII 字串建立 [String](../)。

```cpp
static String System::String::FromAscii(const char *asciiStr, int len)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asciiStr | const char * | 指向使用 ASCII 代碼頁編碼的字串的指標。 |
| len | int | 要處理的字元數。 |

### 返回值

代表傳入字串的 [String](../) 物件。

## String::FromAscii(const std::string\&) 方法

從 ASCII 字串建立 [String](../)。

```cpp
static String System::String::FromAscii(const std::string &asciiStr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asciiStr | const std::string\& | ASCII 編碼的字串。 |

### 返回值

代表傳入字串的 [String](../) 物件。

## 另請參閱

* 類別 [String](../)
* 名稱空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)