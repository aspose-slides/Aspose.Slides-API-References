---
title: idx_get()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un cookie dalla collezione di cookie all'indice specificato.
type: docs
weight: 40
url: /it/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) metodo

Restituisce un cookie dalla collezione di cookie all'indice specificato.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice di un cookie che deve essere restituito. |

### Valore restituito

Un cookie all'indice specificato.

## CookieCollection::idx_get(String) metodo

Restituisce un cookie dalla collezione di cookie per nome specificato.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome di un cookie che deve essere restituito. |

### Valore restituito

Un cookie dalla collezione di cookie per nome specificato se trovato, altrimenti nullptr.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Cookie](../../cookie/)
* Classe [CookieCollection](../)
* Classe [String](../../../system/string/)
* Namespace [System::Net](../../)
* Libreria [Aspose.Slides](../../../)