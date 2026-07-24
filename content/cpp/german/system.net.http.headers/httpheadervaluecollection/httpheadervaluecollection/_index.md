---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz.
type: docs
weight: 40
url: /de/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Der Headername. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Die Sammlung der HTTP-Header. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Der Headername. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Die Sammlung der HTTP-Header. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Der Delegat, der zum Validieren hinzugefügter Elemente verwendet wird. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Der Headername. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Die Sammlung der HTTP-Header. |
| specialValue | T | Ein \"Sonderwert\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Der Headername. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Die Sammlung der HTTP-Header. |
| specialValue | T | Ein \"Sonderwert\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Der Delegat, der zum Validieren hinzugefügter Elemente verwendet wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Klasse [String](../../../system/string/)
* Klasse [HttpHeaders](../../httpheaders/)
* Klasse [HttpHeaderValueCollection](../)
* Namensraum [System::Net::Http::Headers](../../)
* Bibliothek [Aspose.Slides](../../../)