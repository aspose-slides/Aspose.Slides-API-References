---
title: PropertyInfo()
second_title: مرجع API Aspose.Slides للغة C++
description: المُنشئ. خاصية ذات مُستخرج ثابت فقط.
type: docs
weight: 66
url: /ar/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) المُنشئ

المُنشئ. خاصية ذات مُستخرج ثابت فقط.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| PropertyType | نوع الخاصية. |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) المُنشئ

المُنشئ. خاصية ذات مُستخرج غير ثابت فقط.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| PropertyType | نوع الخاصية. |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) المُنشئ

المُنشئ.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| PropertyType | نوع الخاصية. |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | طريقة الضبط. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) المُنشئ

المُنشئ. [Nullable](../../../system/nullable/) خاصية مع مُحدد ومُستخرج.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| PropertyType | نوع الخاصية. |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | طريقة الضبط. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) المُنشئ

المُنشئ. [Nullable](../../../system/nullable/) خاصية مع مُستخرج ثابت فقط.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| PropertyType | نوع الخاصية. |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | طريقة الضبط. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) المُنشئ

المُنشئ. [Object](../../../system/object/) خاصية مع مُستخرج فقط.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| PropertyType | نوع الخاصية. |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | طريقة الضبط. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) المُنشئ

ينشئ معلومات خاصية النص.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | طريقة الضبط. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) المُنشئ

ينشئ معلومات خاصية النص من الفئة مع مُستخرج ثابت.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | طريقة الضبط. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) المُنشئ

ينشئ [Decimal](../../../system/decimal/) معلومات الخاصية.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | طريقة الضبط. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) المُنشئ

ينشئ [Decimal](../../../system/decimal/) معلومات الخاصية من الفئة مع مُستخرج ثابت.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | طريقة الضبط. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) المُنشئ

ينشئ معلومات الخاصية المنطقية.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)(**bool**) | طريقة الضبط. |
| get_prop_method | **bool**(ClassType::*)() | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) المُنشئ

ينشئ معلومات الخاصية المنطقية من الفئة مع مُستخرج ثابت.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)(**bool**) | طريقة الضبط. |
| get_prop_method | **bool**(ClassType::*)() const | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) المُنشئ

ينشئ معلومات الخاصية **int64_t**.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)(**int64_t**) | طريقة الضبط. |
| get_prop_method | **int64_t**(ClassType::*)() | طريقة الاسترجاع. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) المُنشئ

ينشئ معلومات الخاصية **int64_t** من الفئة مع مُستخرج ثابت.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| ClassType | نوع الفئة التي تنتمي إليها الخاصية. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية. |
| set_prop_method | void(ClassType::*)(**int64_t**) | طريقة الضبط. |
| get_prop_method | **int64_t**(ClassType::*)() const | طريقة الاسترجاع. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)