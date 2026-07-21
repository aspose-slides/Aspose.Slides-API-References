---
title: DynamicWeakPtr()
second_title: Справочник API Aspose.Slides для C++
description: Создает нулевой умный указатель.
type: docs
weight: 1
url: /ru/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) конструктор

Создает нулевой умный указатель.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) конструктор

Создает умный указатель, указывающий на заданный объект.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Указатель. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_&) конструктор

Копирует умный указатель.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Умный указатель, из которого копируются данные указателя. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) конструктор

Копирует умный указатель.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип указателя-источника. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Умный указатель, из которого копируются данные указателя. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_&) конструктор

Копирует умный указатель.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Умный указатель, из которого копируются данные указателя. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_&&) конструктор

Перемещает умный указатель.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Умный указатель, из которого перемещаются данные указателя. После вызова становится непригодным к использованию. |

## См. также

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Класс [DynamicWeakPtr](../)
* Класс [SmartPtr](../../smartptr/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)