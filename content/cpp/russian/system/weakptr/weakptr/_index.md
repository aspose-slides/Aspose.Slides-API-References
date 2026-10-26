---
title: WeakPtr()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт нулевой указатель.
type: docs
weight: 1
url: /ru/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) конструктор

Создаёт нулевой указатель.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) конструктор

Создаёт слабый указатель на заданный объект.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) для создания слабого указателя на. |

## WeakPtr::WeakPtr(const SmartPtr_\&) конструктор

Создаёт слабый указатель, ссылающийся на тот же указатель, на который указывает ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Указатель, из которого копируется значение pointee. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) конструктор

Создаёт слабый указатель, ссылающийся на тот же указатель, на который указывает x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип pointee исходного указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Указатель, из которого копируется значение pointee. |

## WeakPtr::WeakPtr(const WeakPtr_\&) конструктор

Создаёт копию слабого указателя.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Указатель, из которого копируется значение pointee. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) конструктор

Создаёт копию слабого указателя.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип pointee источника. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Указатель, из которого копируется значение pointee. |

## WeakPtr::WeakPtr(SmartPtr_\&&) конструктор

Перемещает слабый указатель.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Указатель, из которого перемещается значение pointee. |

## См. также

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)