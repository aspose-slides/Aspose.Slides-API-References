---
title: ConvertFrom()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte objetos.
type: docs
weight: 14
url: /es/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) método

Convierte objetos.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) a convertir. |

### Valor devuelto

objeto convertido.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) método

Convierte objetos.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) información del contexto de conversión. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar al convertir objetos. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) a convertir. |

### Valor devuelto

objeto convertido.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) método

Convierte cadena a objeto.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) información del contexto de conversión. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar al convertir objetos. |
| value | const [System::String](../../../system/string/)\& | Valor a convertir. |

### Valor devuelto

objeto convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeConverter](../)
* Clase [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::ComponentModel](../../)
* Biblioteca [Aspose.Slides](../../../)