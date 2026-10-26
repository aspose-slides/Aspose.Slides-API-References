---
title: GetCredential()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يعيد بيانات الاعتماد لبادئة URI المحددة ونوع المصادقة.
type: docs
weight: 66
url: /ar/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) method


يعيد بيانات الاعتماد للبادئة URI المحددة ونوع المصادقة.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | بادئة URI. |
| authenticationType | [String](../../../system/string/) | نوع مصادقة. |

## CredentialCache::GetCredential(String, int32_t, String) method


يعيد بيانات الاعتماد لاسم المضيف المحدد، والمنفذ، ونوع المصادقة.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | اسم المضيف المرتبط ببيانات الاعتماد. |
| port | **int32_t** | رقم المنفذ. |
| authenticationType | [String](../../../system/string/) | نوع المصادقة. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)