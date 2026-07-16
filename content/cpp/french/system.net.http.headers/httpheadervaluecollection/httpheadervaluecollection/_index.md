---
title: HttpHeaderValueCollection()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 40
url: /fr/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Le nom de l’en-tête. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La collection des en-têtes HTTP. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Le nom de l’en-tête. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La collection des en-têtes HTTP. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Le délégué utilisé pour valider les éléments ajoutés. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Le nom de l’en-tête. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La collection des en-têtes HTTP. |
| specialValue | T | Une \"valeur spéciale\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructeur


Construit une nouvelle instance.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Le nom de l’en-tête. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | La collection des en-têtes HTTP. |
| specialValue | T | Une \"valeur spéciale\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Le délégué utilisé pour valider les éléments ajoutés. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Classe [String](../../../system/string/)
* Classe [HttpHeaders](../../httpheaders/)
* Classe [HttpHeaderValueCollection](../)
* Espace de noms [System::Net::Http::Headers](../../)
* Bibliothèque [Aspose.Slides](../../../)