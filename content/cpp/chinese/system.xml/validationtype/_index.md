---
title: ValidationType
second_title: Aspose.Slides C++ API 参考
description: 指定要执行的验证类型。
type: docs
weight: 729
url: /zh/system.xml/validationtype/
---
## ValidationType 枚举

指定要执行的验证类型。

```cpp
enum class ValidationType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 不执行任何验证，也不抛出验证错误。此设置创建一个符合 XML 1.0 标准的非验证解析器。 |
| Auto | 1 | 如果找到 DTD 或模式信息，则进行验证。 |
| DTD | 2 | 根据 DTD 进行验证。 |
| XDR | 3 | 根据 XML-Data Reduced (XDR) 模式进行验证，包括内联 XDR 模式。XDR 模式使用 **x-schema** 命名空间前缀或 [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) 值进行识别。 |
| Schema | 4 | 根据 XML [Schema](../../system.xml.schema/) 定义语言 (XSD) 模式进行验证，包括内联 XML 模式。XML 模式通过使用 **schemaLocation** 属性或提供的 **Schemas** 与命名空间 URI 关联。 |

## 参见

* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)