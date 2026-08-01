---
title: PropertyInfo()
second_title: Aspose.Slides voor C++ API-referentie
description: Constructor. Eigenschap met alleen const getter.
type: docs
weight: 66
url: /nl/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor

Constructor. Eigenschap met alleen const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| PropertyType | Type van de eigenschap. |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter-methode. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor

Constructor. Eigenschap met alleen non-const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| PropertyType | Type van de eigenschap. |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor

Constructor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| PropertyType | Type van de eigenschap. |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter-methode. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) constructor

Constructor. [Nullable](../../../system/nullable/) eigenschap met setter en getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| PropertyType | Type van de eigenschap. |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter-methode. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) constructor

Constructor. [Nullable](../../../system/nullable/) eigenschap met alleen const getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| PropertyType | Type van de eigenschap. |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter-methode. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor

Constructor. [Object](../../../system/object/) eigenschap met alleen getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| PropertyType | Type van de eigenschap. |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter-methode. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) constructor

Construeert informatie over een string-eigenschap.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter-methode. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) constructor

Construeert informatie over een string-eigenschap van een klasse met const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter-methode. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) constructor

Construeert [Decimal](../../../system/decimal/) eigenschapsinformatie.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter-methode. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) constructor

Construeert [Decimal](../../../system/decimal/) eigenschapsinformatie van een klasse met const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter-methode. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) constructor

Construeert boolean eigenschapsinformatie.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter-methode. |
| get_prop_method | **bool**(ClassType::*)() | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) constructor

Construeert boolean eigenschapsinformatie van een klasse met const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter-methode. |
| get_prop_method | **bool**(ClassType::*)() const | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) constructor

Construeert **int64_t** eigenschapsinformatie.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter-methode. |
| get_prop_method | **int64_t**(ClassType::*)() | Getter-methode. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) constructor

Construeert **int64_t** eigenschapsinformatie van een klasse met const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ClassType | Type van de klasse waartoe de eigenschap behoort. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | Naam van de eigenschap. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter-methode. |
| get_prop_method | **int64_t**(ClassType::*)() const | Getter-methode. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)