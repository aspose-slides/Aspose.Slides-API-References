---
title: IsNull()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет, является ли конкретное значение null. Версия для арифметических и перечислительных типов.
type: docs
weight: 1
url: /ru/system/testtools/isnull/
---
## TestTools::IsNull(T) метод

Проверяет, является ли конкретное значение null. [Version](../../version/) для арифметических и перечислительных типов.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | Value to check for null. |

### Возвращаемое значение

Always returns false.

## TestTools::IsNull(const T\&) метод

Проверяет, является ли конкретное значение null. [Version](../../version/) для неаритметических и не перечислительных типов значений.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Value to check for null. |

### Возвращаемое значение

True if object is compared to nullptr as true, false otherwise.

## TestTools::IsNull(const SharedPtr\<T\>\&) метод

Проверяет, является ли конкретное значение null. [Version](../../version/) для неаритметических типов значений.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Value to check for null. |

### Возвращаемое значение

True if object is compared to nullptr as true, false otherwise.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) метод

Проверяет, является ли конкретное значение null. [Version](../../version/) для пар ключ-значение.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Объект пары. |

### Возвращаемое значение

True if pair is considered null, false otherwise.

## TestTools::IsNull(const System::String\&) метод

Проверяет, является ли строка null.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) для проверки. |

### Возвращаемое значение

True if string is considered null, false otherwise.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Класс [String](../../string/)
* Структура [TestTools](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)