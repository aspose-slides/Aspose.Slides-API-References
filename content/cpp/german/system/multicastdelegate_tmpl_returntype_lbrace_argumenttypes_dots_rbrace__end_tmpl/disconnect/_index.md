---
title: disconnect()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt den angegebenen Delegaten aus der Delegatensammlung.
type: docs
weight: 170
url: /de/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) Methode


Entfernt den angegebenen Delegaten aus der Delegatensammlung.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [Callback](../callback/) | Der Delegat, der aus der Sammlung entfernt werden soll |

### Rückgabewert

Eine Referenz auf das aktuelle Objekt

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) Methode


Entfernt die angegebene nicht-statische Methode des angegebenen Objekts aus der Delegatensammlung.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| MemberType | Der Typ der nicht-statischen Methode, die aus der Delegatensammlung entfernt werden soll |
| ClassType | Der Typ des Objekts, dessen Methode aus der Delegatensammlung entfernt werden soll |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| member | MemberType ClassType::* | Ein Zeiger auf die nicht-statische Methode des angegebenen Objekts |
| obj | ClassType * | Ein Zeiger auf die Objektmethode, deren Mitglied aus der Delegatensammlung entfernt werden soll |

### Rückgabewert

Eine Referenz auf das aktuelle Objekt

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) Methode


Entfernt die angegebene nicht-statische Methode des angegebenen Objekts aus der Delegatensammlung.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| MemberType | Der Typ der nicht-statischen Methode, die aus der Delegatensammlung entfernt werden soll |
| ClassType | Der Typ des Objekts, dessen Methode aus der Delegatensammlung entfernt werden soll |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| member | MemberType ClassType::* | Ein Zeiger auf die nicht-statische Methode des angegebenen Objekts |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Ein SharedPtr auf die Objektmethode, deren Mitglied aus der Delegatensammlung entfernt werden soll |

### Rückgabewert

Eine Referenz auf das aktuelle Objekt

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) Methode


Entfernt das angegebene MulticastDelegate-Objekt aus der Delegatensammlung.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Eine Instanz der MulticastDelegate-Klasse, die aus der Delegatensammlung entfernt werden soll |

### Rückgabewert

Eine Referenz auf das aktuelle Objekt

## Siehe auch

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)