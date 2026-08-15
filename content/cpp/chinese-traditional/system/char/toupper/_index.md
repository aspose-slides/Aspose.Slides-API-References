---
title: ToUpper()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的字符轉換為大寫。
type: docs
weight: 222
url: /zh-hant/system/char/toupper/
---
## Char::ToUpper(char_t) 方法

將指定字元轉換為大寫。

```cpp
static char_t System::Char::ToUpper(char_t c)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要轉換的字元 |

### 返回值

如果指定字元是小寫字母，則返回其大寫形式；否則 - 指定字元

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

將指定字元轉換為大寫。

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| c | char_t | 要轉換的字元 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 提供特定文化大小寫規則的物件。 |

### 返回值

如果指定字元是小寫字母，則返回其大寫形式；否則 - 指定字元

## 另見

* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [Char](../)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)