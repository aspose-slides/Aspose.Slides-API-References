---
title: Convert()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: معلومات RTTI.
type: docs
weight: 1
url: /ar/system.runtime.serialization/iformatterconverter/convert/
---
## طريقة IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


معلومات RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | الكائن المراد تحويله. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | ال[System::TypeInfo](../../../system/typeinfo/) التي تُحوَّل إليها القيمة. |

### قيمة الإرجاع

القيمة المحوَّلة.
## ملاحظات


يحوِّل القيمة إلى [System::TypeInfo](../../../system/typeinfo/) المحدد. 
## طريقة IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


يحوِّل القيمة إلى [System::TypeCode](../../../system/typecode/) المحدد.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | الكائن المراد تحويله. |
| typeCode | [TypeCode](../../../system/typecode/) | ال[System::TypeCode](../../../system/typecode/) التي تُحوَّل إليها القيمة. |

### قيمة الإرجاع

القيمة المحوَّلة.

## انظر أيضًا

* تعداد [TypeCode](../../../system/typecode/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [IFormatterConverter](../)
* مساحة الاسم [System::Runtime::Serialization](../../)
* مكتبة [Aspose.Slides](../../../)