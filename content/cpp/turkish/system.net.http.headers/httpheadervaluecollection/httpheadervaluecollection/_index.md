---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir örnek oluşturur.
type: docs
weight: 40
url: /tr/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) yapıcı


Yeni bir örnek oluşturur.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Üstbilgi adı. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP üstbilgilerinin koleksiyonu. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) yapıcı


Yeni bir örnek oluşturur.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Üstbilgi adı. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP üstbilgilerinin koleksiyonu. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Eklenen öğeleri doğrulamak için kullanılan temsilci. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) yapıcı


Yeni bir örnek oluşturur.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Üstbilgi adı. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP üstbilgilerinin koleksiyonu. |
| specialValue | T | Bir \"özel değer\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) yapıcı


Yeni bir örnek oluşturur.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Üstbilgi adı. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP üstbilgilerinin koleksiyonu. |
| specialValue | T | Bir \"özel değer\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Eklenen öğeleri doğrulamak için kullanılan temsilci. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Sınıf [String](../../../system/string/)
* Sınıf [HttpHeaders](../../httpheaders/)
* Sınıf [HttpHeaderValueCollection](../)
* İsim Alanı [System::Net::Http::Headers](../../)
* Kütüphane [Aspose.Slides](../../../)