---
title: PropertyInfo()
second_title: Aspose.Slides for C++ API 參考
description: 建構函式。僅具 const getter 的屬性。
type: docs
weight: 66
url: /zh-hant/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) 建構函式

建構函式。僅有 const getter 的屬性。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) 建構函式

建構函式。僅有非 const getter 的屬性。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) 建構函式

建構函式。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) 建構函式

建構函式。[Nullable](../../../system/nullable/) 屬性具備 setter 與 getter。

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) 建構函式

建構函式。[Nullable](../../../system/nullable/) 屬性僅具 const getter。

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) 建構函式

建構函式。[Object](../../../system/object/) 屬性僅有 getter。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) 建構函式

建構 string 屬性資訊。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) 建構函式

建構 string 屬性資訊，來自具有 const getter 的類別。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) 建構函式

建構 [Decimal](../../../system/decimal/) 屬性資訊。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) 建構函式

建構 [Decimal](../../../system/decimal/) 屬性資訊，來自具有 const getter 的類別。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) 建構函式

建構 boolean 屬性資訊。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) 建構函式

建構 boolean 屬性資訊，來自具有 const getter 的類別。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) 建構函式

建構 **int64_t** 屬性資訊。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) 建構函式

建構 **int64_t** 屬性資訊，來自具有 const getter 的類別。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() const | Getter method. |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)