---
title: GetCredential()
second_title: مرجع API Aspose.Slides برای C++
description: اعتبارها را برای پیشوند URI و نوع احراز هویت مشخص شده برمی‌گرداند.
type: docs
weight: 66
url: /fa/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) متد

اعتبارها را برای پیشوند URI و نوع احراز هویت مشخص شده برمی‌گرداند.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | پیشوند URI. |
| authenticationType | [String](../../../system/string/) | یک نوع احراز هویت. |

## CredentialCache::GetCredential(String, int32_t, String) متد

اعتبارها را برای نام میزبان، پورت و نوع احراز هویت مشخص شده برمی‌گرداند.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | [String](../../../system/string/) | نام میزبان که اعتبارها با آن مرتبط هستند. |
| port | **int32_t** | شماره پورت. |
| authenticationType | [String](../../../system/string/) | نوع احراز هویت. |

## موارد مرتبط

* نوع تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [NetworkCredential](../../networkcredential/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [CredentialCache](../)
* فضای نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)