---
title: MulticastDelegate()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una collezione vuota.
type: docs
weight: 1
url: /it/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() method

Crea una collezione vuota.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) method

Equivalente al costruttore predefinito.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) method

Esegue una copia superficiale della collezione di delegate.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | const MulticastDelegate\& | Un'istanza della classe MulticastDelegate da cui copiare la collezione di delegate. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) method

Costruttore di spostamento.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | MulticastDelegate\&& | Un'istanza della classe MulticastDelegate da cui spostare la collezione di delegate. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) method

Crea un'istanza e aggiunge il delegate specificato alla collezione di delegate.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Un delegate da aggiungere alla collezione di delegate |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) method

Crea un'istanza e aggiunge il valore specificato alla collezione di delegate.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del valore da aggiungere alla collezione di delegate della nuova istanza creata; il tipo deve essere convertibile al tipo Callback. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg | T | Un valore da aggiungere alla collezione di delegate |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) method

Crea un'istanza e aggiunge il valore specificato alla collezione di delegate.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Un valore da aggiungere alla collezione di delegate |

## Vedi anche

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)