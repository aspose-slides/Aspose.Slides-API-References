---
title: get_Default()
second_title: Aspose.Slides C++ API 参考
description: 返回一个带有默认设置的 XsltSettings 对象。对 XSLT document() 函数和嵌入的脚本块的支持已被禁用。
type: docs
weight: 1
url: /zh/system.xml.xsl/xsltsettings/get_default/
---
## XsltSettings::get_Default() 方法

返回一个 [XsltSettings](../) 对象，具有默认设置。对 XSLT **document()** 函数和嵌入的脚本块的支持已禁用。

```cpp
static SharedPtr<XsltSettings> System::Xml::Xsl::XsltSettings::get_Default()
```

### 返回值

一个 [XsltSettings](../) 对象，其 [XsltSettings::set_EnableDocumentFunction](../set_enabledocumentfunction/) 和 [XsltSettings::set_EnableScript](../set_enablescript/) 选项设置为 **false**。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XsltSettings](../)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)