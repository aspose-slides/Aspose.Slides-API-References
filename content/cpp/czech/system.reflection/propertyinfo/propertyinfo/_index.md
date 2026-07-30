---
title: PropertyInfo()
second_title: Aspose.Slides pro C++ – reference API
description: Konstruktor. Vlastnost pouze s konstantním getterem.
type: docs
weight: 66
url: /cs/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor

Konstruktor. Vlastnost pouze s konstantním getterem.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| PropertyType | Typ vlastnosti. |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor

Konstruktor. Vlastnost pouze s nekonstantním getterem.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| PropertyType | Typ vlastnosti. |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) konstruktor

Konstruktor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| PropertyType | Typ vlastnosti. |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Metoda setteru. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) konstruktor

Konstruktor. [Nullable](../../../system/nullable/) vlastnost s nastavitováním a getterem.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| PropertyType | Typ vlastnosti. |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Metoda setteru. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) konstruktor

Konstruktor. [Nullable](../../../system/nullable/) vlastnost pouze s konstantním getterem.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| PropertyType | Typ vlastnosti. |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Metoda setteru. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) konstruktor

Konstruktor. [Object](../../../system/object/) vlastnost pouze s getterem.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| PropertyType | Typ vlastnosti. |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Metoda setteru. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) konstruktor

Vytváří informace o řetězcové vlastnosti.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Metoda setteru. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) konstruktor

Vytváří informace o řetězcové vlastnosti třídy s konstantním getterem.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Metoda setteru. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) konstruktor

Vytváří [Decimal](../../../system/decimal/) informace o vlastnosti.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Metoda setteru. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) konstruktor

Vytváří [Decimal](../../../system/decimal/) informace o vlastnosti třídy s konstantním getterem.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Metoda setteru. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) konstruktor

Vytváří informace o vlastnosti typu boolean.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)(**bool**) | Metoda setteru. |
| get_prop_method | **bool**(ClassType::*)() | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) konstruktor

Vytváří informace o vlastnosti typu boolean třídy s konstantním getterem.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)(**bool**) | Metoda setteru. |
| get_prop_method | **bool**(ClassType::*)() const | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) konstruktor

Vytváří informace o vlastnosti typu **int64_t**.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Metoda setteru. |
| get_prop_method | **int64_t**(ClassType::*)() | Metoda getteru. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) konstruktor

Vytváří informace o vlastnosti typu **int64_t** třídy s konstantním getterem.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ClassType | Typ třídy, ke které vlastnost patří. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název vlastnosti. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Metoda setteru. |
| get_prop_method | **int64_t**(ClassType::*)() const | Metoda getteru. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [PropertyInfo](../)
* Třída [Nullable](../../../system/nullable/)
* Třída [Decimal](../../../system/decimal/)
* Jmenný prostor [System::Reflection](../../)
* Knihovna [Aspose.Slides](../../../)