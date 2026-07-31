---
title: HttpHeaderValueCollection()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance baru.
type: docs
weight: 40
url: /id/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) konstruktor


Membuat instance baru.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Nama header. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Koleksi header HTTP. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor


Membuat instance baru.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Nama header. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Koleksi header HTTP. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Delegasi yang digunakan untuk memvalidasi item yang ditambahkan. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) konstruktor


Membuat instance baru.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Nama header. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Koleksi header HTTP. |
| specialValue | T | "nilai khusus". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor


Membuat instance baru.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Nama header. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Koleksi header HTTP. |
| specialValue | T | "nilai khusus". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Delegasi yang digunakan untuk memvalidasi item yang ditambahkan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Kelas [String](../../../system/string/)
* Kelas [HttpHeaders](../../httpheaders/)
* Kelas [HttpHeaderValueCollection](../)
* Ruang Nama [System::Net::Http::Headers](../../)
* Perpustakaan [Aspose.Slides](../../../)