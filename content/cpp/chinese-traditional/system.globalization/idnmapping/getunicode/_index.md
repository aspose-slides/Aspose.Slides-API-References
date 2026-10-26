---
title: GetUnicode()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 ascii 網域名稱轉換為 Unicode 等價字串。
type: docs
weight: 92
url: /zh-hant/system.globalization/idnmapping/getunicode/
---
## IdnMapping::GetUnicode(const String\&) const method


[Convert](../../../system/convert/) ascii 網域名稱的 Unicode 等價字串。

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | [String](../../../system/string/) 需要轉換。 |

### 傳回值

ascii 字串的 Unicode 等價字串。

## IdnMapping::GetUnicode(const String\&, int) const method


[Convert](../../../system/convert/) ascii 網域名稱的 Unicode 等價字串。

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii, int index) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | [String](../../../system/string/) 需要轉換。 |
| index | int | 要轉換的子字串的起始索引 |

### 傳回值

ascii 字串的 Unicode 等價字串。

## IdnMapping::GetUnicode(const String\&, int, int) const method


[Convert](../../../system/convert/) ascii 網域名稱的 Unicode 等價字串。

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii, int index, int count) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | [String](../../../system/string/) 需要轉換。 |
| index | int | 要轉換的子字串的起始索引 |
| count | int | 要轉換的字元數。 |

### 傳回值

ascii 字串的 Unicode 等價字串。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IdnMapping](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)