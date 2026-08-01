---
title: connect()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt de opgegeven delegate toe aan de collectie.
type: docs
weight: 144
url: /nl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) methode

Voegt de opgegeven delegate toe aan de collectie.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [Callback](../callback/) | De delegate die aan de collectie moet worden toegevoegd |

### Retourwaarde

Een referentie naar zichzelf

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args…)>) methode

Voegt het opgegeven functie-object toe aan de delegate-collectie. Het functie-object wordt geconverteerd naar het Callback-delegatetype voordat het aan de collectie wordt toegevoegd.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| R | Het retourtype van het functie-object dat aan de collectie moet worden toegevoegd |
| Args | De argumentenlijst van het functie-object dat aan de collectie moet worden toegevoegd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| f | std::function\<R(Args…)> | Het functie-object dat aan de collectie moet worden toegevoegd |

### Retourwaarde

Een referentie naar zichzelf

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) methode

Voegt het opgegeven MulticastDelegate-object toe aan de delegate-collectie.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Een instantie van de MulticastDelegate-klasse die aan de delegate-collectie moet worden toegevoegd |

### Retourwaarde

Een referentie naar zichzelf

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) methode

Voegt de opgegeven niet-statische methode van het opgegeven object toe aan de delegate-collectie.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| MemberType | Het type van de niet-statische methode die aan de delegate-collectie moet worden toegevoegd |
| ClassType | Het type van het object waarvan de methode aan de delegate moet worden toegevoegd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| member | MemberType ClassType::* | Een pointer naar de niet-statische methode van het opgegeven object |
| obj | ClassType * | Een pointer naar een objectmethode die aan de delegate-collectie moet worden toegevoegd |

### Retourwaarde

Een referentie naar zichzelf

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) methode

Voegt de opgegeven niet-statische methode van het opgegeven object toe aan de delegate-collectie.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| MemberType | Het type van de niet-statische methode die aan de delegate-collectie moet worden toegevoegd |
| ClassType | Het type van het object waarvan de methode aan de delegate-collectie moet worden toegevoegd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| member | MemberType ClassType::* | Een pointer naar de niet-statische methode van het opgegeven object |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Een gedeelde pointer naar een objectmethode die aan de delegate-collectie moet worden toegevoegd |

### Retourwaarde

Een referentie naar zichzelf

## Zie ook

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)