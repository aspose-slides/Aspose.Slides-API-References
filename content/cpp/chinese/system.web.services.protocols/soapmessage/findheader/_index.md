---
title: FindHeader()
second_title: Aspose.Slides for C++ API 参考
description: 根据指定的标头类型查找标头映射。
type: docs
weight: 352
url: /zh/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) 方法

通过指定的标头类型查找标头映射。

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | 标头映射的集合。 |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | 要查找的标头类型。 |

### 返回值

标头映射。

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [SoapMessage](../)
* 命名空间 [System::Web::Services::Protocols](../../)
* 库 [Aspose.Slides](../../../)