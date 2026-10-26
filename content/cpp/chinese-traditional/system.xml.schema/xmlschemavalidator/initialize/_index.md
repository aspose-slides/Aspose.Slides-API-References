---
title: Initialize()
second_title: Aspose.Slides for C++ API 參考
description: 初始化 XmlSchemaValidator 物件的狀態。
type: docs
weight: 118
url: /zh-hant/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() 方法

初始化 [XmlSchemaValidator](../) 物件的狀態。

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```

## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) 方法

初始化 [XmlSchemaValidator](../) 物件的狀態，使用為部分驗證指定的 [XmlSchemaObject](../../xmlschemaobject/)。

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | 用於初始化 [XmlSchemaValidator](../) 物件的驗證上下文以進行部分驗證的 [XmlSchemaElement](../../xmlschemaelement/)、[XmlSchemaAttribute](../../xmlschemaattribute/) 或 [XmlSchemaType](../../xmlschematype/) 物件。 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaValidator](../)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)