---
title: MulticastDelegate()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт пустую коллекцию.
type: docs
weight: 1
url: /ru/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() метод

Создаёт пустую коллекцию.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) метод

Эквивалент дефолтному конструктору.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) метод

Выполняет поверхностное копирование коллекции делегатов.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| o | const MulticastDelegate\& | Экземпляр класса MulticastDelegate, из которого копируется коллекция делегатов. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) метод

Конструктор перемещения.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| o | MulticastDelegate\&& | Экземпляр класса MulticastDelegate, из которого перемещается коллекция делегатов. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) метод

Создаёт экземпляр и помещает указанный делегат в коллекцию делегатов.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Делегат, который будет помещён в коллекцию делегатов |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) метод

Создаёт экземпляр и помещает указанное значение в коллекцию делегатов.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип значения, которое будет помещено в коллекцию делегатов вновь созданного экземпляра; тип должен быть преобразуемым к типу Callback. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg | T | Значение, которое будет помещено в коллекцию делегатов |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) метод

Создаёт экземпляр и помещает указанное значение в коллекцию делегатов.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Значение, которое будет помещено в коллекцию делегатов |

## См. также

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)