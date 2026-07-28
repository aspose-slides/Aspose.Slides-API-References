---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową instancję.
type: docs
weight: 40
url: /pl/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | The header name. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | The collection of the HTTP headers. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | The header name. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | The collection of the HTTP headers. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | The delegate that is used to validate added items. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | The header name. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | The collection of the HTTP headers. |
| specialValue | T | A "special value". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | The header name. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | The collection of the HTTP headers. |
| specialValue | T | A "special value". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | The delegate that is used to validate added items. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Klasa [String](../../../system/string/)
* Klasa [HttpHeaders](../../httpheaders/)
* Klasa [HttpHeaderValueCollection](../)
* Przestrzeń nazw [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)