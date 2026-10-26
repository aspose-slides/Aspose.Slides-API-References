---
title: ToLower()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的字元轉換為小寫。
type: docs
weight: 235
url: /zh-hant/system/char/tolower/
---
## Char::ToLower(char_t) 方法

將指定的字元轉換為小寫。

```cpp
static char_t System::Char::ToLower(char_t c)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | 要轉換的字元 |

### 回傳值

如果指定的字元是大寫字母，則返回其小寫形式，否則返回原字元

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

將指定的字元轉換為小寫。

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | 要轉換的字元 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 提供特定文化大小寫規則的物件。 |

### 回傳值

如果指定的字元是大寫字母，則返回其小寫形式，否則返回原字元

## 參見

* Typedef [SharedPtr](../../sharedptr/)
* Class [Char](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)