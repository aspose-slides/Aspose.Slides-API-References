---
title: CollectHeaders()
second_title: Aspose.Slides for C++ API 参考
description: 设置 SOAP 标头的内部集合。
type: docs
weight: 326
url: /zh/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) 方法


设置 SOAP 标头的内部集合。

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用于获取 SOAP 标头的对象。 |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | 用于填充内部集合的标头集合。 |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | SOAP 标头的方向。 |

## 另请参见

* 枚举 [SoapHeaderDirection](../../soapheaderdirection/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Object](../../../system/object/)
* 类 [SoapMessage](../)
* 命名空间 [System::Web::Services::Protocols](../../)
* 库 [Aspose.Slides](../../../)