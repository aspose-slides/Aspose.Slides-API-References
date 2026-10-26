---
title: disconnect()
second_title: Aspose.Slides для C++ API Reference
description: Удаляет указанный делегат из коллекции делегатов.
type: docs
weight: 170
url: /ru/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) метод


Удаляет указанный делегат из коллекции делегатов.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [Callback](../callback/) | Делегат, который необходимо удалить из коллекции |

### Возвращаемое значение

Ссылка на текущий объект

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) метод


Удаляет указанный нестатический метод указанного объекта из коллекции делегатов.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который должен быть удалён из коллекции делегатов |
| ClassType | Тип объекта, метод которого должен быть удалён из коллекции делегатов |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| member | MemberType ClassType::* | Указатель на нестатический метод указанного объекта |
| obj | ClassType * | Указатель на объект, метод которого должен быть удалён из коллекции делегатов |

### Возвращаемое значение

Ссылка на текущий объект

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) метод


Удаляет указанный нестатический метод указанного объекта из коллекции делегатов.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который должен быть удалён из коллекции делегатов |
| ClassType | Тип объекта, метод которого должен быть удалён из коллекции делегатов |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| member | MemberType ClassType::* | Указатель на нестатический метод указанного объекта |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Разделяемый указатель на объект, метод которого должен быть удалён из коллекции делегатов |

### Возвращаемое значение

Ссылка на текущий объект

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) метод


Удаляет указанный объект MulticastDelegate из коллекции делегатов.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Экземпляр класса MulticastDelegate, который необходимо удалить из коллекции делегатов |

### Возвращаемое значение

Ссылка на текущий объект

## См. также

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)