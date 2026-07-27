---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona um cookie à coleção.
type: docs
weight: 105
url: /pt/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) método


Adiciona um cookie à coleção.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | O cookie a ser adicionado. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) método


Adiciona um cookie à coleção.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | O cookie a ser adicionado. |
| throwOnError | **bool** | Um valor que indica se uma exceção será lançada quando ocorrer um erro. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) método


Copia cookies da coleção especificada para a atual.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | A coleção da qual os cookies serão copiados. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) método


Adiciona um cookie para o URI especificado.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Um URI do cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | O cookie a ser adicionado. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) método


Copia cookies da coleção especificada para o URI especificado para a coleção atual.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Um URI do cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Uma coleção de cookies da qual os cookies devem ser copiados. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Cookie](../../cookie/)
* Classe [CookieContainer](../)
* Classe [CookieCollection](../../cookiecollection/)
* Classe [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)