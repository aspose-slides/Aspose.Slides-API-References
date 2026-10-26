---
title: PropertyInfo()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore. Proprietà con solo getter const.
type: docs
weight: 66
url: /it/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) costruttore

Costruttore. Proprietà con solo getter const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| PropertyType | Tipo della proprietà. |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Metodo getter. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) costruttore

Costruttore. Proprietà con solo getter non const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| PropertyType | Tipo della proprietà. |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) costruttore

Costruttore.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| PropertyType | Tipo della proprietà. |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Metodo setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) costruttore

Costruttore. [Nullable](../../../system/nullable/) proprietà con setter e getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| PropertyType | Tipo della proprietà. |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Metodo setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) costruttore

Costruttore. [Nullable](../../../system/nullable/) proprietà con solo getter const.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| PropertyType | Tipo della proprietà. |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Metodo setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) costruttore

Costruttore. [Object](../../../system/object/) proprietà con solo getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| PropertyType | Tipo della proprietà. |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Metodo setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) costruttore

Costruisce informazioni sulla proprietà stringa.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Metodo setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) costruttore

Costruisce informazioni sulla proprietà stringa dalla classe con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Metodo setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) costruttore

Costruisce [Decimal](../../../system/decimal/) informazioni sulla proprietà.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Metodo setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) costruttore

Costruisce [Decimal](../../../system/decimal/) informazioni sulla proprietà dalla classe con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Metodo setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) costruttore

Costruisce informazioni sulla proprietà booleana.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)(**bool**) | Metodo setter. |
| get_prop_method | **bool**(ClassType::*)() | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) costruttore

Costruisce informazioni sulla proprietà booleana dalla classe con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)(**bool**) | Metodo setter. |
| get_prop_method | **bool**(ClassType::*)() const | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) costruttore

Costruisce **int64_t** informazioni sulla proprietà.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Metodo setter. |
| get_prop_method | **int64_t**(ClassType::*)() | Metodo getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) costruttore

Costruisce **int64_t** informazioni sulla proprietà dalla classe con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ClassType | Tipo della classe a cui appartiene la proprietà. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome della proprietà. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Metodo setter. |
| get_prop_method | **int64_t**(ClassType::*)() const | Metodo getter. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [PropertyInfo](../)
* Classe [Nullable](../../../system/nullable/)
* Classe [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Libreria [Aspose.Slides](../../../)