---
title: Cast()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указатель к его собственному типу.
type: docs
weight: 287
url: /ru/system/smartptr/cast/
---
## SmartPtr::Cast() const метод


Преобразует указатель к его собственному типу.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Y | Целевой тип указываемого объекта. |
| Check | Флаги для генерации исключения, если приведение невозможно. |

### Возвращаемое значение

Указатель изменённого типа, который всегда находится в режиме shared.

## SmartPtr::Cast() const метод


Преобразует указатель к базовому типу с помощью static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Y | Целевой тип указываемого объекта. |
| Check | Флаги для генерации исключения, если приведение невозможно. |

### Возвращаемое значение

Указатель изменённого типа, который всегда находится в режиме shared.

## SmartPtr::Cast() const метод


Преобразует указатель к типу-наследнику с помощью dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Y | Целевой тип указываемого объекта. |
| Check | Флаги для генерации исключения, если приведение невозможно. |

### Возвращаемое значение

Указатель изменённого типа, который всегда находится в режиме shared. Выбрасывает InvalidCastException, если преобразование недоступно.

## SmartPtr::Cast() const метод


Преобразует указатель к типу-наследнику с помощью dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Y | Целевой тип указываемого объекта. |
| Check | Флаги для генерации исключения, если приведение невозможно. |

### Возвращаемое значение

Указатель изменённого типа, который всегда находится в режиме shared. Возвращает nullptr, если преобразование недоступно.

## См. также

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)