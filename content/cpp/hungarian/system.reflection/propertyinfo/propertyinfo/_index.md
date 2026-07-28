---
title: PropertyInfo()
second_title: Aspose.Slides for C++ API Referencia
description: Konstruktor. Csak const getterrel rendelkező tulajdonság.
type: docs
weight: 66
url: /hu/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor


Konstruktor. Csak const getterrel rendelkező tulajdonság.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| PropertyType | A tulajdonság típusa. |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter metódus. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor


Konstruktor. Csak nem const getterrel rendelkező tulajdonság.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| PropertyType | A tulajdonság típusa. |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor


Konstruktor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| PropertyType | A tulajdonság típusa. |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter metódus. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) konstruktor


Konstruktor. [Nullable](../../../system/nullable/) tulajdonság setterrel és getterrel.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| PropertyType | A tulajdonság típusa. |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter metódus. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) konstruktor


Konstruktor. [Nullable](../../../system/nullable/) tulajdonság csak const getterrel.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| PropertyType | A tulajdonság típusa. |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Setter metódus. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor


Konstruktor. [Object](../../../system/object/) tulajdonság csak getterrel.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| PropertyType | A tulajdonság típusa. |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Setter metódus. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) konstruktor


Létrehozza a string típusú tulajdonság információt.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter metódus. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) konstruktor


Létrehozza a string típusú tulajdonság információt a const getterrel rendelkező osztályból.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Setter metódus. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) konstruktor


Létrehozza a [Decimal](../../../system/decimal/) tulajdonság információt.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter metódus. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) konstruktor


Létrehozza a [Decimal](../../../system/decimal/) tulajdonság információt a const getterrel rendelkező osztályból.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Setter metódus. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) konstruktor


Létrehozza a logikai tulajdonság információt.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter metódus. |
| get_prop_method | **bool**(ClassType::*)() | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) konstruktor


Létrehozza a logikai tulajdonság információt a const getterrel rendelkező osztályból.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)(**bool**) | Setter metódus. |
| get_prop_method | **bool**(ClassType::*)() const | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) konstruktor


Létrehozza a **int64_t** típusú tulajdonság információt.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter metódus. |
| get_prop_method | **int64_t**(ClassType::*)() | Getter metódus. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) konstruktor


Létrehozza a **int64_t** típusú tulajdonság információt a const getterrel rendelkező osztályból.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| ClassType | A tulajdonságot tartalmazó osztály típusa. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Tulajdonság neve. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Setter metódus. |
| get_prop_method | **int64_t**(ClassType::*)() const | Getter metódus. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [PropertyInfo](../)
* Osztály [Nullable](../../../system/nullable/)
* Osztály [Decimal](../../../system/decimal/)
* Névtér [System::Reflection](../../)
* Könyvtár [Aspose.Slides](../../../)