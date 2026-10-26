---
title: XmlSeverityType
second_title: Aspose.Slides C++ API 参考
description: 表示验证事件的严重程度。
type: docs
weight: 1080
url: /zh/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType 枚举

表示验证事件的严重程度。

```cpp
enum class XmlSeverityType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Error | 0 | 指示在验证实例文档时发生了验证错误。此情况适用于文档类型定义（DTDs）和 XML [Schema](../) 定义语言（XSD）模式。万维 [Web](../../system.web/) 联盟（W3C）的有效性约束被视为错误。如果未创建验证事件处理程序，错误将抛出异常。 |
| Warning | 1 | 指示发生了不是错误的验证事件。当不存在 DTD，或没有 XML [Schema](../) 可用于验证特定元素或属性时，通常会发出警告。与错误不同，如果没有验证事件处理程序，警告不会抛出异常。 |

## 另见

* 命名空间 [System::Xml::Schema](../)
* 库 [Aspose.Slides](../../)