---
title: Add()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يضيف ملف تعريف الارتباط إلى المجموعة.
type: docs
weight: 105
url: /ar/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) طريقة

يضيف ملف تعريف الارتباط إلى المجموعة.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | ملف تعريف الارتباط المراد إضافته. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) طريقة

يضيف ملف تعريف الارتباط إلى المجموعة.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | ملف تعريف الارتباط المراد إضافته. |
| throwOnError | **bool** | قيمة تشير إلى ما إذا كان سيتم رمي استثناء عند حدوث خطأ. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) طريقة

ينسخ ملفات تعريف الارتباط من المجموعة المحددة إلى الحالية.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | المجموعة التي سيتم نسخ ملفات تعريف الارتباط منها. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) طريقة

يضيف ملف تعريف الارتباط للـ URI المحدد.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | عنوان URI الخاص بملف تعريف الارتباط. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | ملف تعريف الارتباط المراد إضافته. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) طريقة

ينسخ ملفات تعريف الارتباط من المجموعة المحددة للـ URI المحدد إلى المجموعة الحالية.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | عنوان URI الخاص بملف تعريف الارتباط. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | مجموعة ملفات تعريف الارتباط التي يجب نسخ ملفات تعريف الارتباط منها. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieContainer](../)
* Class [CookieCollection](../../cookiecollection/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)