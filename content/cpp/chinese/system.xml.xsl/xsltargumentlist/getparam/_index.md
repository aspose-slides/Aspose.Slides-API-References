---
title: GetParam()
second_title: Aspose.Slides for C++ API 参考
description: 返回与命名空间限定名称关联的参数。
type: docs
weight: 14
url: /zh/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) 方法


返回与命名空间限定名称关联的参数。

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 参数的名称。[XsltArgumentList](../) 不检查传入的名称是否为有效的本地名称；但是，该名称不能为 **nullptr**。 |
| namespaceUri | const [String](../../../system/string/)\& | 与该参数关联的命名空间 URI。 |

### 返回值

参数对象，若未找到则为 **nullptr**。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [String](../../../system/string/)
* 类 [XsltArgumentList](../)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)