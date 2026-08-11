---
title: IndexOf()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد فهرس الظهور الأول للعنصر المحدد في المصفوفة.
type: docs
weight: 131
url: /ar/system/array/indexof/
---
## Array::IndexOf(const T\&) const طريقة

يحدد فهرس الظهور الأول للعنصر المحدد في المصفوفة.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | const T\& | فهرس العنصر المراد تحديده |

### القيمة المرجعة

[Index](../../index/) من أول ظهور للعنصر المحدد إذا تم العثور على العنصر، وإلا -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) طريقة

يحدد فهرس الظهور الأول للعنصر المحدد في المصفوفة.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| ArrayType | نوع العناصر في المصفوفة المستهدفة |
| ValueType | نوع العنصر الذي يُبحث عنه في المصفوفة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) للبحث عن العنصر المحدد في |
| value | const [ValueType](../valuetype/)\& | فهرس العنصر المراد تحديده |

### القيمة المرجعة

[Index](../../index/) من أول ظهور للعنصر المحدد إذا تم العثور على العنصر، وإلا -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) طريقة

يحدد فهرس الظهور الأول للعنصر المحدد في المصفوفة بدءًا من الفهرس المحدد.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| ArrayType | نوع العناصر في المصفوفة المستهدفة |
| ValueType | نوع العنصر الذي يُبحث عنه في المصفوفة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) للبحث عن العنصر المحدد في |
| value | const [ValueType](../valuetype/)\& | فهرس العنصر المراد تحديده |
| startIndex | int | [Index](../../index/) حيث يبدأ البحث |

### القيمة المرجعة

[Index](../../index/) من أول ظهور للعنصر المحدد إذا تم العثور على العنصر، وإلا -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) طريقة

يحدد فهرس الظهور الأول للعنصر المحدد في نطاق من عناصر المصفوفة المحدد بواسطة فهرس البداية وعدد العناصر في النطاق.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| ArrayType | نوع العناصر في المصفوفة المستهدفة |
| ValueType | نوع العنصر الذي يُبحث عنه في المصفوفة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) للبحث عن العنصر المحدد في |
| value | const [ValueType](../valuetype/)\& | فهرس العنصر المراد تحديده |
| startIndex | int | [Index](../../index/) حيث يبدأ البحث |
| count | int | عدد عناصر النطاق للبحث فيه |

### القيمة المرجعة

[Index](../../index/) من أول ظهور للعنصر المحدد إذا تم العثور على العنصر، وإلا -1

## أنظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [ValueType](../valuetype/)
* فئة [Array](../)
* نطاق اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)