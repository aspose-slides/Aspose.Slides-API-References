---
title: GetCredential()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعيد بيانات الاعتماد للـ URI المحدد ونوع المصادقة.
type: docs
weight: 92
url: /ar/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) طريقة

يعيد بيانات الاعتماد للـ URI المحدد ونوع المصادقة.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | الـ URI. |
| authenticationType | [String](../../../system/string/) | نوع المصادقة. |

## NetworkCredential::GetCredential(String, int32_t, String) طريقة

يعيد بيانات الاعتماد لاسم المضيف المحدد، المنفذ، ونوع المصادقة.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| host | [String](../../../system/string/) | اسم المضيف. |
| port | **int32_t** | رقم المنفذ. |
| authenticationType | [String](../../../system/string/) | نوع المصادقة. |

## راجع أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)