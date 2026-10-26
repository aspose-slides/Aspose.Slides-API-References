---
title: ValidateWhitespace()
second_title: Aspose.Slides for C++ API 参考
description: 验证在当前元素上下文中指定的字符串中的空白是否被允许，并且如果当前元素具有简单内容，则累计用于验证的空白。
type: docs
weight: 196
url: /zh/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) 方法

验证在当前元素上下文中指定的 **string** 的空白是否被允许，并且如果当前元素具有简单内容，则累计用于验证的空白。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | 在当前元素上下文中要验证的空白 **string**。 |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) 方法

验证由指定的 XmlValueGetter 对象返回的空白是否在当前元素上下文中被允许，并且如果当前元素具有简单内容，则累计用于验证的空白。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | 一个 XmlValueGetter 回调，用于将空白值作为与 XML [Schema](../../) 定义语言 (XSD) 属性类型兼容的类型传递。 |

## 参见

* 类型定义 [XmlValueGetter](../../xmlvaluegetter/)
* 类 [String](../../../system/string/)
* 类 [XmlSchemaValidator](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)