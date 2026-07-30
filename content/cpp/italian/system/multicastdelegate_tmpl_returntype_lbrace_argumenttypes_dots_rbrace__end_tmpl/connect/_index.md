---
title: connect()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge il delegato specificato alla raccolta.
type: docs
weight: 144
url: /it/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) metodo

Aggiunge il delegato specificato alla raccolta.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [Callback](../callback/) | Il delegato da aggiungere alla raccolta |

### Valore di ritorno

Un riferimento a se stesso

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) metodo

Aggiunge l'oggetto funzione specificato alla raccolta di delegati. L'oggetto funzione viene convertito al tipo di delegato Callback prima di essere aggiunto alla raccolta.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| R | Il tipo di ritorno dell'oggetto funzione da aggiungere alla raccolta |
| Args | L'elenco degli argomenti dell'oggetto funzione da aggiungere alla raccolta |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| f | std::function\<R(Args...)> | L'oggetto funzione da aggiungere alla raccolta |

### Valore di ritorno

Un riferimento a se stesso

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) metodo

Aggiunge l'oggetto MulticastDelegate specificato alla raccolta di delegati.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Un'istanza della classe MulticastDelegate da aggiungere alla raccolta di delegati |

### Valore di ritorno

Un riferimento a se stesso

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) metodo

Aggiunge il metodo non statico specificato dell'oggetto specificato alla raccolta di delegati.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| MemberType | Il tipo del metodo non statico da aggiungere alla raccolta di delegati |
| ClassType | Il tipo dell'oggetto il cui metodo deve essere aggiunto alla raccolta di delegati |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntatore al metodo non statico dell'oggetto specificato |
| obj | ClassType * | Un puntatore a un oggetto il cui metodo membro deve essere aggiunto alla raccolta di delegati |

### Valore di ritorno

Un riferimento a se stesso

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metodo

Aggiunge il metodo non statico specificato dell'oggetto specificato alla raccolta di delegati.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| MemberType | Il tipo del metodo non statico da aggiungere alla raccolta di delegati |
| ClassType | Il tipo dell'oggetto il cui metodo deve essere aggiunto alla raccolta di delegati |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntatore al metodo non statico dell'oggetto specificato |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Un puntatore condiviso a un oggetto il cui metodo membro deve essere aggiunto alla raccolta di delegati |

### Valore di ritorno

Un riferimento a se stesso

## Vedi anche

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Metodo [MulticastDelegate](../multicastdelegate/)
* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)