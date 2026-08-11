---
title: CopyTo()
second_title: مرجع API Aspose.Slides للغة C++
description: ينسخ عناصر القائمة إلى عناصر مصفوفة موجودة.
type: docs
weight: 209
url: /ar/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) طريقة

ينسخ عناصر القائمة إلى عناصر مصفوفة موجودة.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | مصفوفة الوجهة. |
| arrayIndex | int | فهرس البدء لمصفوفة الوجهة. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) طريقة

ينسخ جميع العناصر إلى عناصر مصفوفة موجودة.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) لنسخ العناصر إليه. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) طريقة

ينسخ العناصر بدءًا من الفهرس المحدد إلى عناصر مصفوفة موجودة.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس يبدأ من 0 للعنصر في القائمة الممثلة بالكائن الحالي للبدء بالنسخ منه |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) لنسخ العناصر إليه. |
| arrayIndex | int | الموضع الابتدائي في مصفوفة الوجهة. |
| count | int | عدد العناصر التي سيتم نسخها. |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)