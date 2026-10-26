---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides برای مرجع API C++
description: یک نمونه جدید ایجاد می‌کند.
type: docs
weight: 40
url: /fa/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) سازنده

یک نمونه جدید ایجاد می‌کند.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | نام هدر. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | مجموعه‌ی هدرهای HTTP. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) سازنده

یک نمونه جدید ایجاد می‌کند.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | نام هدر. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | مجموعه‌ی هدرهای HTTP. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | نماینده‌ای که برای اعتبارسنجی آیتم‌های اضافه‌شده استفاده می‌شود. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) سازنده

یک نمونه جدید ایجاد می‌کند.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | نام هدر. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | مجموعه‌ی هدرهای HTTP. |
| specialValue | T | یک «مقدار ویژه». |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) سازنده

یک نمونه جدید ایجاد می‌کند.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | نام هدر. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | مجموعه‌ی هدرهای HTTP. |
| specialValue | T | یک «مقدار ویژه». |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | نماینده‌ای که برای اعتبارسنجی آیتم‌های اضافه‌شده استفاده می‌شود. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* کلاس [String](../../../system/string/)
* کلاس [HttpHeaders](../../httpheaders/)
* کلاس [HttpHeaderValueCollection](../)
* فضای‌نام [System::Net::Http::Headers](../../)
* کتابخانه [Aspose.Slides](../../../)