---
title: Validate()
second_title: Aspose.Slides C++ API 参考
description: "验证 XmlDocument 是否符合 XmlDocument::get_Schemas 列表中包含的 XML Schema Definition Language (XSD) 架构。"
type: docs
weight: 573
url: /zh/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) 方法

验证 [XmlDocument](../) 是否符合包含在 [XmlDocument::get_Schemas](../get_schemas/) 列表中的 XML [Schema](../../../system.xml.schema/) 定义语言 (XSD) 架构。

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | 接收有关模式验证警告和错误信息的 [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) 对象。 |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) 方法

验证指定的 [XmlNode](../../xmlnode/) 对象是否符合 [XmlDocument::get_Schemas](../get_schemas/) 列表中 XML [Schema](../../../system.xml.schema/) 定义语言 (XSD) 架构。

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | 接收有关模式验证警告和错误信息的 [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) 对象。 |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 用于验证的从 [XmlDocument](../) 创建的 [XmlNode](../../xmlnode/) 对象。 |

## 参见

* 类型定义 [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlDocument](../)
* 类 [XmlNode](../../xmlnode/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)