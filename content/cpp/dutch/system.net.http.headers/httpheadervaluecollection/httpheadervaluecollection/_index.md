---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw exemplaar aan.
type: docs
weight: 40
url: /nl/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) constructor


Maakt een nieuw exemplaar aan.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | De headernaam. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | De collectie van de HTTP-headers. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor


Maakt een nieuw exemplaar aan.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | De headernaam. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | De collectie van de HTTP-headers. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | De delegate die wordt gebruikt om toegevoegde items te valideren. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) constructor


Maakt een nieuw exemplaar aan.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | De headernaam. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | De collectie van de HTTP-headers. |
| specialValue | T | Een \"speciale waarde\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor


Maakt een nieuw exemplaar aan.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | De headernaam. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | De collectie van de HTTP-headers. |
| specialValue | T | Een \"speciale waarde\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | De delegate die wordt gebruikt om toegevoegde items te valideren. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Klasse [String](../../../system/string/)
* Klasse [HttpHeaders](../../httpheaders/)
* Klasse [HttpHeaderValueCollection](../)
* Naamruimte [System::Net::Http::Headers](../../)
* Bibliotheek [Aspose.Slides](../../../)