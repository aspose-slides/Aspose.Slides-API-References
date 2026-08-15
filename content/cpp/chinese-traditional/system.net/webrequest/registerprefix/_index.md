---
title: RegisterPrefix()
second_title: Aspose.Slides C++ API 參考
description: 為指定的 URI 註冊 WebRequest 子類別。
type: docs
weight: 92
url: /zh-hant/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) 方法


Registers the [WebRequest](../) descendant for the specified URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI 或 URI 前綴。 |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | 建立 [WebRequest](../) 類別的新實例。 |

### Return Value

True 當 [WebRequest](../) 子類別成功註冊於指定的 URI 時，否則 false。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [IWebRequestCreate](../../iwebrequestcreate/)
* 類別 [WebRequest](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)