---
title: CheckValidity()
second_title: Aspose.Slides C++ API 参考
description: 验证 XPathNavigator 中的 XML 数据符合提供的 XML 架构定义语言（XSD）模式。
type: docs
weight: 755
url: /zh/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) 方法


验证位于 [XPathNavigator](../) 中的 XML 数据符合提供的 XML [Schema](../../../system.xml.schema/) 定义语言（XSD）模式。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | 包含用于验证位于 [XPathNavigator](../) 中的 XML 数据的模式的 XmlSchemaSet。 |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | 接收有关模式验证警告和错误信息的 ValidationEventHandler。 |

### 返回值

**true** 如果没有发生模式验证错误；否则 **false**。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)