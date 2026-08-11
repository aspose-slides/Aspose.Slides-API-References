---
title: Remove()
second_title: مرجع API Aspose.Slides برای C++
description: مجوزهای شبکه را برای پیشوند URI و نوع احراز هویت مشخص شده حذف می‌کند.
type: docs
weight: 53
url: /fa/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) متد

مجوزهای شبکه را برای پیشوند URI و نوع احراز هویت مشخص شده حذف می‌کند.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | پیشوند URI. |
| authenticationType | [String](../../../system/string/) | نوع احراز هویت. |

## CredentialCache::Remove(String, int32_t, String) متد

مجوزهای شبکه را برای نام میزبان، پورت و نوع احراز هویت مشخص شده حذف می‌کند.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | [String](../../../system/string/) | نام میزبان که مجوزها با آن مرتبط هستند. |
| port | **int32_t** | عدد پورت. |
| authenticationType | [String](../../../system/string/) | یک نوع احراز هویت. |

## همچنین ببینید

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [CredentialCache](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)