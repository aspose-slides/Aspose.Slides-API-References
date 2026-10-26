---
title: connect()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет указанный делегат в коллекцию.
type: docs
weight: 144
url: /ru/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) метод


Adds the specified delegate to the collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [Callback](../callback/) | Делегат, который нужно добавить в коллекцию |

### Возвращаемое значение

Ссылка на объект

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) метод


Adds the specified function object to the delegate collection. The function object is converted to the Callback delegate type before being added to the collection.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| R | Тип возвращаемого значения объекта функции, который нужно добавить в коллекцию |
| Args | Список аргументов объекта функции, который нужно добавить в коллекцию |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Объект функции, который нужно добавить в коллекцию |

### Возвращаемое значение

Ссылка на объект

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) метод


Adds the specified MulticastDelegate object to the delegate collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Экземпляр класса MulticastDelegate, который нужно добавить в коллекцию делегатов |

### Возвращаемое значение

Ссылка на объект

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) метод


Adds the specified non-static method of the specified object to the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который будет добавлен в коллекцию делегатов |
| ClassType | Тип объекта, метод которого будет добавлен в делегат |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| member | MemberType ClassType::* | Указатель на нестатический метод указанного объекта |
| obj | ClassType * | Указатель на объект, метод которого будет добавлен в коллекцию делегатов |

### Возвращаемое значение

Ссылка на объект

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) метод


Adds the specified non-static method of the specified object to the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который будет добавлен в коллекцию делегатов |
| ClassType | Тип объекта, метод которого будет добавлен в коллекцию делегатов |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| member | MemberType ClassType::* | Указатель на нестатический метод указанного объекта |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Разделяемый указатель на объект, метод которого будет добавлен в коллекцию делегатов |

### Возвращаемое значение

Ссылка на объект

## См. также

* Тип [Callback](../callback/)
* Тип [SharedPtr](../../sharedptr/)
* Метод [MulticastDelegate](../multicastdelegate/)
* Класс [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)