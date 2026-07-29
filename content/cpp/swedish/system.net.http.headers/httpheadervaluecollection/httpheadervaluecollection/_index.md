---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 40
url: /sv/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Headernamnet. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Samlingen av HTTP-rubrikerna. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Headernamnet. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Samlingen av HTTP-rubrikerna. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Delegaten som används för att validera tillagda objekt. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) konstruktor


Skapar en ny instans.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Headernamnet. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Samlingen av HTTP-rubrikerna. |
| specialValue | T | Ett \"specialvärde\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Headernamnet. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Samlingen av HTTP-rubrikerna. |
| specialValue | T | Ett \"specialvärde\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Delegaten som används för att validera tillagda objekt. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Klass [String](../../../system/string/)
* Klass [HttpHeaders](../../httpheaders/)
* Klass [HttpHeaderValueCollection](../)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)