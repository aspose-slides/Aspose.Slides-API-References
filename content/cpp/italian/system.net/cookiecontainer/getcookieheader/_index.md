---
title: GetCookieHeader()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un'intestazione HTTP che contiene i cookie associati all'URI specificato.
type: docs
weight: 170
url: /it/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) metodo

Restituisce un'intestazione HTTP che contiene i cookie associati all'URI specificato.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Un URI per il quale verrà costruito il nome dell'intestazione. |

### Valore di ritorno

Un'intestazione HTTP che contiene i cookie associati all'URI specificato.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) metodo

Restituisce un'intestazione HTTP che contiene i cookie associati all'URI specificato.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Un URI per il quale verrà costruito il nome dell'intestazione. |
| optCookie2 | [String](../../../system/string/)\& | Il parametro di output dove verrà assegnato un cookie con la versione massima supportata. |

### Valore di ritorno

Un'intestazione HTTP che contiene i cookie associati all'URI specificato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Uri](../../../system/uri/)
* Classe [CookieContainer](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)