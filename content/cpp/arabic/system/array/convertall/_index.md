---
title: ConvertAll()
second_title: دليل API لـ Aspose.Slides للـ C++
description: ينشئ كائن Array جديد ويملأه بعناصر المصفوفة المحددة بعد تحويلها إلى النوع OutputType باستخدام المندوب (delegate) المحول المحدد.
type: docs
weight: 625
url: /ar/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) طريقة

ينشئ كائن [Array](../) جديد ويملأه بعناصر المصفوفة المحددة بعد تحويلها إلى النوع **OutputType** باستخدام المندوب (delegate) المحول المحدد.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| InputType | نوع عناصر مصفوفة الإدخال |
| OutputType | نوع عناصر المصفوفة الناتجة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | كائن [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | كائن Converter يستخدم لتحويل كل عنصر من مصفوفة الإدخال إلى قيم مكافئة من النوع **OutputType** |

### قيمة الإرجاع

مصفوفة جديدة تحتوي على قيم من النوع **OutputType** مكافئة للقيم في `input_array`

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) طريقة

ينشئ كائن [Array](../) جديد ويملأه بعناصر المصفوفة المحددة بعد تحويلها إلى النوع **OutputType** باستخدام كائن الدالة المحول المحدد.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| InputType | نوع عناصر مصفوفة الإدخال |
| OutputType | نوع عناصر المصفوفة الناتجة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | كائن [Array](../) |
| converter | std::function\<OutputType(InputType)> | كائن دالة يستخدم لتحويل كل عنصر من مصفوفة الإدخال إلى قيم مكافئة من النوع **OutputType** |

### قيمة الإرجاع

مصفوفة جديدة تحتوي على قيم من النوع **OutputType** مكافئة للقيم في `input_array`

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [Converter](../../converter/)
* فئة [Array](../)
* نطاق الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)