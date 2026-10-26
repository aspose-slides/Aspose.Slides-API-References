---
title: ValidateText()
second_title: Aspose.Slides for C++ API 参考
description: 验证在当前元素上下文中指定的文本字符串是否被允许，并在当前元素具有简单内容时累计进行验证的文本。
type: docs
weight: 183
url: /zh/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) method

验证在当前元素上下文中指定的文本 **字符串** 是否被允许，并在当前元素具有简单内容时累计进行验证的文本。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### Arguments

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | 在当前元素上下文中用于验证的文本 **字符串**。 |

## XmlSchemaValidator::ValidateText(XmlValueGetter) method

验证由指定的 XmlValueGetter 对象返回的文本是否在当前元素上下文中被允许，并在当前元素具有简单内容时累计进行验证的文本。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### Arguments

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | 用于将文本值作为与 XML [Schema](../../) 定义语言 (XSD) 属性类型兼容的类型传递的 XmlValueGetter 回调。 |

## See Also

* 类型定义 [XmlValueGetter](../../xmlvaluegetter/)
* 类 [String](../../../system/string/)
* 类 [XmlSchemaValidator](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)