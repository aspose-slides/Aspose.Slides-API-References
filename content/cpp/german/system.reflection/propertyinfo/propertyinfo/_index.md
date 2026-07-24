---
title: PropertyInfo()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruktor. Eigenschaft nur mit const Getter.
type: docs
weight: 66
url: /de/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) Konstruktor


Konstruktor. Eigenschaft nur mit const Getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) Konstruktor


Konstruktor. Eigenschaft nur mit non-const Getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) Konstruktor


Konstruktor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) Konstruktor


Konstruktor. [Nullable](../../../system/nullable/) Eigenschaft mit Setter und Getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) Konstruktor


Konstruktor. [Nullable](../../../system/nullable/) Eigenschaft nur mit const Getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter method. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) Konstruktor


Konstruktor. [Object](../../../system/object/) Eigenschaft nur mit Getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| PropertyType | Type of the property. |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter method. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) Konstruktor


Erstellt String-Eigenschaftsinformation.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) Konstruktor


Erstellt String-Eigenschaftsinformation aus Klasse mit const Getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter method. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) Konstruktor


Erstellt [Decimal](../../../system/decimal/) Eigenschaftsinformation.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) Konstruktor


Erstellt [Decimal](../../../system/decimal/) Eigenschaftsinformation aus Klasse mit const Getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter method. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) Konstruktor


Erstellt boolesche Eigenschaftsinformation.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) Konstruktor


Erstellt boolesche Eigenschaftsinformation aus Klasse mit const Getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter method. |
| get_prop_method | **bool**(ClassType::*)() const | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) Konstruktor


Erstellt **int64_t** Eigenschaftsinformation.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() | Getter method. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) Konstruktor


Erstellt **int64_t** Eigenschaftsinformation aus Klasse mit const Getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ClassType | Type of the class the property belongs to. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Property name. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter method. |
| get_prop_method | **int64_t**(ClassType::*)() const | Getter method. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)