---
title: Delegate()
second_title: Aspose.Slides для C++ справочник API
description: Конструктор по умолчанию. Создаёт объект delegate, который не указывает ни на что.
type: docs
weight: 1
url: /ru/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() метод

Конструктор по умолчанию. Создаёт объект Delegate, который не указывает ни на что.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) метод

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) метод

Конструктор перемещения копии. Берёт на себя владение сущностью, на которую указывает указанный объект Delegate.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| o | Delegate\&& | Объект Delegate, из которого перемещается указываемая сущность |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) метод

Конструктор. Создаёт объект Delegate из указанного указателя на свободную функцию или статический метод.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Тип | тип указателя на функцию или статический метод, принимаемый конструктором в качестве аргумента |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| function | T | Указатель на функцию или статический метод, на который будет указывать вновь созданный экземпляр Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) метод

Конструктор. Создаёт объект Delegate из указанного указателя на объект функции, созданный с помощью std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Тип | тип объекта функции, созданного std::bind(), принимаемый конструктором в качестве аргумента |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| function | T | Указатель на «bind-выражение» — указатель на функцию, сгенерированный std::bind(), — на который будет указывать вновь созданный экземпляр Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) метод

Конструктор. Создаёт объект Delegate из указанного объекта функции.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип объекта функции, принимаемый конструктором в качестве аргумента |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functor_tag | int | Фиктивное целочисленное значение; этот аргумент используется для разрешения неоднозначности |
| functor | T\& | Объект функции, на который будет указывать вновь сконструированный delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) метод

Конструктор перемещения. Создаёт объект Delegate из указанного объекта функции.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип объекта функции, принимаемый конструктором в качестве аргумента |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functor_tag | long | Фиктивное целочисленное значение; этот аргумент используется для разрешения неоднозначности |
| functor | T\&& | Объект функции, на который будет указывать вновь сконструированный delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) метод

Конструктор. Создаёт объект Delegate, указывающий на указанный нестатический метод указанного объекта.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который конструктор принимает в качестве аргумента |
| ClassType | Тип объекта, принимаемого конструктором в качестве аргумента |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| member | MemberType ClassType::* | Указатель на нестатический метод, на который будет указывать вновь созданный delegate |
| obj | ClassType * | Указатель на объект, метод которого будет указываться вновь созданным delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) метод

Конструктор. Создаёт объект Delegate, указывающий на указанный нестатический метод указанного объекта.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который конструктор принимает в качестве аргумента |
| ClassType | Тип объекта, принимаемого конструктором в качестве аргумента |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| member | MemberType MemberClass::* | Указатель на нестатический метод, на который будет указывать вновь созданный delegate |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Указатель shared-pointer на объект, метод которого будет указываться вновь созданным delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) метод

Создаёт объект Delegate, указывающий на объект функции std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| R | Тип возвращаемого значения объекта функции, принимаемого конструктором в качестве аргумента |
| Args | Список аргументов объекта функции, принимаемого конструктором в качестве аргумента |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Объект функции, на который будет указывать вновь созданный объект delegate |

## Смотрите также

* Определение типа [SharedPtr](../../sharedptr/)
* Класс [Delegate< ReturnType(ArgumentTypes...)>](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)