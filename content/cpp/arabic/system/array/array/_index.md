---
title: Array()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مصفوفة فارغة.
type: docs
weight: 1
url: /ar/system/array/array/
---
## Array::Array() المُنشئ

ينشئ مصفوفة فارغة.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) المُنشئ

منشئ تعبئة.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| count | int | الحجم الأولي للمصفوفة |
| init | const T\& | القيمة الأولية المستخدمة لملء المصفورة |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) المُنشئ

منشئ تعبئة.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| ValueType | نوع القيمة الأولية |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | الحجم الأولي للمصفوفة |
| init | [ValueType](../valuetype/) | القيمة الأولية المستخدمة لملء المصفورة |

## Array::Array(int, const T) المُنشئ

منشئ تعبئة.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| count | int | الحجم الأولي للمصفوفة |
| inits | const T | القيم المستخدمة لملء المصفورة |

## Array::Array(vector_t\&&) المُنشئ

منشئ نقل.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector، العناصر التي يحصل عليها المصفوفة |

## Array::Array(const vector_t\&) المُنشئ

منشئ نسخة.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector لنسخ القيم منه |

## Array::Array(const std::vector\<Q\>\&) المُنشئ

ينشئ كائن [Array](../) ويملؤه بالقيم المنقولة من كائن std::vector يكون نوع قيمه هو نفسه **T** لكنه مختلف عن **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Q | نوع عناصر كائن std::vector الذي تُنسخ العناصر منه |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector لنسخ القيم منه |

## Array::Array(std::vector\<Q\>\&&) المُنشئ

ينشئ كائن [Array](../) ويملؤه بالقيم المنقولة من كائن std::vector يكون نوع قيمه هو نفسه **T** لكنه مختلف عن **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Q | نوع عناصر كائن std::vector الذي تُنقل العناصر منه |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector لنقل القيم منه |

## Array::Array(std::initializer_list\<UnderlyingType\>) المُنشئ

ينشئ كائن [Array](../) ويملؤه بالقيم من قائمة التهيئة المحددة التي تحتوي على عناصر من نوع **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | قائمة التهيئة التي تحتوي على عناصر لملء المصفورة |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) المُنشئ

ينشئ كائن [Array](../) ويملؤه بالقيم من المصفوفة المحددة التي تحتوي على عناصر من نوع **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| InitArraySize | عدد عناصر مصفوفة **init**. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) لنسخها إلى المصفوفة التي يتم إنشاؤها. |

## Array::Array(std::initializer_list\<bool\>, int) المُنشئ

ينشئ كائن [Array](../) ويملؤه بالقيم من قائمة التهيئة المحددة التي تحتوي على عناصر من نوع bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | قائمة التهيئة التي تحتوي على عناصر لملء المصفورة |

## أنظر أيضًا

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)