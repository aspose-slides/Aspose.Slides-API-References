---
title: ConvertFromString()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte una cadena a un objeto.
type: docs
weight: 40
url: /es/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) método


Convierte una cadena a un objeto.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Valor a convertir. |

### Valor devuelto

objeto convertido.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) método


Convierte una cadena a un objeto.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) información del contexto de conversión. |
| text | const [System::String](../../../system/string/)\& | Valor a convertir. |

### Valor devuelto

objeto convertido.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) método


Convierte una cadena a un objeto.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) información del contexto de conversión. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar al convertir objetos. |
| text | const [System::String](../../../system/string/)\& | Valor a convertir. |

### Valor devuelto

objeto convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [String](../../../system/string/)
* Clase [TypeConverter](../)
* Clase [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Espacio de nombres [System::ComponentModel](../../)
* Biblioteca [Aspose.Slides](../../../)