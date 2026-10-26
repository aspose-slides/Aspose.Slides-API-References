---
title: Clear()
second_title: مرجع API Aspose.Slides للغة C++
description: غير مدعوم لأن المصفوفة التي يمثلها الكائن الحالي هي للقراءة فقط.
type: docs
weight: 53
url: /ar/system/array/clear/
---
## Array::Clear() طريقة

غير مدعوم لأن المصفوفة التي يمثلها الكائن الحالي هي للقراءة فقط.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) طريقة

يستبدل القيم **count** بدءًا من الفهرس **startIndex** في المصفوفة المحددة بالقيم الافتراضية.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Type | نوع العناصر في المصفوفة الهدف |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | المصفوفة المستهدفة |
| startIndex | int | [Index](../../index/) التي يبدأ فيها استبدال العناصر |
| count | int | عدد العناصر التي سيتم استبدالها |

## انظر أيضا

* تعريف النوع [ArrayPtr](../../arrayptr/)
* طريقة [Type](../../object/type/)
* فئة [Array](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)