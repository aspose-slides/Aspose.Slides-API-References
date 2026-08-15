---
title: GetCredential()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回指定主機和驗證類型的憑證。
type: docs
weight: 1
url: /zh-hant/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) 方法


返回指定主機和驗證類型的憑證。

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 驗證客戶端的主機。 |
| port | **int32_t** | 主機埠號。 |
| authenticationType | [String](../../../system/string/) | 驗證類型。 |

## 參見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [NetworkCredential](../../networkcredential/)
* 類別 [String](../../../system/string/)
* 類別 [ICredentialsByHost](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)