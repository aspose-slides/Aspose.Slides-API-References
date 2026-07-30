---
title: HttpHeaderValueCollection()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 40
url: /it/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Il nome dell'intestazione. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La collezione delle intestazioni HTTP. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Il nome dell'intestazione. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La collezione delle intestazioni HTTP. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Il delegato usato per convalidare gli elementi aggiunti. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) costruttore


Crea una nuova istanza.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Il nome dell'intestazione. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La collezione delle intestazioni HTTP. |
| specialValue | T | Un \"valore speciale\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Il nome dell'intestazione. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La collezione delle intestazioni HTTP. |
| specialValue | T | Un \"valore speciale\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Il delegato usato per convalidare gli elementi aggiunti. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Classe [String](../../../system/string/)
* Classe [HttpHeaders](../../httpheaders/)
* Classe [HttpHeaderValueCollection](../)
* Spazio dei nomi [System::Net::Http::Headers](../../)
* Libreria [Aspose.Slides](../../../)