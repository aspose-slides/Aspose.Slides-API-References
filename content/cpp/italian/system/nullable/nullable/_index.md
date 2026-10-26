---
title: Nullable()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisce un'istanza che rappresenta un valore nullo.
type: docs
weight: 1
url: /it/system/nullable/nullable/
---
## Nullable::Nullable() constructor

Costruisce un'istanza che rappresenta un valore nullo.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) constructor

Costruisce un'istanza che rappresenta null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) constructor

Costruisce un'istanza della classe [Nullable](../) che rappresenta il valore specificato convertito (se necessario) al valore del tipo sottostante T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del valore specificato |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T1\& | Un riferimento costante al valore da rappresentare dal nuovo oggetto [Nullable](../) costruito |

## Nullable::Nullable(const Nullable\<T1\>\&) constructor

Costruisce un'istanza che rappresenta un valore rappresentato dall'oggetto [Nullable](../) specificato. L'oggetto nullable specificato può rappresentare un valore di tipo diverso rispetto al tipo sottostante dell'istanza costruita, nel qual caso il valore rappresentato viene convertito in un valore di tipo T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del valore rappresentato dall'oggetto [Nullable](../) specificato |

## Vedi anche

* Classe [Nullable](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)