---
title: InternalAdd()
second_title: Aspose.Slides per C++ Riferimento API
description: Aggiunge il cookie specificato alla raccolta.
type: docs
weight: 118
url: /it/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) metodo

Aggiunge il cookie specificato alla raccolta.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Il cookie da aggiungere. |
| isStrict | **bool** | True quando il cookie specificato deve sostituire quello vecchio, altrimenti false. |

### Valore di ritorno

0 quando il cookie specificato ha sostituito quello vecchio, altrimenti 1.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)