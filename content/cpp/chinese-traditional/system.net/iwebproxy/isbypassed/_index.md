---
title: IsBypassed()
second_title: Aspose.Slides C++ API 參考手冊
description: 傳回一個值，用於指示是否不得為指定的主機使用代理伺服器。
type: docs
weight: 40
url: /zh-hant/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) method


傳回一個值，用於指示是否不得為指定的主機使用代理伺服器。

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 要檢查的主機 URI。 |

### Return Value

若不得使用代理伺服器則傳回 true，否則傳回 false。

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [IWebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)