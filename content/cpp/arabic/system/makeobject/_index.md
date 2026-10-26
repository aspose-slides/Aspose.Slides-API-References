---
title: MakeObject()
second_title: Aspose.Slides لمرجع API C++
description: ينشئ كائنًا في الذاكرة المخصصة ويعيد مؤشرًا مشتركًا إليه.
type: docs
weight: 2887
url: /ar/system/makeobject/
---
## System::MakeObject(Args\&&...) دالة

ينشئ كائنًا في الذاكرة المخصصة (heap) ويعيد مؤشرًا مشتركًا إليه.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | الفئة لإنشاء كائن منها. |
| Args | أنواع وسائط المُنشئ. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| args | Args\&&... | وسائط المُنشئ. |

### قيمة الإرجاع

[SmartPtr](../smartptr/) إلى الكائن الذي تم إنشاؤه حديثًا، دائمًا في وضع مشترك.

## System::MakeObject(Args\&&...) دالة

ينشئ كائنًا في الذاكرة المخصصة (heap) ويعيد مؤشرًا مشتركًا إليه.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | [SmartPtr](../smartptr/) إلى الفئة لإنشاء كائن منها. |
| Args | أنواع وسائط المُنشئ. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| args | Args\&&... | وسائط المُنشئ. |

### قيمة الإرجاع

[SmartPtr](../smartptr/) إلى الكائن الذي تم إنشاؤه حديثًا، دائمًا في وضع مشترك.

## انظر أيضًا

* الفئة [SmartPtr](../smartptr/)
* الهيكل [IsSmartPtr](../issmartptr/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)