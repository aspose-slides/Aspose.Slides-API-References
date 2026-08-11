---
title: PropertyInfo()
second_title: Aspose.Slides برای C++ مرجع API
description: سازنده. ویژگی فقط دارای getter ثابت.
type: docs
weight: 66
url: /fa/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) سازنده

سازنده. ویژگی فقط دارای getter ثابت.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| PropertyType | نوع ویژگی. |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | متد getter. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) سازنده

سازنده. ویژگی فقط دارای getter غیر ثابت.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| PropertyType | نوع ویژگی. |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) سازنده

سازنده.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| PropertyType | نوع ویژگی. |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | متد setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) سازنده

سازنده. [Nullable](../../../system/nullable/) ویژگی با setter و getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| PropertyType | نوع ویژگی. |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | متد setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) سازنده

سازنده. [Nullable](../../../system/nullable/) ویژگی فقط دارای getter ثابت.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| PropertyType | نوع ویژگی. |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | متد setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) سازنده

سازنده. [Object](../../../system/object/) ویژگی فقط دارای getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| PropertyType | نوع ویژگی. |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | متد setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) سازنده

ساختن اطلاعات ویژگی رشته‌ای.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | متد setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) سازنده

ساختن اطلاعات ویژگی رشته‌ای از کلاس با getter ثابت.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | متد setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) سازنده

ساختن اطلاعات ویژگی [Decimal](../../../system/decimal/).

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | متد setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) سازنده

ساختن اطلاعات ویژگی [Decimal](../../../system/decimal/) از کلاس با getter ثابت.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | متد setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) سازنده

ساختن اطلاعات ویژگی boolean.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)(**bool**) | متد setter. |
| get_prop_method | **bool**(ClassType::*)() | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) سازنده

ساختن اطلاعات ویژگی boolean از کلاس با getter ثابت.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)(**bool**) | متد setter. |
| get_prop_method | **bool**(ClassType::*)() const | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) سازنده

ساختن اطلاعات ویژگی **int64_t**.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)(**int64_t**) | متد setter. |
| get_prop_method | **int64_t**(ClassType::*)() | متد getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) سازنده

ساختن اطلاعات ویژگی **int64_t** از کلاس با getter ثابت.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ClassType | نوع کلاسی که ویژگی به آن تعلق دارد. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام ویژگی. |
| set_prop_method | void(ClassType::*)(**int64_t**) | متد setter. |
| get_prop_method | **int64_t**(ClassType::*)() const | متد getter. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [PropertyInfo](../)
* کلاس [Nullable](../../../system/nullable/)
* کلاس [Decimal](../../../system/decimal/)
* فضا‌نام [System::Reflection](../../)
* Library [Aspose.Slides](../../../)