---
title: MulticastDelegate()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een lege collectie.
type: docs
weight: 1
url: /nl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() methode

Construeert een lege collectie.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) methode

Gelijk aan de standaardconstructor.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) methode

Voert een oppervlakkige kopie uit van de delegate-collectie.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| o | const MulticastDelegate\& | Een instantie van de class MulticastDelegate om de collectie van delegates van te kopiëren. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) methode

Verplaatsende constructor.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| o | MulticastDelegate\&& | Een instantie van de class MulticastDelegate om de collectie van delegates van te verplaatsen. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) methode

Construeert een instantie en plaatst de opgegeven delegate in de delegate-collectie.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Een delegate om toe te voegen aan de delegate-collectie |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) methode

Construeert een instantie en plaatst de opgegeven waarde in de delegate-collectie.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van de waarde die in de delegate-collectie van de nieuw geconstrueerde instantie moet worden geplaatst; het type moet converteerbaar zijn naar het Callback-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg | T | Een waarde om in de delegate-collectie te plaatsen |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) methode

Construeert een instantie en plaatst de opgegeven waarde in de delegate-collectie.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Een waarde om in de delegate-collectie te plaatsen |

## Zie ook

* Typedef [Callback](../callback/)
* Klasse [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)