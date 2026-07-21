---
title: Is()
second_title: Aspose.Slides для C++ справочника API
description: Реализует перевод оператора 'is'. Специализация для упаковываемых (значимых) типов, которые именно таковыми и являются.
type: docs
weight: 92
url: /ru/system/objectext/is/
---
## ObjectExt::Is(const T\&) метод


Реализует перевод оператора `is`. Специализация для упаковываемых (значимых) типов, что именно они являются.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) для проверки оператора `is`. Игнорируется. |

### Возвращаемое значение

Всегда true

## ObjectExt::Is(const U\&) метод


Реализует перевод оператора `is`. Специализация для указательных типов, оптимизированных для «final» классов.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |
| U | Тестируемый тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const U\&) метод


Реализует перевод оператора `is`. Специализация для указательных типов.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |
| U | Тестируемый тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const Object\&) метод


Реализует перевод оператора `is`. Специализация для значимых типов.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const Object\&) метод


Реализует перевод оператора `is`. Специализация для неконвертируемых типов.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

Всегда возвращает false, так как типы неконвертируемы.

## ObjectExt::Is(const SmartPtr\<U\>\&) метод


Реализует перевод оператора `is`. Специализация для указательных типов.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) метод


Реализует перевод оператора `is`. Специализация для типов-обёрток исключений.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) метод


Реализует перевод оператора `is`. Специализация для nullable-типов.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) метод


Реализует перевод оператора `is`. Специализация для упаковываемых типов с определённым оператором `==`.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) метод


Реализует перевод оператора `is`. Специализация для упаковываемых типов без определённого `==`.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const SmartPtr\<V\>\&) метод


Реализует перевод оператора `is`. Специализация для значимых типов, упакованных в интерфейсы.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |
| V | Тип указываемого объекта. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const SmartPtr\<U\>\&) метод


Реализует перевод оператора `is`. Специализация для enum-типов.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |
| U | Тип указываемого объекта. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const WeakPtr\<U\>\&) метод


Реализует перевод оператора `is`. Специализация для enum-типов против слабых указателей.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |
| U | Тип указываемого объекта. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) для проверки оператора `is`. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const Nullable\<U\>\&) метод


Реализует перевод оператора `is`. Специализация для типа [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) тип. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(const char16_t *) метод


Реализует перевод оператора `is`. Специализация для строкового литерала.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) литерал. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## ObjectExt::Is(int32_t) метод


Реализует перевод оператора `is`. Специализация для целочисленного литерала.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **int32_t** | целочисленный литерал. |

### Возвращаемое значение

True если `is` возвращает true, иначе false.

## Смотрите также

* Класс [ObjectExt](../)
* Класс [Object](../../object/)
* Класс [SmartPtr](../../smartptr/)
* Класс [ExceptionWrapper](../../exceptionwrapper/)
* Класс [WeakPtr](../../weakptr/)
* Класс [Nullable](../../nullable/)
* Структура [IsBoxable](../../isboxable/)
* Структура [IsSmartPtr](../../issmartptr/)
* Структура [IsExceptionWrapper](../../isexceptionwrapper/)
* Структура [IsNullable](../../isnullable/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)