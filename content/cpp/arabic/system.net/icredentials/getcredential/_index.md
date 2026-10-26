---
title: GetCredential()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يرجع بيانات الاعتماد للـ URI المحدد ونوع المصادقة.
type: docs
weight: 1
url: /ar/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) طريقة

يرجع بيانات الاعتماد للـ URI المحدد ونوع المصادقة.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | الـ URI الذي يتم توفير نوع المصادقة له من قبل العميل. |
| authType | [String](../../../system/string/) | نوع المصادقة. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [NetworkCredential](../../networkcredential/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [ICredentials](../)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)