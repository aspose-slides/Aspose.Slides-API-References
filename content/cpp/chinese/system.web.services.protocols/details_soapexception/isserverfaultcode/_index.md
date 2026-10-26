---
title: IsServerFaultCode()
second_title: Aspose.Slides for C++ API 参考
description: 检查指定的代码是否等于 'Server' SOAP 故障代码。
type: docs
weight: 131
url: /zh/system.web.services.protocols/details_soapexception/isserverfaultcode/
---
## Details_SoapException::IsServerFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) 方法

检查指定的代码是否等于 'Server' SOAP 故障代码。

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsServerFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 要检查的 SOAP 故障代码。 |

### 返回值

当指定的代码等于 'Server' SOAP 故障代码时返回 true，否则返回 false。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* 类 [Details_SoapException](../)
* 命名空间 [System::Web::Services::Protocols](../../)
* 库 [Aspose.Slides](../../../)