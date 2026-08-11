---
title: Get()
second_title: مرجع API Aspose.Slides للـ C++
description: دالة للحصول على العنصر رقم N من الـ tuple المعطى. تحميل مخصص للكيان الأساسي.
type: docs
weight: 2406
url: /ar/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) دالة

دالة للحصول على العنصر رقم N من الـ tuple المعطى. تحميل مخصص للكيان الأساسي.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| N | فهرس العنصر. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | الكائن للفحص. |

### قيمة الإرجاع

قيمة العنصر رقم N من الـ tuple تم تحويله إلى كائن.

## System::Get(const T\&) دالة

دالة للحصول على العنصر رقم N من الـ tuple المعطى. تحميل مخصص للكائنات التي تحتوي على طريقة Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| N | فهرس العنصر. |
| T | نوع الكائن المفحوص. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| object | const T\& | الكائن للفحص. |

### قيمة الإرجاع

قيمة العنصر رقم N من الـ tuple.

## System::Get(const SharedPtr\<T\>\&) دالة

دالة للحصول على العنصر رقم N من الـ tuple المعطى. تحميل مخصص للمؤشرات المشتركة.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| N | فهرس العنصر. |
| T | نوع الكائن المفحوص. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | الكائن للفحص. |

### قيمة الإرجاع

قيمة العنصر رقم N من الـ tuple تم تحويله إلى كائن.

## System::Get(T\&, const Index\&) دالة

تنفيذ لتعبيرات collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المجموعة. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| collection | T\& | كائن المجموعة. |
| index | const [Index](../index/)\& | فهرس العنصر من النوع [System.Index](../index/). |

### قيمة الإرجاع

عنصر المجموعة عند الإزاحة المحسوبة.

## System::Get(T\&, const Range\&) دالة

إرجاع شريحة من المجموعة المحددة المعرفة بالنطاق المقدم.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| collection | T\& | المجموعة لتقطيعها. |
| range | const [Range](../range/)\& | النطاق الذي يحدد حدود الشريحة. |

### قيمة الإرجاع

عرض أو شريحة من المجموعة بدءاً من الإزاحة الأولية المحسوبة والطول.

## System::Get(const ValueTuple\<Args...\>\&) دالة

يحصل على العنصر رقم N من value tuple.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| N | فهرس العنصر. |
| Args | عناصر الـ tuple. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | الـ tuple للحصول على العنصر منه. |

### قيمة الإرجاع

قيمة العنصر رقم N من الـ tuple.

## انظر أيضا

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Index](../index/)
* Class [Range](../range/)
* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)