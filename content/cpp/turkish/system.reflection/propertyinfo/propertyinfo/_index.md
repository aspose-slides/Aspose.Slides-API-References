---
title: PropertyInfo()
second_title: Aspose.Slides for C++ API Referansı
description: Yapıcı. Sadece const alıcıya sahip özellik.
type: docs
weight: 66
url: /tr/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) yapıcı


Yapıcı. Sadece const alıcıya sahip özellik.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| PropertyType | Özelliğin türü. |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) yapıcı


Yapıcı. Sadece const olmayan alıcıya sahip özellik.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| PropertyType | Özelliğin türü. |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) yapıcı


Yapıcı.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| PropertyType | Özelliğin türü. |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Ayarlayıcı yöntemi. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) yapıcı


Yapıcı. [Nullable](../../../system/nullable/) ayarlayıcı ve alıcıya sahip özellik.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| PropertyType | Özelliğin türü. |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Ayarlayıcı yöntemi. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) yapıcı


Yapıcı. [Nullable](../../../system/nullable/) sadece const alıcıya sahip özellik.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| PropertyType | Özelliğin türü. |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Ayarlayıcı yöntemi. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) yapıcı


Yapıcı. [Object](../../../system/object/) sadece alıcıya sahip özellik.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| PropertyType | Özelliğin türü. |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Ayarlayıcı yöntemi. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) yapıcı


Dize özelliği bilgisini oluşturur.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Ayarlayıcı yöntemi. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) yapıcı


Sınıftan const alıcı ile dize özelliği bilgisini oluşturur.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Ayarlayıcı yöntemi. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) yapıcı


[Decimal](../../../system/decimal/) özelliği bilgisini oluşturur.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Ayarlayıcı yöntemi. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) yapıcı


Sınıftan const alıcı ile [Decimal](../../../system/decimal/) özelliği bilgisini oluşturur.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Ayarlayıcı yöntemi. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) yapıcı


Boolean özelliği bilgisini oluşturur.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)(**bool**) | Ayarlayıcı yöntemi. |
| get_prop_method | **bool**(ClassType::*)() | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) yapıcı


Sınıftan const alıcı ile boolean özelliği bilgisini oluşturur.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)(**bool**) | Ayarlayıcı yöntemi. |
| get_prop_method | **bool**(ClassType::*)() const | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) yapıcı


**int64_t** özelliği bilgisini oluşturur.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Ayarlayıcı yöntemi. |
| get_prop_method | **int64_t**(ClassType::*)() | Alıcı yöntemi. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) yapıcı


Sınıftan const alıcı ile **int64_t** özelliği bilgisini oluşturur.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ClassType | Özelliğin ait olduğu sınıfın türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özellik adı. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Ayarlayıcı yöntemi. |
| get_prop_method | **int64_t**(ClassType::*)() const | Alıcı yöntemi. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)