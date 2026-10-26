---
title: GetCredential()
second_title: Aspose.Slides for C++ API 參考
description: 傳回指定 URI 和驗證類型的認證。
type: docs
weight: 1
url: /zh-hant/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) 方法

傳回指定 URI 和驗證類型的認證。

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 客戶端提供驗證類型之 URI。 |
| authType | [String](../../../system/string/) | 驗證類型。 |

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [NetworkCredential](../../networkcredential/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [ICredentials](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)