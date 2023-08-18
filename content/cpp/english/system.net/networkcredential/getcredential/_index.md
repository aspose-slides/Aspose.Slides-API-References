---
title: GetCredential()
second_title: Aspose.Slides for C++ API Reference
description: Returns credentials for the specified URI and authentication type.
type: docs
weight: 92
url: /system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) method


Returns credentials for the specified URI and authentication type.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI. |
| authenticationType | [String](../../../system/string/) | The authentication type. |

## NetworkCredential::GetCredential(String, int32_t, String) method


Returns credentials for the specified host name, port, and authentication type.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | The host name. |
| port | **int32_t** | The port number. |
| authenticationType | [String](../../../system/string/) | The authentication type. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)