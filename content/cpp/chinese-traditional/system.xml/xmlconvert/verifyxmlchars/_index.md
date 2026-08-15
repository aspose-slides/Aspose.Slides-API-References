---
title: VerifyXmlChars()
second_title: Aspose.Slides for C++ API 參考文件
description: 如果字串參數中的所有字元及代理配對字元皆為有效的 XML 字元，則回傳傳入的字串；否則拋出 XmlException，並提供首次遇到的無效字元資訊。
type: docs
weight: 105
url: /zh-hant/system.xml/xmlconvert/verifyxmlchars/
---
## XmlConvert::VerifyXmlChars(const String\&) 方法

如果字串參數中的所有字元與代理配對字元皆為有效的 XML 字元，則回傳傳入的字串；否則拋出 XmlException，並提供首次遇到的無效字元資訊。

```cpp
static String System::Xml::XmlConvert::VerifyXmlChars(const String &content)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| content | const [String](../../../system/string/)\& | [String](../../../system/string/)，其中包含要驗證的字元。 |

### 回傳值

如果字串參數中的所有字元與代理配對字元皆為有效的 XML 字元，則回傳傳入的字串；否則拋出 XmlException，並提供首次遇到的無效字元資訊。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlConvert](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)