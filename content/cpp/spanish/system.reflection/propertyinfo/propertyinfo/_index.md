---
title: PropertyInfo()
second_title: Referencia de API de Aspose.Slides para C++
description: Constructor. Propiedad con solo getter const.
type: docs
weight: 66
url: /es/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor

Constructor. Propiedad con solo getter const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor

Constructor. Propiedad con solo getter no const.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) constructor

Constructor.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Método setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) constructor

Constructor. [Nullable](../../../system/nullable/) propiedad con setter y getter.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Método setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) constructor

Constructor. [Nullable](../../../system/nullable/) propiedad con solo getter const.

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | Método setter. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) constructor

Constructor. [Object](../../../system/object/) propiedad con solo getter.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| PropertyType | Tipo de la propiedad. |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | Método setter. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) constructor

Construye información de la propiedad de cadena.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Método setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) constructor

Construye información de la propiedad de cadena de la clase con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | Método setter. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) constructor

Construye [Decimal](../../../system/decimal/) información de propiedad.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Método setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) constructor

Construye [Decimal](../../../system/decimal/) información de propiedad de la clase con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | Método setter. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) constructor

Construye información de propiedad booleana.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(**bool**) | Método setter. |
| get_prop_method | **bool**(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) constructor

Construye información de propiedad booleana de la clase con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(**bool**) | Método setter. |
| get_prop_method | **bool**(ClassType::*)() const | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) constructor

Construye información de propiedad **int64_t**.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Método setter. |
| get_prop_method | **int64_t**(ClassType::*)() | Método getter. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) constructor

Construye información de propiedad **int64_t** de la clase con getter const.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ClassType | Tipo de la clase a la que pertenece la propiedad. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nombre de la propiedad. |
| set_prop_method | void(ClassType::*)(**int64_t**) | Método setter. |
| get_prop_method | **int64_t**(ClassType::*)() const | Método getter. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [PropertyInfo](../)
* Clase [Nullable](../../../system/nullable/)
* Clase [Decimal](../../../system/decimal/)
* Espacio de nombres [System::Reflection](../../)
* Biblioteca [Aspose.Slides](../../../)