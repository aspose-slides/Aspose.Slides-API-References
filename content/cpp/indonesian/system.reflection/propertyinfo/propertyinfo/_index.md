---
title: PropertyInfo()
second_title: Referensi API Aspose.Slides untuk C++
description: Konstruktor. Properti dengan hanya getter const.
type: docs
weight: 66
url: /id/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor


Konstruktor. Properti dengan hanya getter const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| PropertyType | Tipe properti. |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Metode getter. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor


Konstruktor. Properti dengan hanya getter non-const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| PropertyType | Tipe properti. |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor


Konstruktor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| PropertyType | Tipe properti. |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Metode setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) konstruktor


Konstruktor. Properti [Nullable](../../../system/nullable/) dengan setter dan getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| PropertyType | Tipe properti. |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Metode setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) konstruktor


Konstruktor. Properti [Nullable](../../../system/nullable/) dengan hanya getter const.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| PropertyType | Tipe properti. |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Metode setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor


Konstruktor. Properti [Object](../../../system/object/) dengan hanya getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| PropertyType | Tipe properti. |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Metode setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) konstruktor


Membuat informasi properti string.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Metode setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) konstruktor


Membuat informasi properti string dari kelas dengan getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Metode setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) konstruktor


Membuat informasi properti [Decimal](../../../system/decimal/).

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Metode setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) konstruktor


Membuat informasi properti [Decimal](../../../system/decimal/) dari kelas dengan getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Metode setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) konstruktor


Membuat informasi properti boolean.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)(**bool**) | Metode setter. |
| get_prop_method | **bool**(ClassType::*)() | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) konstruktor


Membuat informasi properti boolean dari kelas dengan getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)(**bool**) | Metode setter. |
| get_prop_method | **bool**(ClassType::*)() const | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) konstruktor


Membuat informasi properti **int64_t**.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Metode setter. |
| get_prop_method | **int64_t**(ClassType::*)() | Metode getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) konstruktor


Membuat informasi properti **int64_t** dari kelas dengan getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ClassType | Tipe kelas tempat properti berada. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama properti. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Metode setter. |
| get_prop_method | **int64_t**(ClassType::*)() const | Metode getter. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)