---
title: HttpHeaderValueCollection()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 40
url: /pt/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) construtor


Constrói uma nova instância.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | O nome do cabeçalho. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | A coleção dos cabeçalhos HTTP. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) construtor


Constrói uma nova instância.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | O nome do cabeçalho. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | A coleção dos cabeçalhos HTTP. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | O delegate que é usado para validar os itens adicionados. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) construtor


Constrói uma nova instância.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | O nome do cabeçalho. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | A coleção dos cabeçalhos HTTP. |
| specialValue | T | Um \"valor especial\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) construtor


Constrói uma nova instância.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | O nome do cabeçalho. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | A coleção dos cabeçalhos HTTP. |
| specialValue | T | Um \"valor especial\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | O delegate que é usado para validar os itens adicionados. |

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Classe [String](../../../system/string/)
* Classe [HttpHeaders](../../httpheaders/)
* Classe [HttpHeaderValueCollection](../)
* Espaço de nomes [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)