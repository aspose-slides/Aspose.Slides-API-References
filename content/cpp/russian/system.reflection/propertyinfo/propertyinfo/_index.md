---
title: PropertyInfo()
second_title: Справочник API Aspose.Slides для C++
description: Конструктор. Свойство только с const getter.
type: docs
weight: 66
url: /ru/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) Конструктор


Конструктор. Свойство только с const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) Конструктор


Конструктор. Свойство только с non-const getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) Конструктор


Конструктор.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Метод-сеттер. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) Конструктор


Конструктор. [Nullable](../../../system/nullable/) свойство с сеттером и геттером.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Метод-сеттер. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) Конструктор


Конструктор. [Nullable](../../../system/nullable/) свойство только с const getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Метод-сеттер. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) Конструктор


Конструктор. [Object](../../../system/object/) свойство только с геттером.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| PropertyType | Тип свойства. |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Метод-сеттер. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) Конструктор


Создаёт информацию о строковом свойстве.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Метод-сеттер. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) Конструктор


Создаёт информацию о строковом свойстве из класса с const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Метод-сеттер. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) Конструктор


Создаёт [Decimal](../../../system/decimal/) информацию о свойстве.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Метод-сеттер. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) Конструктор


Создаёт [Decimal](../../../system/decimal/) информацию о свойстве из класса с const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Метод-сеттер. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) Конструктор


Создаёт информацию о булевом свойстве.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)(**bool**) | Метод-сеттер. |
| get_prop_method | **bool**(ClassType::*)() | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) Конструктор


Создаёт информацию о булевом свойстве из класса с const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)(**bool**) | Метод-сеттер. |
| get_prop_method | **bool**(ClassType::*)() const | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) Конструктор


Создаёт информацию о свойстве типа **int64_t**.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Метод-сеттер. |
| get_prop_method | **int64_t**(ClassType::*)() | Метод-геттер. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) Конструктор


Создаёт информацию о свойстве типа **int64_t** из класса с const getter.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ClassType | Тип класса, которому принадлежит свойство. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя свойства. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Метод-сеттер. |
| get_prop_method | **int64_t**(ClassType::*)() const | Метод-геттер. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)