---
title: Convert()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يقوم بتحويل قيمة إلى System::TypeInfo المحدد."
type: docs
weight: 1
url: /ar/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) طريقة

يقوم بتحويل قيمة إلى [System::TypeInfo](../../../system/typeinfo/) المحدد.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | الكائن الذي سيتم تحويله. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | الـ [System::TypeInfo](../../../system/typeinfo/) الذي ستحول إليه القيمة. |

### قيمة الإرجاع

القيمة المحوَّلة.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) طريقة

يقوم بتحويل قيمة إلى [System::TypeCode](../../../system/typecode/) المحدد.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | الكائن الذي سيتم تحويله. |
| typeCode | [TypeCode](../../../system/typecode/) | الـ [System::TypeCode](../../../system/typecode/) الذي ستحول إليه القيمة. |

### قيمة الإرجاع

القيمة المحوَّلة.

## انظر أيضًا

* تعداد [TypeCode](../../../system/typecode/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [FormatterConverter](../)
* نطاق [System::Runtime::Serialization](../../)
* مكتبة [Aspose.Slides](../../../)