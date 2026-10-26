---
title: GetHashCode()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает хеш-код для указанного скалярного значения.
type: docs
weight: 2445
url: /ru/system/gethashcode/
---
## System::GetHashCode(const T\&) функция


Возвращает хеш-код для указанного скалярного значения.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of the value for which the function generates hash code |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | The value to generate hash code for |

### Возвращаемое значение

The hash code generated for the specified value

## System::GetHashCode(const T\&) функция


Возвращает хеш-код для указанного объекта.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of the object for which the function generates hash code |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | The [SmartPtr](../smartptr/) pointing to the object to generate hash code for |

### Возвращаемое значение

The hash code generated for the specified object

## System::GetHashCode(const T\&) функция


Возвращает хеш-код для указанного объекта, который является исключением.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of the object for which the function generates hash code |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | The Exception Wrapper that contains the object to generate hash code for |

### Возвращаемое значение

The hash code generated for the specified object

## System::GetHashCode(const T\&) функция


Возвращает хеш-код для указанного объекта, который не является умным указателем и не является исключением.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of the object for which the function generates hash code |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | A const reference to the object to generate hash code for |

### Возвращаемое значение

The hash code generated for the specified object

## System::GetHashCode(const std::thread::id\&) функция


Specialization for std::thread::id; Returns the hash code for the specified thread object.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## См. также

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)