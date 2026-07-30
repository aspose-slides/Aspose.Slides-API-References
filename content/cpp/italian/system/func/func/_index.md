---
title: Func()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore predefinito che crea null-Func.
type: docs
weight: 1
url: /it/system/func/func/
---
## Func::Func() costruttore

Costruttore predefinito che crea null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) costruttore

Costruttore che crea l'oggetto [Func](../) e assegna ad esso un valore (sia callback reale che nullptr).

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo dell'argomento. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg | T\&& | Argomento. |

## Func::Func(const Func\&) costruttore

Costruttore di copia.

```cpp
System::Func<Args>::Func(const Func &func)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) da cui copiare i dati. |

## Func::Func(Func\&&) costruttore

Costruttore di spostamento.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) da cui spostare i dati. |

## Vedi anche

* Classe [Func](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)