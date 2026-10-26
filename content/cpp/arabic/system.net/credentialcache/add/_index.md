---
title: Add()
second_title: مرجع API Aspose.Slides for C++
description: يضيف بيانات الاعتماد الشبكية المحددة إلى الذاكرة المؤقتة.
type: docs
weight: 40
url: /ar/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) طريقة

يضيف بيانات الاعتماد الشبكية المحددة إلى الذاكرة المؤقتة.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | بادئة URI للموارد التي ترتبط ببيانات الاعتماد. |
| authenticationType | [String](../../../system/string/) | آلية المصادقة. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | بيانات الاعتماد المراد إضافتها. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) طريقة

يضيف بيانات الاعتماد الشبكية المحددة إلى الذاكرة المؤقتة.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | اسم المضيف المرتبط ببيانات الاعتماد. |
| port | **int32_t** | رقم المنفذ. |
| authenticationType | [String](../../../system/string/) | آلية المصادقة. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | بيانات الاعتماد المراد إضافتها. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [NetworkCredential](../../networkcredential/)
* فئة [CredentialCache](../)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)