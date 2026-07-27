---
title: HttpHeaderValueCollection()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia.
type: docs
weight: 40
url: /es/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) constructor

Construye una nueva instancia.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | El nombre del encabezado. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La colección de los encabezados HTTP. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor

Construye una nueva instancia.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | El nombre del encabezado. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La colección de los encabezados HTTP. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | El delegado que se utiliza para validar los elementos añadidos. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) constructor

Construye una nueva instancia.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | El nombre del encabezado. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La colección de los encabezados HTTP. |
| specialValue | T | Un \"valor especial\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor

Construye una nueva instancia.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | El nombre del encabezado. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La colección de los encabezados HTTP. |
| specialValue | T | Un \"valor especial\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | El delegado que se utiliza para validar los elementos añadidos. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [String](../../../system/string/)
* Class [HttpHeaders](../../httpheaders/)
* Class [HttpHeaderValueCollection](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)