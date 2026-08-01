---
title: disconnect()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert de opgegeven delegate uit de delegatieverzameling.
type: docs
weight: 170
url: /nl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) methode


Verwijdert de opgegeven delegate uit de delegatieverzameling.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | De delegate die uit de verzameling moet worden verwijderd |

### Retourwaarde

Een referentie naar zichzelf

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) methode


Verwijdert de opgegeven niet-statische methode van het opgegeven object uit de delegatieverzameling.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| MemberType | Het type van de niet-statische methode die uit de delegatieverzameling moet worden verwijderd |
| ClassType | Het type van de objectmethode waarvan moet worden verwijderd uit de delegatieverzameling |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Een pointer naar de niet-statische methode van het opgegeven object |
| obj | ClassType * | Een pointer naar een objectlidmethode waarvan moet worden verwijderd uit de delegatieverzameling |

### Retourwaarde

Een referentie naar zichzelf

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) methode


Verwijdert de opgegeven niet-statische methode van het opgegeven object uit de delegatieverzameling.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| MemberType | Het type van de niet-statische methode die uit de delegatieverzameling moet worden verwijderd |
| ClassType | Het type van de objectmethode waarvan moet worden verwijderd uit de delegatieverzameling |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Een pointer naar de niet-statische methode van het opgegeven object |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Een gedeelde pointer naar een objectlidmethode waarvan moet worden verwijderd uit de delegatieverzameling |

### Retourwaarde

Een referentie naar zichzelf

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) methode


Verwijdert het opgegeven MulticastDelegate-object uit de delegatieverzameling.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Een instantie van de MulticastDelegate-klasse die uit de delegatieverzameling moet worden verwijderd |

### Retourwaarde

Een referentie naar zichzelf

## Zie ook

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)