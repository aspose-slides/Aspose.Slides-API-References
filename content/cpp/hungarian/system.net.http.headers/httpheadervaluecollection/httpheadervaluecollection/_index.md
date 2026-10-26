---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides C++ API referencia
description: Új példányt hoz létre.
type: docs
weight: 40
url: /hu/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | A fejléc neve. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Az HTTP-fejlécek gyűjteménye. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | A fejléc neve. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Az HTTP-fejlécek gyűjteménye. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Az a delegált, amely a hozzáadott elemek ellenőrzésére szolgál. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | A fejléc neve. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Az HTTP-fejlécek gyűjteménye. |
| specialValue | T | Egy "speciális érték". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | A fejléc neve. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Az HTTP-fejlécek gyűjteménye. |
| specialValue | T | Egy "speciális érték". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Az a delegált, amely a hozzáadott elemek ellenőrzésére szolgál. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [String](../../../system/string/)
* Class [HttpHeaders](../../httpheaders/)
* Class [HttpHeaderValueCollection](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)