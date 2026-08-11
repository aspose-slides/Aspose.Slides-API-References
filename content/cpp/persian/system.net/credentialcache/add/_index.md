---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: مجوزهای شبکهٔ مشخص‌شده را به کش اضافه می‌کند.
type: docs
weight: 40
url: /fa/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) متد

مجوزهای شبکهٔ تعیین‌شده را به کش اضافه می‌کند.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | پیشوند URI منبعی که اعتبارها با آن مرتبط هستند. |
| authenticationType | [String](../../../system/string/) | طرح احراز هویت. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | اعتبارهایی که باید اضافه شوند. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) متد

مجوزهای شبکهٔ تعیین‌شده را به کش اضافه می‌کند.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | [String](../../../system/string/) | نام میزبان که اعتبارها با آن مرتبط هستند. |
| port | **int32_t** | شمارهٔ پورت. |
| authenticationType | [String](../../../system/string/) | طرح احراز هویت. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | اعتبارهایی که باید اضافه شوند. |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [NetworkCredential](../../networkcredential/)
* کلاس [CredentialCache](../)
* فضای نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)