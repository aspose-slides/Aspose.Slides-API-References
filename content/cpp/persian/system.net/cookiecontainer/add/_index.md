---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: یک کوکی را به مجموعه اضافه می‌کند.
type: docs
weight: 105
url: /fa/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) متد


یک کوکی را به مجموعه اضافه می‌کند.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | کوکی‌ای که باید اضافه شود. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) متد


یک کوکی را به مجموعه اضافه می‌کند.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | کوکی‌ای که باید اضافه شود. |
| throwOnError | **bool** | مقداریک نشان می‌دهد که آیا هنگام رخ دادن خطا استثنا پرتاب شود یا خیر. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) متد


کوکی‌ها را از مجموعه مشخص‌شده به مجموعه فعلی کپی می‌کند.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | مجموعه‌ای که کوکی‌ها از آن کپی می‌شوند. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) متد


یک کوکی برای URI مشخص‌شده اضافه می‌کند.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI مربوط به کوکی. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | کوکی‌ای که باید اضافه شود. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) متد


کوکی‌ها را از مجموعه مشخص‌شده برای URI مشخص‌شده به مجموعه فعلی کپی می‌کند.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI مربوط به کوکی. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | مجموعه‌ای از کوکی‌ها که باید کپی شوند. |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Cookie](../../cookie/)
* کلاس [CookieContainer](../)
* کلاس [CookieCollection](../../cookiecollection/)
* کلاس [Uri](../../../system/uri/)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)