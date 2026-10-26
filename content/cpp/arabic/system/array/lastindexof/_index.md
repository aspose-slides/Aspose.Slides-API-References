---
title: LastIndexOf()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدّد فهرس آخر حدوث للعنصر المحدد في نطاق من عناصر المصفوفة المحددة بفهرس البداية وعدد العناصر في النطاق.
type: docs
weight: 703
url: /ar/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) طريقة

يحدد فهرس آخر ظهور للعنصر المحدد في نطاق من عناصر المصفوفة المحدد بواسطة فهرس البداية وعدد العناصر في النطاق.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| ArrayType | نوع العناصر في المصفوفة المستهدفة |
| ValueType | نوع العنصر الذي يتم البحث عنه في المصفوفة |

### معاملات

| معلمة | النوع | الوصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) للبحث عن العنصر المحدد في |
| value | const [ValueType](../valuetype/)\& | فهرس العنصر الذي سيتم تحديده |
| startIndex | int | [Index](../../index/) حيث يبدأ البحث |
| count | int | عدد العناصر في النطاق الذي سيتم البحث فيه |

### قيمة الإرجاع

[Index](../../index/) لآخر ظهور للعنصر المحدد إذا تم العثور على العنصر، وإلا -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) طريقة

يحدد فهرس آخر ظهور للعنصر المحدد في المصفوفة بدءًا من الفهرس المحدد.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| ArrayType | نوع العناصر في المصفوفة المستهدفة |
| ValueType | نوع العنصر الذي يتم البحث عنه في المصفوفة |

### معاملات

| معلمة | النوع | الوصف |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) للبحث عن العنصر المحدد في |
| value | const [ValueType](../valuetype/)\& | فهرس العنصر الذي سيتم تحديده |
| startIndex | int | [Index](../../index/) حيث يبدأ البحث |

### قيمة الإرجاع

[Index](../../index/) لآخر ظهور للعنصر المحدد إذا تم العثور على العنصر، وإلا -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) طريقة

يحدد فهرس آخر ظهور للعنصر المحدد في المصفوفة.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| ArrayType | نوع العناصر في المصفوفة المستهدفة |
| ValueType | نوع العنصر الذي يتم البحث عنه في المصفوفة |

### معاملات

| معلمة | النوع | الوصف |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) للبحث عن العنصر المحدد في |
| value | const [ValueType](../valuetype/)\& | فهرس العنصر الذي سيتم تحديده |

### قيمة الإرجاع

[Index](../../index/) لآخر ظهور للعنصر المحدد إذا تم العثور على العنصر، وإلا -1

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)