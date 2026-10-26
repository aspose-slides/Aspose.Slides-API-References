---
title: PropertyInfo()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konstruktor. Właściwość posiadająca tylko stały getter.
type: docs
weight: 66
url: /pl/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor


Konstruktor. Właściwość posiada jedynie getter const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| PropertyType | Typ właściwości. |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Metoda getter. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor


Konstruktor. Właściwość posiada jedynie getter nie-const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| PropertyType | Typ właściwości. |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor


Konstruktor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| PropertyType | Typ właściwości. |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Metoda setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) konstruktor


Konstruktor. [Nullable](../../../system/nullable/) właściwość z setterem i getterem.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| PropertyType | Typ właściwości. |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Metoda setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) konstruktor


Konstruktor. [Nullable](../../../system/nullable/) właściwość z jedynie getterem const.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| PropertyType | Typ właściwości. |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Metoda setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor


Konstruktor. [Object](../../../system/object/) właściwość tylko z getterem.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| PropertyType | Typ właściwości. |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Metoda setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) konstruktor


Tworzy informacje o właściwości typu string.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Metoda setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) konstruktor


Tworzy informacje o właściwości typu string z klasy z getterem const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Metoda setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) konstruktor


Tworzy [Decimal](../../../system/decimal/) informacje o właściwości.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Metoda setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) konstruktor


Tworzy [Decimal](../../../system/decimal/) informacje o właściwości z klasy z getterem const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Metoda setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) konstruktor


Tworzy informacje o właściwości typu bool.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)(**bool**) | Metoda setter. |
| get_prop_method | **bool**(ClassType::*)() | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) konstruktor


Tworzy informacje o właściwości typu bool z klasy z getterem const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)(**bool**) | Metoda setter. |
| get_prop_method | **bool**(ClassType::*)() const | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) konstruktor


Tworzy **int64_t** informacje o właściwości.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Metoda setter. |
| get_prop_method | **int64_t**(ClassType::*)() | Metoda getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) konstruktor


Tworzy **int64_t** informacje o właściwości z klasy z getterem const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ClassType | Typ klasy, do której należy właściwość. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa właściwości. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Metoda setter. |
| get_prop_method | **int64_t**(ClassType::*)() const | Metoda getter. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)