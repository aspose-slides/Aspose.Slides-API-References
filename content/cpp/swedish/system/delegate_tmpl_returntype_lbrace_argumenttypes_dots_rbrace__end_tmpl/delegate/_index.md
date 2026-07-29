---
title: Delegate()
second_title: Aspose.Slides för C++ API-referens
description: Standardkonstruktor. Skapar delegatobjektet som inte pekar på någonting.
type: docs
weight: 1
url: /sv/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() metod


Standardkonstruktor. Skapar delegatobjektet som inte pekar på någonting.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) metod




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) metod


Flyttkonstruktorkopi. Tar ägandeskapet av en enhet som pekas på av den angivna delegaten.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | Delegate\&& | Delegate-objektet att flytta den pekade enheten från |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) metod


Konstruktor. Skapar ett delegatobjekt från den angivna pekaren till en fri funktion eller en statisk metod.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Den | typ av funktions- eller statisk metodpekare som accepteras av konstruktorn som argument |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| function | T | Pekare till en funktion eller en statisk metod som den nysskapade Delegate-instansen kommer att peka på |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) metod


Konstruktor. Skapar en delegat från den angivna pekaren till funktionsobjektet som genererats av std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Den | typ av funktionsobjektet som genererats av std::bind() och som accepteras av konstruktorn som argument |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| function | T | Pekare till ett "bind-uttryck" – en funktionspekare som genererats av std::bind() – som den nysskapade Delegate-instansen kommer att peka på |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) metod


Konstruktor. Skapar en delegat från det angivna funktionsobjektet.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjektet som accepteras av konstruktorn som argument |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functor_tag | int | Ett dummy-heltal; detta argument används för att lösa tvetydighet |
| functor | T\& | Ett funktionsobjekt som den nykonstruerade delegaten kommer att peka på |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) metod


Flyttkonstruktor. Skapar en delegat från det angivna funktionsobjektet.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjektet som accepteras av konstruktorn som argument |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functor_tag | long | Ett dummy-heltal; detta argument används för att lösa tvetydighet |
| functor | T\&& | Ett funktionsobjekt som den nykonstruerade delegaten kommer att peka på |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) metod


Konstruktor. Skapar en delegat som pekar på den angivna icke-statiska metoden i det angivna objektet.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| MemberType | Typen av den icke-statiska metoden som konstruktorn accepterar som argument |
| ClassType | Typen av objektet som konstruktorn accepterar som argument |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| member | MemberType ClassType::* | En pekare till den icke-statiska metod som den nysskapade delegaten kommer att peka på |
| obj | ClassType * | En pekare till ett objekt vars medlemsmetod den nysskapade delegaten kommer att peka på |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) metod


Konstruktor. Skapar en delegat som pekar på den angivna icke-statiska metoden i det angivna objektet.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| MemberType | Typen av den icke-statiska metoden som konstruktorn accepterar som argument |
| ClassType | Typen av objektet som konstruktorn accepterar som argument |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| member | MemberType MemberClass::* | En pekare till den icke-statiska metod som den nysskapade delegaten kommer att peka på |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | En delad pekare till ett objekt vars medlemsmetod den nysskapade delegaten kommer att peka på |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) metod


Skapar ett delegatobjekt som pekar på ett std::function-funktionsobjekt.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| R | Returtypen för funktionsobjektet som accepteras av konstruktorn som argument |
| Args | Argumentlistan för funktionsobjektet som accepteras av konstruktorn som argument |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Ett funktionsobjekt som den nysskapade delegatobjektet kommer att peka på |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)