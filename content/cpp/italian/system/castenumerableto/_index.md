---
title: CastEnumerableTo()
second_title: Riferimento API Aspose.Slides per C++
description: Esegue il cast esplicito degli elementi dell'oggetto enumerabile specificato a un tipo diverso.
type: docs
weight: 2965
url: /it/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) funzione

Esegue il cast esplicito degli elementi dell'oggetto enumerabile specificato a un tipo diverso.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| To | Il tipo a cui effettuare il cast statico degli elementi dell'oggetto enumerabile |
| From | Il tipo dell'oggetto enumerabile |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| enumerable | const From\& | Oggetto enumerabile contenente gli elementi da castare |

### Valore di ritorno

Un puntatore a una nuova collezione contenente elementi di tipo **To** equivalenti agli elementi di **enumerable**


## System::CastEnumerableTo(const From\&) funzione

Esegue il cast esplicito degli elementi dell'oggetto enumerabile specificato a un tipo diverso.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| To | Il tipo a cui effettuare il cast statico degli elementi dell'oggetto enumerabile |
| From | Il tipo dell'oggetto enumerabile |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| enumerable | const From\& | è erede di un oggetto Enumerable con metodo get_Count definito e contenente gli elementi da castare |

### Valore di ritorno

Un puntatore a una nuova collezione contenente elementi di tipo **To** equivalenti agli elementi di **enumerable**


## Vedi anche

* Classe [ListPtr](../../system.collections.generic/listptr/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)