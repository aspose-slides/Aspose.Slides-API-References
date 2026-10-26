---
title: UnboxToNullable()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يفك تغليف الكائن إلى نوع قابل للإلغاء.
type: docs
weight: 79
url: /ar/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) طريقة

يفك تغليف الكائن إلى نوع قابل للإلغاء.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الوجهة. |

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) لتفكيك. |
| safe | **bool** | إذا كان صحيحًا، أعد nullptr عند الفشل، وإلا ارمِ استثناء InvalidCastException. |

### قيمة الإرجاع

قيمة قابلة للإلغاء تم تفكيكها (قد تكون null).

## انظر أيضًا

* الفئة [Nullable](../../nullable/)
* الفئة [SmartPtr](../../smartptr/)
* الفئة [Object](../../object/)
* الفئة [ObjectExt](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)