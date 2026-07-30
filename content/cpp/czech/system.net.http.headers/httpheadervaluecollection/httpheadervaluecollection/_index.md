---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci.
type: docs
weight: 40
url: /cs/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Název hlavičky. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Kolekce HTTP hlaviček. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Název hlavičky. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Kolekce HTTP hlaviček. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Delegát, který se používá k ověření přidaných položek. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Název hlavičky. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Kolekce HTTP hlaviček. |
| specialValue | T | \"speciální hodnota\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Název hlavičky. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Kolekce HTTP hlaviček. |
| specialValue | T | \"speciální hodnota\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Delegát, který se používá k ověření přidaných položek. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Třída [String](../../../system/string/)
* Třída [HttpHeaders](../../httpheaders/)
* Třída [HttpHeaderValueCollection](../)
* Jmenný prostor [System::Net::Http::Headers](../../)
* Knihovna [Aspose.Slides](../../../)