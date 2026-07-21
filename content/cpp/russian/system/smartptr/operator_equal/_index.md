---
title: operator=()
second_title: Aspose.Slides для C++ справочник API
description: Перемещающее присваивание объекту SmartPtr. x становится недоступным.
type: docs
weight: 27
url: /ru/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) метод


Перемещающее присваивание объекту [SmartPtr](../). x становится недоступным.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Указатель для перемещающего присваивания. |

### Возвращаемое значение

Ссылка на этот объект.

## SmartPtr::operator=(const SmartPtr_&) метод


Копирующее присваивание объекту [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | Указатель для копирующего присваивания. |

### Возвращаемое значение

Ссылка на этот объект.

## SmartPtr::operator=(const SmartPtr\<Q\>&) метод


Копирующее присваивание объекту [SmartPtr](../). Выполняет необходимые преобразования типов.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип объекта, на который указывает x. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [SmartPtr](../)<Q>& | Указатель для копирующего присваивания. |

### Возвращаемое значение

Ссылка на этот объект.

## SmartPtr::operator=(Pointee_ *) метод


Назначает сырый указатель объекту [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Значение указателя для назначения. |

### Возвращаемое значение

Ссылка на этот объект.

## SmartPtr::operator=(std::nullptr_t) метод


Устанавливает значение указателя в nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### Возвращаемое значение

Ссылка на этот объект.

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)