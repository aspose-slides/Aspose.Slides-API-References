---
title: ValidateText()
second_title: Aspose.Slides for C++ API 參考文件
description: 驗證指定的文字字串是否在當前元素的上下文中被允許，且如果當前元素具有簡單內容，則會累積該文字以供驗證。
type: docs
weight: 183
url: /zh-hant/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) method

驗證指定的文字 **string** 是否在當前元素的上下文中被允許，且如果當前元素具有簡單內容，則會累積該文字以供驗證。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | 要在當前元素的上下文中驗證的文字 **string**。 |

## XmlSchemaValidator::ValidateText(XmlValueGetter) method

驗證由指定的 XmlValueGetter 物件返回的文字是否在當前元素的上下文中被允許，且如果當前元素具有簡單內容，則會累積該文字以供驗證。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | 用於傳遞文字值的 XmlValueGetter 回呼，以符合屬性的 XML [Schema](../../) 定義語言 (XSD) 類型的相容型別。 |

## 另請參閱

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)