---
title: Convert()
second_title: مرجع API Aspose.Slides برای C++
description: "مقداری را به System::TypeInfo داده‌شده تبدیل می‌کند."
type: docs
weight: 1
url: /fa/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) متد

یک مقدار را به [System::TypeInfo](../../../system/typeinfo/) داده شده تبدیل می‌کند.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | شی‌ای که باید تبدیل شود. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | [System::TypeInfo](../../../system/typeinfo/)ی که مقدار باید به آن تبدیل شود. |

### مقدار بازگشتی

مقدار تبدیل‌شده.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) متد

یک مقدار را به [System::TypeCode](../../../system/typecode/) داده شده تبدیل می‌کند.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | شی‌ای که باید تبدیل شود. |
| typeCode | [TypeCode](../../../system/typecode/) | [System::TypeCode](../../../system/typecode/)ی که مقدار باید به آن تبدیل شود. |

### مقدار بازگشتی

مقدار تبدیل‌شده.

## موارد مرتبط

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)