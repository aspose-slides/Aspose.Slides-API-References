---
title: Convert()
second_title: مرجع API Aspose.Slides برای C++
description: اطلاعات RTTI.
type: docs
weight: 1
url: /fa/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) متد


اطلاعات RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | شیئی که باید تبدیل شود. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | [System::TypeInfo](../../../system/typeinfo/)ی که مقدار باید به آن تبدیل شود. |

### مقدار بازگشت

مقدار تبدیل شده.
## توضیحات


یک مقدار را به [System::TypeInfo](../../../system/typeinfo/) داده شده تبدیل می‌کند. 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) متد


یک مقدار را به [System::TypeCode](../../../system/typecode/) داده شده تبدیل می‌کند.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | شیئی که باید تبدیل شود. |
| typeCode | [TypeCode](../../../system/typecode/) | [System::TypeCode](../../../system/typecode/)ی که مقدار باید به آن تبدیل شود. |

### مقدار بازگشت

مقدار تبدیل شده.

## موارد مرتبط

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)