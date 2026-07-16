---
title: PropertyInfo()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur. Propriété avec uniquement un accesseur const.
type: docs
weight: 66
url: /fr/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructeur


Constructeur. Propriété avec uniquement un accesseur const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) constructeur


Constructeur. Propriété avec uniquement un accesseur non-const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructeur


Constructeur.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) constructeur


Constructeur. [Nullable](../../../system/nullable/) propriété avec mutateur et accesseur.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) constructeur


Constructeur. [Nullable](../../../system/nullable/) propriété avec uniquement un accesseur const.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) constructeur


Constructeur. [Object](../../../system/object/) propriété avec uniquement un accesseur.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) constructeur


Construit les informations de propriété de chaîne.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) constructeur


Construit les informations de propriété de chaîne à partir d'une classe avec un accesseur const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) constructeur


Construit les informations de propriété [Decimal](../../../system/decimal/).

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) constructeur


Construit les informations de propriété [Decimal](../../../system/decimal/) à partir d'une classe avec un accesseur const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) constructeur


Construit les informations de propriété booléenne.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) constructeur


Construit les informations de propriété booléenne à partir d'une classe avec un accesseur const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) constructeur


Construit les informations de propriété **int64_t**.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) constructeur


Construit les informations de propriété **int64_t** à partir d'une classe avec un accesseur const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() const | Getter method. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)