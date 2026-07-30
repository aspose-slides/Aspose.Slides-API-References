---
title: Add()
second_title: Aspose.Slides per C++ Riferimento API
description: Aggiunge un cookie alla collezione.
type: docs
weight: 105
url: /it/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) metodo

Aggiunge un cookie alla collezione.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Il cookie da aggiungere. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) metodo

Aggiunge un cookie alla collezione.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Il cookie da aggiungere. |
| throwOnError | **bool** | Un valore che indica se un'eccezione verrà sollevata quando si verifica un errore. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) metodo

Copia i cookie dalla collezione specificata a quella corrente.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | La collezione da cui verranno copiati i cookie. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) metodo

Aggiunge un cookie per l'URI specificato.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Un URI del cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Il cookie da aggiungere. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) metodo

Copia i cookie dalla collezione specificata per l'URI specificato alla collezione corrente.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Un URI del cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Una collezione di cookie da cui devono essere copiati i cookie. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Cookie](../../cookie/)
* Classe [CookieContainer](../)
* Classe [CookieCollection](../../cookiecollection/)
* Classe [Uri](../../../system/uri/)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)