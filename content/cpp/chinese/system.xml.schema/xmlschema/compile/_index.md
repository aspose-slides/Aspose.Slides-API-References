---
title: Compile()
second_title: Aspose.Slides for C++ API 参考
description: 将 XML SchemaObject Model (SOM) 编译为用于验证的模式信息。用于检查以编程方式构建的 SOM 的语法和语义结构。语义验证检查在编译期间执行。
type: docs
weight: 352
url: /zh/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) 方法

将 XML [Schema](../../)[Object](../../../system/object/) 模型 (SOM) 编译为用于验证的模式信息。用于检查以编程方式构建的 SOM 的语法和语义结构。语义验证检查在编译期间执行。

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有关 XML [Schema](../../) 验证错误信息的验证事件处理程序。 |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) 方法

将 XML [Schema](../../)[Object](../../../system/object/) 模型 (SOM) 编译为用于验证的模式信息。用于检查以编程方式构建的 SOM 的语法和语义结构。语义验证检查在编译期间执行。

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有关 XML [Schema](../../) 验证错误信息的验证事件处理程序。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 用于解析 **include** 和 **import** 元素中引用的命名空间。 |

## 另见

* 类型定义 [ValidationEventHandler](../../validationeventhandler/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlSchema](../)
* 类 [XmlResolver](../../../system.xml/xmlresolver/)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)