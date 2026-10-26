---
title: disconnect()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den angivna delegaten från delegatsamlingen.
type: docs
weight: 170
url: /sv/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) metod

Tar bort den angivna delegaten från delegatsamlingen.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [Callback](../callback/) | Delegaten som ska tas bort från samlingen |

### Returvärde

En referens till sig själv

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) metod

Tar bort den angivna icke-statiska metoden för det angivna objektet från delegatsamlingen.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| MemberType | Typen av den icke-statiska metod som ska tas bort från delegatsamlingen |
| ClassType | Typen av objektet vars metod ska tas bort från delegatsamlingen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| member | MemberType ClassType::* | En pekare till den icke-statiska metoden för det angivna objektet |
| obj | ClassType * | En pekare till ett objekt vars medlemsmetod ska tas bort från delegatsamlingen |

### Returvärde

En referens till sig själv

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metod

Tar bort den angivna icke-statiska metoden för det angivna objektet från delegatsamlingen.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| MemberType | Typen av den icke-statiska metod som ska tas bort från delegatsamlingen |
| ClassType | Typen av objektet vars metod ska tas bort från delegatsamlingen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| member | MemberType ClassType::* | En pekare till den icke-statiska metoden för det angivna objektet |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | En delad pekare till ett objekt vars medlemsmetod ska tas bort från delegatsamlingen |

### Returvärde

En referens till sig själv

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) metod

Tar bort det angivna MulticastDelegate-objektet från delegatsamlingen.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | En instans av MulticastDelegate-klassen som ska tas bort från delegatsamlingen |

### Returvärde

En referens till sig själv

## Se även

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Metod [MulticastDelegate](../multicastdelegate/)
* Klass [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)