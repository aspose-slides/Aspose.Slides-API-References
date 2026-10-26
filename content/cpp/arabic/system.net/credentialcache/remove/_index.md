---
title: Remove()
second_title: Aspose.Slides لـ C++ مرجع API
description: يزيل بيانات الاعتماد الشبكية للبادئة المحددة للـ URI ونوع المصادقة.
type: docs
weight: 53
url: /ar/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) طريقة

يزيل بيانات الاعتماد الشبكية للبادئة المحددة للـ URI ونوع المصادقة.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | بادئة URI. |
| authenticationType | [String](../../../system/string/) | نوع المصادقة. |

## CredentialCache::Remove(String, int32_t, String) طريقة

يزيل بيانات الاعتماد الشبكية لاسم المضيف المحدد والمنفذ ونوع المصادقة.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| host | [String](../../../system/string/) | اسم المضيف المرتبط به بيانات الاعتماد. |
| port | **int32_t** | رقم المنفذ. |
| authenticationType | [String](../../../system/string/) | نوع مصادقة. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [CredentialCache](../)
* مساحة الاسم [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)