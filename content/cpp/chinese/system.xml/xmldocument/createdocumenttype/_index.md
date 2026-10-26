---
title: CreateDocumentType()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个新的 XmlDocumentType 对象。
type: docs
weight: 313
url: /zh/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) 方法


返回一个新的 [XmlDocumentType](../../xmldocumenttype/) 对象。

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 文档类型的名称。 |
| publicId | const [String](../../../system/string/)\& | 文档类型的公共标识符或 **nullptr**。您可以指定公共 URI 以及系统标识符来标识外部 DTD 子集的位置。 |
| systemId | const [String](../../../system/string/)\& | 文档类型的系统标识符或 **nullptr**。指定外部 DTD 子集的文件位置的 URL。 |
| internalSubset | const [String](../../../system/string/)\& | 文档类型的 DTD 内部子集或 **nullptr**。 |

### 返回值

新的 [XmlDocumentType](../../xmldocumenttype/)。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlDocumentType](../../xmldocumenttype/)
* 类 [String](../../../system/string/)
* 类 [XmlDocument](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)