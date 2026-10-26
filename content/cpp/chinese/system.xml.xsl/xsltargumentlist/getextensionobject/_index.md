---
title: GetExtensionObject()
second_title: Aspose.Slides C++ API 参考
description: 返回与给定命名空间关联的对象。
type: docs
weight: 27
url: /zh/system.xml.xsl/xsltargumentlist/getextensionobject/
---
## XsltArgumentList::GetExtensionObject(const String\&) 方法

返回与给定命名空间关联的对象。

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetExtensionObject(const String &namespaceUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceUri | const [String](../../../system/string/)\& | 对象的命名空间 URI。 |

### 返回值

如果未找到，则返回命名空间 URI 对象或 **nullptr**。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [String](../../../system/string/)
* 类 [XsltArgumentList](../)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)