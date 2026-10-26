---
title: ValidateWhitespace()
second_title: Aspose.Slides for C++ API 參考
description: 驗證指定字串中的空白是否允許出現在目前元素的上下文中，若目前元素具有簡單內容，則會累積該空白以供驗證。
type: docs
weight: 196
url: /zh-hant/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String&) 方法

驗證在指定的 **字串** 中的空白是否允許出現在當前元素的上下文中，若當前元素具有簡單內容，則會累積空白以供驗證。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | 用於在當前元素上下文中驗證的空白 **字串**。 |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) 方法

驗證由指定的 XmlValueGetter 物件返回的空白是否允許出現在當前元素的上下文中，若當前元素具有簡單內容，則會累積空白以供驗證。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | 用於傳遞白空格值的 XmlValueGetter 回呼，其類型需與 XML [Schema](../../) 定義語言 (XSD) 屬性的類型相容。 |

## 另請參見

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)