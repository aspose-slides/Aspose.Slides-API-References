---
title: GetCredential()
second_title: مرجع API Aspose.Slides برای C++
description: اعتبارها را برای URI و نوع احراز هویت مشخص شده برمی‌گرداند.
type: docs
weight: 92
url: /fa/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) متد

اعتبارها را برای URI و نوع احراز هویت مشخص شده برمی‌گرداند.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| authenticationType | [String](../../../system/string/) | نوع احراز هویت. |

## NetworkCredential::GetCredential(String, int32_t, String) متد

اعتبارها را برای نام‌سرور، پورت و نوع احراز هویت مشخص شده برمی‌گرداند.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | [String](../../../system/string/) | نام سرور. |
| port | **int32_t** | شماره پورت. |
| authenticationType | [String](../../../system/string/) | نوع احراز هویت. |

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)