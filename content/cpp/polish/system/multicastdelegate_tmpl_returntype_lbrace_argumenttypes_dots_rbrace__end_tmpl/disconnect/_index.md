---
title: disconnect()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Usuwa określony delegat z kolekcji delegatów.
type: docs
weight: 170
url: /pl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) metoda


Usuwa określony delegat z kolekcji delegatów.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [Callback](../callback/) | Delegat do usunięcia z kolekcji |

### Wartość zwracana

Referencja do obiektu

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) metoda


Usuwa określoną metodę niestatyczną określonego obiektu z kolekcji delegatów.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| MemberType | Typ metody niestatycznej, która ma zostać usunięta z kolekcji delegatów |
| ClassType | Typ obiektu, którego metoda ma zostać usunięta z kolekcji delegatów |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| member | MemberType ClassType::* | Wskaźnik na metodę niestatyczną określonego obiektu |
| obj | ClassType * | Wskaźnik na metodę członkowską obiektu, która ma zostać usunięta z kolekcji delegatów |

### Wartość zwracana

Referencja do obiektu

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metoda


Usuwa określoną metodę niestatyczną określonego obiektu z kolekcji delegatów.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| MemberType | Typ metody niestatycznej, która ma zostać usunięta z kolekcji delegatów |
| ClassType | Typ obiektu, którego metoda ma zostać usunięta z kolekcji delegatów |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| member | MemberType ClassType::* | Wskaźnik na metodę niestatyczną określonego obiektu |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Współdzielony wskaźnik do obiektu, którego metoda ma zostać usunięta z kolekcji delegatów |

### Wartość zwracana

Referencja do obiektu

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) metoda


Usuwa określony obiekt MulticastDelegate z kolekcji delegatów.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Instancja klasy MulticastDelegate do usunięcia z kolekcji delegatów |

### Wartość zwracana

Referencja do obiektu

## Zobacz także

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)