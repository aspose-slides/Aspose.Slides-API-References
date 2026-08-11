---
title: Cast()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحويل المؤشر إلى نوعه نفسه.
type: docs
weight: 287
url: /ar/system/smartptr/cast/
---
## SmartPtr::Cast() const طريقة

يقوم بتحويل المؤشر إلى نوعه ذاته.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| Y | النوع الهدف للكائن المشار إليه. |
| Check | العلامات التي تُطلق استثناءً إذا لم يتوفر التحويل. |

### قيمة الإرجاع

مؤشر من النوع المتغيّر يكون دائمًا في وضع المشاركة.

## SmartPtr::Cast() const طريقة

يحوِّل المؤشر إلى النوع الأساسي باستخدام static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| Y | النوع الهدف للكائن المشار إليه. |
| Check | العلامات التي تُطلق استثناءً إذا لم يتوفر التحويل. |

### قيمة الإرجاع

مؤشر من النوع المتغيّر يكون دائمًا في وضع المشاركة.

## SmartPtr::Cast() const طريقة

يحوِّل المؤشر إلى النوع المستمد باستخدام dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| Y | النوع الهدف للكائن المشار إليه. |
| Check | العلامات التي تُطلق استثناءً إذا لم يتوفر التحويل. |

### قيمة الإرجاع

مؤشر من النوع المتغيّر يكون دائمًا في وضع المشاركة. يرمي الاستثناء InvalidCastException إذا لم تتوفر عملية تحويل.

## SmartPtr::Cast() const طريقة

يحوِّل المؤشر إلى النوع المستمد باستخدام dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| Y | النوع الهدف للكائن المشار إليه. |
| Check | العلامات التي تُطلق استثناءً إذا لم يتوفر التحويل. |

### قيمة الإرجاع

مؤشر من النوع المتغيّر يكون دائمًا في وضع المشاركة. يرجع nullptr إذا لم تتوفر عملية تحويل.

## انظر أيضًا

* الفئة [SmartPtr](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)