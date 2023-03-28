---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified network credentials to the cache.
type: docs
weight: 40
url: /cpp/system.net/credentialcache/add/
---
## CredentialCache::Add([System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>, [String](../../../system/string/), [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\>) method


Adds the specified network credentials to the cache.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The resource's URI prefix with which the credentials are associated. |
| authenticationType | [String](../../../system/string/) | The authentication scheme. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | The credentials to add. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## CredentialCache::Add([String](../../../system/string/), **int32_t**, [String](../../../system/string/), [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\>) method


Adds the specified network credentials to the cache.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | The host name with which the credentials are associated. |
| port | **int32_t** | The port number. |
| authenticationType | [String](../../../system/string/) | The authentication scheme. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | The credentials to add. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
