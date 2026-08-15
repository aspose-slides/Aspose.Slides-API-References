---
title: CollectHeaders()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定 SOAP 標頭的內部集合。
type: docs
weight: 326
url: /zh-hant/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) 方法

設定 SOAP 標頭的內部集合。

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用於取得 SOAP 標頭的物件。 |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | 用於填充內部集合的標頭集合。 |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | SOAP 標頭方向。 |

## 另請參閱

* 列舉 [SoapHeaderDirection](../../soapheaderdirection/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Object](../../../system/object/)
* 類別 [SoapMessage](../)
* 命名空間 [System::Web::Services::Protocols](../../)
* 函式庫 [Aspose.Slides](../../../)