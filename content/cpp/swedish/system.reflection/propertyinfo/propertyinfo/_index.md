---
title: PropertyInfo()
second_title: Aspose.Slides för C++ API-referens
description: Konstruktor. Egenskap med endast konstant getter.
type: docs
weight: 66
url: /sv/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor


Konstruktor. Egenskap med endast konstant getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter-metod. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor


Konstruktor. Egenskap med endast icke-konstant getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor


Konstruktor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter-metod. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) konstruktor


Konstruktor. [Nullable](../../../system/nullable/) egenskap med setter och getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter-metod. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) konstruktor


Konstruktor. [Nullable](../../../system/nullable/) egenskap med endast konstant getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter-metod. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor


Konstruktor. [Object](../../../system/object/) egenskap med endast getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| PropertyType | Typ av egenskapen. |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter-metod. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) konstruktor


Skapar strängegenskapsinformation.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter-metod. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) konstruktor


Skapar strängegenskapsinformation från klass med konstant getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter-metod. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) konstruktor


Skapar [Decimal](../../../system/decimal/) egenskapsinformation.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter-metod. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) konstruktor


Skapar [Decimal](../../../system/decimal/) egenskapsinformation från klass med konstant getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter-metod. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) konstruktor


Skapar boolesk egenskapsinformation.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter-metod. |
| get_prop_method | **bool**(ClassType::*)() | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) konstruktor


Skapar boolesk egenskapsinformation från klass med konstant getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter-metod. |
| get_prop_method | **bool**(ClassType::*)() const | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) konstruktor


Skapar **int64_t** egenskapsinformation.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter-metod. |
| get_prop_method | **int64_t**(ClassType::*)() | Getter-metod. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) konstruktor


Skapar **int64_t** egenskapsinformation från klass med konstant getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ClassType | Typ av klassen som egenskapen tillhör. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Egenskapsnamn. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter-metod. |
| get_prop_method | **int64_t**(ClassType::*)() const | Getter-metod. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [PropertyInfo](../)
* Klass [Nullable](../../../system/nullable/)
* Klass [Decimal](../../../system/decimal/)
* Namnrymd [System::Reflection](../../)
* Bibliotek [Aspose.Slides](../../../)