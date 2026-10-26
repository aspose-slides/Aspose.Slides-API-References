---
title: MulticastDelegate()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom samling.
type: docs
weight: 1
url: /sv/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() metod


Skapar en tom samling.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) metod


Motsvarar standardkonstruktorn.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) metod


Utför en ytlig kopia av delegatsamlingen.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | const MulticastDelegate\& | En instans av MulticastDelegate-klass för att kopiera delegatsamlingen från. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) metod


Flyttkonstruktor.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | MulticastDelegate\&& | En instans av MulticastDelegate-klass för att flytta delegatsamlingen från. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) metod


Skapar en instans och lägger till den angivna delegaten i delegatsamlingen.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | En delegate att lägga till delegatsamlingen |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) metod


Skapar en instans och lägger till det angivna värdet i delegatsamlingen.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```


### Template parameters

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av värdet som ska läggas till delegatsamlingen i den nykonstruerade instansen; typen måste vara konverterbar till Callback-typen. |

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg | T | Ett värde att lägga till delegatsamlingen |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) metod


Skapar en instans och lägger till det angivna värdet i delegatsamlingen.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Ett värde att lägga till delegatsamlingen |

## Se även

* Typedef [Callback](../callback/)
* Klass [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)