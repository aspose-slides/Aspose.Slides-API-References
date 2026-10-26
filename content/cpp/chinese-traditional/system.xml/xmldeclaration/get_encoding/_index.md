---
title: get_Encoding()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 傳回 XML 文件的編碼層級。
type: docs
weight: 14
url: /zh-hant/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() 方法

返回 XML 文件的編碼級別。

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### 回傳值

有效的字元編碼名稱。

## 備註

XML 最常支援的字元編碼名稱如下：

| 類別 | 編碼名稱 |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (其中 "n" 是 1 到 9 的數字) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

此值為可選項目。如果未設定值，此方法會回傳 [String::Empty](../../../system/string/empty/)。如果未包含編碼屬性，則在寫入或儲存文件時假定為 UTF-8 編碼。

## 參見

* 類別 [String](../../../system/string/)
* 類別 [XmlDeclaration](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)