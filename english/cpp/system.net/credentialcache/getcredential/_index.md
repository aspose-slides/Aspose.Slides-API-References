---
title: GetCredential()
second_title: Aspose.Slides for C++ API Reference
description: Returns credentials for the specified URI prefix and authentication type.
type: docs
weight: 66
url: /cpp/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) method


Returns credentials for the specified URI prefix and authentication type.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI prefix. |
| authenticationType | [String](../../../system/string/) | An authentication type. |

## CredentialCache::GetCredential(String, int32_t, String) method


Returns credentials for the specified host name, port, and authentication type.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | The host name with which the credentials are associated. |
| port | **int32_t** | The port number. |
| authenticationType | [String](../../../system/string/) | The authentication type. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)