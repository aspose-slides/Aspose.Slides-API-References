---
title: PropertyInfo()
second_title: Referência da API Aspose.Slides para C++
description: Construtor. Propriedade com apenas getter const.
type: docs
weight: 66
url: /pt/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) construtor


Construtor. Propriedade com apenas getter const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| PropertyType | Tipo da propriedade. |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) construtor


Construtor. Propriedade com apenas getter não const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| PropertyType | Tipo da propriedade. |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) construtor


Construtor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| PropertyType | Tipo da propriedade. |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Método setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) construtor


Construtor. [Nullable](../../../system/nullable/) propriedade com setter e getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| PropertyType | Tipo da propriedade. |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Método setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) construtor


Construtor. [Nullable](../../../system/nullable/) propriedade apenas com getter const.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| PropertyType | Tipo da propriedade. |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Método setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) construtor


Construtor. [Object](../../../system/object/) propriedade apenas com getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| PropertyType | Tipo da propriedade. |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Método setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) construtor


Constrói informações da propriedade de string.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Método setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) construtor


Constrói informações da propriedade de string a partir da classe com getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Método setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) construtor


Constrói [Decimal](../../../system/decimal/) informações da propriedade.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Método setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) construtor


Constrói [Decimal](../../../system/decimal/) informações da propriedade a partir da classe com getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Método setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) construtor


Constrói informações da propriedade booleana.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)(**bool**) | Método setter. |
| get_prop_method | **bool**(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) construtor


Constrói informações da propriedade booleana a partir da classe com getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)(**bool**) | Método setter. |
| get_prop_method | **bool**(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) construtor


Constrói **int64_t** informações da propriedade.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Método setter. |
| get_prop_method | **int64_t**(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) construtor


Constrói **int64_t** informações da propriedade a partir da classe com getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ClassType | Tipo da classe a que a propriedade pertence. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nome da propriedade. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Método setter. |
| get_prop_method | **int64_t**(ClassType::*)() const | Método getter. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)