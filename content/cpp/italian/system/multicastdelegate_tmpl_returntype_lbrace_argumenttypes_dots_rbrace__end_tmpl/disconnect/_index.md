---
title: disconnect()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove il delegato specificato dalla raccolta di delegati.
type: docs
weight: 170
url: /it/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) metodo

Rimuove il delegato specificato dalla raccolta di delegati.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [Callback](../callback/) | Il delegato da rimuovere dalla raccolta |

### Valore di ritorno

Un riferimento all'oggetto stesso

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) metodo

Rimuove il metodo non statico specificato dell'oggetto specificato dalla raccolta di delegati.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| MemberType | Il tipo del metodo non statico che deve essere rimosso dalla raccolta di delegati |
| ClassType | Il tipo dell'oggetto il cui metodo deve essere rimosso dalla raccolta di delegati |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntatore al metodo non statico dell'oggetto specificato |
| obj | ClassType * | Un puntatore a un oggetto il cui metodo membro deve essere rimosso dalla raccolta di delegati |

### Valore di ritorno

Un riferimento all'oggetto stesso

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metodo

Rimuove il metodo non statico specificato dell'oggetto specificato dalla raccolta di delegati.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| MemberType | Il tipo del metodo non statico che deve essere rimosso dalla raccolta di delegati |
| ClassType | Il tipo dell'oggetto il cui metodo deve essere rimosso dalla raccolta di delegati |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| member | MemberType ClassType::* | Un puntatore al metodo non statico dell'oggetto specificato |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Un puntatore condiviso a un metodo membro dell'oggetto il cui metodo deve essere rimosso dalla raccolta di delegati |

### Valore di ritorno

Un riferimento all'oggetto stesso

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) metodo

Rimuove l'oggetto MulticastDelegate specificato dalla raccolta di delegati.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Un'istanza della classe MulticastDelegate da rimuovere dalla raccolta di delegati |

### Valore di ritorno

Un riferimento all'oggetto stesso

## Vedi anche

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Metodo [MulticastDelegate](../multicastdelegate/)
* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)