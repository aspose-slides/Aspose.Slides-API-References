---
title: disconnect()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odstraní zadaný delegát ze sbírky delegátů.
type: docs
weight: 170
url: /cs/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) metoda


Odstraní zadaný delegát ze sbírky delegátů.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [Callback](../callback/) | Delegát, který má být odstraněn ze sbírky |

### Návratová hodnota

Odkaz na sebe

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) metoda


Odstraní zadanou nestatickou metodu specifikovaného objektu ze sbírky delegátů.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| MemberType | Typ nestatické metody, která má být odstraněna ze sbírky delegátů |
| ClassType | Typ objektu, jehož metoda má být odstraněna ze sbírky delegátů |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| member | MemberType ClassType::* | Ukazatel na nestatickou metodu specifikovaného objektu |
| obj | ClassType * | Ukazatel na metodu členu objektu, která má být odstraněna ze sbírky delegátů |

### Návratová hodnota

Odkaz na sebe

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metoda


Odstraní zadanou nestatickou metodu specifikovaného objektu ze sbírky delegátů.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| MemberType | Typ nestatické metody, která má být odstraněna ze sbírky delegátů |
| ClassType | Typ objektu, jehož metoda má být odstraněna ze sbírky delegátů |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| member | MemberType ClassType::* | Ukazatel na nestatickou metodu specifikovaného objektu |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Sdílený ukazatel na metodu členu objektu, která má být odstraněna ze sbírky delegátů |

### Návratová hodnota

Odkaz na sebe

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) metoda


Odstraní zadaný objekt MulticastDelegate ze sbírky delegátů.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Instance třídy MulticastDelegate, která má být odstraněna ze sbírky delegátů |

### Návratová hodnota

Odkaz na sebe

## Viz také

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)