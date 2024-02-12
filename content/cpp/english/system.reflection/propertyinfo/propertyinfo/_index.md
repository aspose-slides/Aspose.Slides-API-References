---
title: PropertyInfo()
second_title: Aspose.Slides for C++ API Reference
description: Constructor. Property with only const getter.
type: docs
weight: 66
url: /system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor


Constructor. Property with only const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Constructor. Property with only non-const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Template parameters

| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor


Constructor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) constructor


Constructor. [Nullable](../../../system/nullable/) property with setter and getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Template parameters

| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) constructor


Constructor. [Nullable](../../../system/nullable/) property with const getter only.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor


Constructor. [Object](../../../system/object/) property with getter only.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Template parameters

| Parameter | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) constructor


Constructs string property information.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) constructor


Constructs string property information from class with const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) constructor


Constructs [Decimal](../../../system/decimal/) property information.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) constructor


Constructs [Decimal](../../../system/decimal/) property information from class with const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) constructor


Constructs boolean property information.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) constructor


Constructs boolean property information from class with const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) constructor


Constructs **int64_t** property information.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) constructor


Constructs **int64_t** property information from class with const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() const | Getter method. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)