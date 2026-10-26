---
title: Initialize()
second_title: Aspose.Slides C++ API 参考
description: 初始化 XmlSchemaValidator 对象的状态。
type: docs
weight: 118
url: /zh/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() 方法

初始化 [XmlSchemaValidator](../) 对象的状态。

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```

## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) 方法

使用指定用于部分验证的 [XmlSchemaObject](../../xmlschemaobject/)，初始化 [XmlSchemaValidator](../) 对象的状态。

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | 一个用于初始化 [XmlSchemaValidator](../) 对象的验证上下文以进行部分验证的 [XmlSchemaElement](../../xmlschemaelement/)、[XmlSchemaAttribute](../../xmlschemaattribute/) 或 [XmlSchemaType](../../xmlschematype/) 对象。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlSchemaValidator](../)
* 类 [XmlSchemaObject](../../xmlschemaobject/)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)