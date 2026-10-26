---
title: CreateHttp()
second_title: مرجع API Aspose.Slides للـ C++
description: ينشئ مثلاً جديداً من فئة WebRequest باستخدام URI المحدد.
type: docs
weight: 79
url: /ar/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) طريقة

ينشئ مثلاً جديداً من الفئة [WebRequest](../) باستخدام URI المحدد.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | URI الذي يُستخدم لإنشاء مثلاً جديداً من الفئة [WebRequest](../). |

### قيمة الإرجاع

مثلة من فئة WebRequest-class تم إنشاؤها حديثاً.

## ملاحظات

سيُرمى استثناء NotSupportedException عندما يبدأ URI المحدد بأي مخطط غير [http://](http://) أو [https://](https://).

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) طريقة

ينشئ مثلاً جديداً من الفئة [WebRequest](../) باستخدام URI المحدد.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI الذي يُستخدم لإنشاء مثلاً جديداً من الفئة [WebRequest](../). |

### قيمة الإرجاع

مثلة من فئة WebRequest-class تم إنشاؤها حديثاً.

## ملاحظات

سيُرمى استثناء NotSupportedException عندما يبدأ URI المحدد بأي مخطط غير [http://](http://) أو [https://](https://).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [HttpWebRequest](../../httpwebrequest/)
* فئة [String](../../../system/string/)
* فئة [WebRequest](../)
* فئة [Uri](../../../system/uri/)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)