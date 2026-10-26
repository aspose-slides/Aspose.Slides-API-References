---
title: connect()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt den angegebenen Delegaten zur Sammlung hinzu.
type: docs
weight: 144
url: /de/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) method


Fügt den angegebenen Delegaten zur Sammlung hinzu.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [Callback](../callback/) | Der Delegat, der zur Sammlung hinzugefügt werden soll |

### Return Value

Ein Verweis auf das Objekt selbst

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) method


Fügt das angegebene Funktionsobjekt zur Delegatensammlung hinzu. Das Funktionsobjekt wird vor dem Hinzufügen in den Delegaten-Typ Callback konvertiert.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| R | Der Rückgabetyp des Funktionsobjekts, das zur Sammlung hinzugefügt werden soll |
| Args | Die Argumentliste des Funktionsobjekts, das zur Sammlung hinzugefügt werden soll |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Das Funktionsobjekt, das zur Sammlung hinzugefügt werden soll |

### Return Value

Ein Verweis auf das Objekt selbst

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) method


Fügt das angegebene MulticastDelegate-Objekt zur Delegatensammlung hinzu.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Eine Instanz der Klasse MulticastDelegate, die zur Delegatensammlung hinzugefügt werden soll |

### Return Value

Ein Verweis auf das Objekt selbst

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) method


Fügt die angegebene nicht-statische Methode des angegebenen Objekts zur Delegatensammlung hinzu.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| MemberType | Der Typ der nicht-statischen Methode, die zur Delegatensammlung hinzugefügt werden soll |
| ClassType | Der Typ des Objekts, dessen Methode zur Delegatensammlung hinzugefügt werden soll |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| member | MemberType ClassType::* | Ein Zeiger auf die nicht-statische Methode des angegebenen Objekts |
| obj | ClassType * | Ein Zeiger auf die Objektmitgliedsmethode, die zur Delegatensammlung hinzugefügt werden soll |

### Return Value

Ein Verweis auf das Objekt selbst

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Fügt die angegebene nicht-statische Methode des angegebenen Objekts zur Delegatensammlung hinzu.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| MemberType | Der Typ der nicht-statischen Methode, die zur Delegatensammlung hinzugefügt werden soll |
| ClassType | Der Typ des Objekts, dessen Methode zur Delegatensammlung hinzugefügt werden soll |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| member | MemberType ClassType::* | Ein Zeiger auf die nicht-statische Methode des angegebenen Objekts |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Ein SharedPtr auf die Objektmitgliedsmethode, die zur Delegatensammlung hinzugefügt werden soll |

### Return Value

Ein Verweis auf das Objekt selbst

## Siehe auch

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)