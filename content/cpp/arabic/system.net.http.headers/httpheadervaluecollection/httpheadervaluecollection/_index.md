---
title: HttpHeaderValueCollection()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ نسخة جديدة.
type: docs
weight: 40
url: /ar/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) المنشئ

ينشئ نسخة جديدة.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | اسم الترويسة. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | مجموعة رؤوس HTTP. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) المنشئ

ينشئ نسخة جديدة.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | اسم الترويسة. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | مجموعة رؤوس HTTP. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | المندوب المستخدم للتحقق من صحة العناصر المُضافة. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) المنشئ

ينشئ نسخة جديدة.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | اسم الترويسة. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | مجموعة رؤوس HTTP. |
| specialValue | T | قيمة \"خاصة\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) المنشئ

ينشئ نسخة جديدة.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | اسم الترويسة. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | مجموعة رؤوس HTTP. |
| specialValue | T | قيمة \"خاصة\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | المندوب المستخدم للتحقق من صحة العناصر المُضافة. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* الصنف [String](../../../system/string/)
* الصنف [HttpHeaders](../../httpheaders/)
* الصنف [HttpHeaderValueCollection](../)
* النطاق [System::Net::Http::Headers](../../)
* المكتبة [Aspose.Slides](../../../)