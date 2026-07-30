---
title: Delegate()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore predefinito. Crea l'oggetto delegate che non punta a nulla.
type: docs
weight: 1
url: /it/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() metodo

Costruttore predefinito. Crea l'oggetto delegate che non punta a nulla.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) metodo






```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) metodo

Costruttore di copia di spostamento. Assume la proprietà di un'entità puntata dal delegate specificato.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | Delegate\&& | L'oggetto Delegate da cui spostare l'entità puntata |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) metodo

Costruttore. Crea un oggetto delegate dal puntatore specificato a una funzione libera o a un metodo statico.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| The | il tipo del puntatore a funzione o a metodo statico accettato dal costruttore come argomento |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| function | T | Puntatore a una funzione o a un metodo statico a cui farà riferimento la nuova istanza di Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) metodo

Costruttore. Crea un delegate dal puntatore specificato all'oggetto funzione generato da std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| The | il tipo dell'oggetto funzione generato da std::bind() accettato dal costruttore come argomento |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| function | T | Puntatore a una "espressione bind" - un puntatore a funzione generato da std::bind() - a cui farà riferimento la nuova istanza di Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) metodo

Costruttore. Crea un delegate dall'oggetto funzione specificato.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | il tipo dell'oggetto funzione accettato dal costruttore come argomento |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functor_tag | int | Un valore intero fittizio; questo argomento è usato per risolvere l'ambiguità |
| functor | T\& | Un oggetto funzione a cui il delegate appena costruito punterà |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) metodo

Costruttore di spostamento. Crea un delegate dall'oggetto funzione specificato.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | il tipo dell'oggetto funzione accettato dal costruttore come argomento |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functor_tag | long | Un valore intero fittizio; questo argomento è usato per risolvere l'ambiguità |
| functor | T\&& | Un oggetto funzione a cui il delegate appena costruito punterà |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) metodo

Costruttore. Crea un delegate che punta al metodo non statico specificato dell'oggetto specificato.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| MemberType | il tipo del metodo non statico accettato dal costruttore come argomento |
| ClassType | il tipo dell'oggetto accettato dal costruttore come argomento |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntatore al metodo non statico a cui punterà il nuovo delegate creato |
| obj | ClassType * | Un puntatore a un oggetto il cui metodo membro sarà puntato dal nuovo delegate creato |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) metodo

Costruttore. Crea un delegate che punta al metodo non statico specificato dell'oggetto specificato.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| MemberType | il tipo del metodo non statico accettato dal costruttore come argomento |
| ClassType | il tipo dell'oggetto accettato dal costruttore come argomento |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| member | MemberType MemberClass::* | Un puntatore al metodo non statico a cui punterà il nuovo delegate creato |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Un puntatore condiviso a un oggetto il cui metodo membro sarà puntato dal nuovo delegate creato |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) metodo

Crea un oggetto delegate che punta a un oggetto funzione std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| R | il tipo di ritorno dell'oggetto funzione accettato dal costruttore come argomento |
| Args | l'elenco degli argomenti dell'oggetto funzione accettato dal costruttore come argomento |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Un oggetto funzione a cui punterà il nuovo oggetto delegate creato |

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)