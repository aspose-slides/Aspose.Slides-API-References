---
title: connect()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přidá zadaný delegát do kolekce.
type: docs
weight: 144
url: /cs/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) metoda


Přidá zadaný delegát do kolekce.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [Callback](../callback/) | Delegát, který se má přidat do kolekce |

### Návratová hodnota

Odkaz na sebe

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) metoda


Přidá zadaný objekt funkce do kolekce delegátů. Objekt funkce je před přidáním do kolekce převeden na typ delegáta Callback.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| R | Návratový typ objektu funkce, který se má přidat do kolekce |
| Args | Seznam argumentů objektu funkce, který se má přidat do kolekce |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Objekt funkce, který se má přidat do kolekce |

### Návratová hodnota

Odkaz na sebe

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) metoda


Přidá zadaný objekt MulticastDelegate do kolekce delegátů.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Instance třídy MulticastDelegate, která se má přidat do kolekce delegátů |

### Návratová hodnota

Odkaz na sebe

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) metoda


Přidá zadanou nestatickou metodu daného objektu do kolekce delegátů.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| MemberType | Typ nestatické metody, která se má přidat do kolekce delegátů |
| ClassType | Typ objektu, jehož metoda se má přidat do delegáta |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| member | MemberType ClassType::* | Ukazatel na nestatickou metodu daného objektu |
| obj | ClassType * | Ukazatel na metodu členu objektu, která se má přidat do kolekce delegátů |

### Návratová hodnota

Odkaz na sebe

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metoda


Přidá zadanou nestatickou metodu daného objektu do kolekce delegátů.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| MemberType | Typ nestatické metody, která se má přidat do kolekce delegátů |
| ClassType | Typ objektu, jehož metoda se má přidat do kolekce delegátů |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| member | MemberType ClassType::* | Ukazatel na nestatickou metodu daného objektu |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Sdílený ukazatel na metodu členu objektu, která se má přidat do kolekce delegátů |

### Návratová hodnota

Odkaz na sebe

## Viz také

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Metoda [MulticastDelegate](../multicastdelegate/)
* Třída [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)