---
title: FindHeader()
second_title: Aspose.Slides for C++ API 參考
description: 依照指定的標頭類型尋找標頭對應。
type: docs
weight: 352
url: /zh-hant/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) method


依照指定的標頭類型尋找標頭對應。

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | 標頭對應的集合。 |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | 要查找的標頭類型。 |

### 返回值

標頭對應。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [SoapMessage](../)
* 命名空間 [System::Web::Services::Protocols](../../)
* 函式庫 [Aspose.Slides](../../../)