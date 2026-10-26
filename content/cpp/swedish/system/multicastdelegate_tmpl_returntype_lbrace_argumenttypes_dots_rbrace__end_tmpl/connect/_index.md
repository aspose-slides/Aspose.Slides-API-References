---
title: connect()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till den angivna delegaten i samlingen.
type: docs
weight: 144
url: /sv/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) metod


Lägger till den angivna delegaten i samlingen.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [Callback](../callback/) | Delegaten att lägga till i samlingen |

### Returvärde

En referens till sig själv

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) metod


Lägger till det angivna funktionsobjektet i delegatsamlingen. Funktionsobjektet konverteras till delegattypen Callback innan det läggs till i samlingen.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| R | Returtypen för funktionsobjektet som ska läggas till i samlingen |
| Args | Argumentlistan för funktionsobjektet som ska läggas till i samlingen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Funktionsobjektet att lägga till i samlingen |

### Returvärde

En referens till sig själv

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) metod


Lägger till det angivna MulticastDelegate-objektet i delegatsamlingen.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | En instans av MulticastDelegate-klassen att lägga till i delegatsamlingen |

### Returvärde

En referens till sig själv

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) metod


Lägger till den angivna icke-statiska metoden för det angivna objektet i delegatsamlingen.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| MemberType | Typen av den icke-statiska metod som ska läggas till i delegatsamlingen |
| ClassType | Typen av objektet vars metod ska läggas till i delegaten |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| member | MemberType ClassType::* | En pekare till den icke-statiska metoden för det angivna objektet |
| obj | ClassType * | En pekare till ett medlemsmetod i ett objekt som ska läggas till i delegatsamlingen |

### Returvärde

En referens till sig själv

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metod


Lägger till den angivna icke-statiska metoden för det angivna objektet i delegatsamlingen.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| MemberType | Typen av den icke-statiska metod som ska läggas till i delegatsamlingen |
| ClassType | Typen av objektet vars metod ska läggas till i delegaten |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| member | MemberType ClassType::* | En pekare till den icke-statiska metoden för det angivna objektet |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | En delad pekare till ett medlemsmetod i ett objekt som ska läggas till i delegatsamlingen |

### Returvärde

En referens till sig själv

## Se även

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)