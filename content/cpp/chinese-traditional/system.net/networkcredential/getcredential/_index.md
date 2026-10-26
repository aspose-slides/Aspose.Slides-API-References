---
title: GetCredential()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回指定 URI 與驗證類型的認證。
type: docs
weight: 92
url: /zh-hant/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) 方法

傳回指定 URI 與驗證類型的認證。

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI。 |
| authenticationType | [String](../../../system/string/) | 驗證類型。 |

## NetworkCredential::GetCredential(String, int32_t, String) 方法

傳回指定主機名稱、埠號與驗證類型的認證。

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 主機名稱。 |
| port | **int32_t** | 埠號。 |
| authenticationType | [String](../../../system/string/) | 驗證類型。 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [NetworkCredential](../)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)