---
title: RemoveParam()
second_title: Aspose.Slides for C++ API 参考
description: 从 XsltArgumentList 中移除参数。
type: docs
weight: 66
url: /zh/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) 方法

从 [XsltArgumentList](../) 中移除参数。

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 要移除的参数的名称。[XsltArgumentList](../) 不会检查传入的名称是否为有效的本地名称；但是，该名称不能为 **nullptr**。 |
| namespaceUri | const [String](../../../system/string/)\& | 要移除的参数的命名空间 URI。 |

### 返回值

参数对象，如果未找到则为 **nullptr**。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [String](../../../system/string/)
* 类 [XsltArgumentList](../)
* 命名空间 [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)