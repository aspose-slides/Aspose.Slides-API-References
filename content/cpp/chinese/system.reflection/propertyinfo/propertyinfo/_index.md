---
title: PropertyInfo()
second_title: Aspose.Slides C++ API 参考
description: 构造函数。属性仅具有 const getter。
type: docs
weight: 66
url: /zh/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) 构造函数

构造函数。属性仅具有 const getter。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| PropertyType | 属性的类型。 |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | getter 方法。 |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) 构造函数

构造函数。属性仅具有非 const getter。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| PropertyType | 属性的类型。 |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) 构造函数

构造函数。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| PropertyType | 属性的类型。 |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | setter 方法。 |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) 构造函数

构造函数。[Nullable](../../../system/nullable/) 属性具有 setter 和 getter。

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| PropertyType | 属性的类型。 |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | setter 方法。 |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) 构造函数

构造函数。[Nullable](../../../system/nullable/) 属性仅具有 const getter。

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| PropertyType | 属性的类型。 |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | setter 方法。 |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) 构造函数

构造函数。[Object](../../../system/object/) 属性仅具有 getter。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| PropertyType | 属性的类型。 |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | setter 方法。 |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) 构造函数

构造字符串属性信息。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | setter 方法。 |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) 构造函数

构造具有 const getter 的类的字符串属性信息。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | setter 方法。 |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) 构造函数

构造[Decimal](../../../system/decimal/)属性信息。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | setter 方法。 |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) 构造函数

构造[Decimal](../../../system/decimal/)属性信息，来自具有 const getter 的类。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | setter 方法。 |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) 构造函数

构造布尔属性信息。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)(**bool**) | setter 方法。 |
| get_prop_method | **bool**(ClassType::*)() | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) 构造函数

构造具有 const getter 的类的布尔属性信息。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)(**bool**) | setter 方法。 |
| get_prop_method | **bool**(ClassType::*)() const | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) 构造函数

构造 **int64_t** 属性信息。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)(**int64_t**) | setter 方法。 |
| get_prop_method | **int64_t**(ClassType::*)() | getter 方法。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) 构造函数

构造具有 const getter 的类的 **int64_t** 属性信息。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| ClassType | 属性所属类的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性名称。 |
| set_prop_method | void(ClassType::*)(**int64_t**) | setter 方法。 |
| get_prop_method | **int64_t**(ClassType::*)() const | getter 方法。 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [PropertyInfo](../)
* 类 [Nullable](../../../system/nullable/)
* 类 [Decimal](../../../system/decimal/)
* 命名空间 [System::Reflection](../../)
* Library [Aspose.Slides](../../../)