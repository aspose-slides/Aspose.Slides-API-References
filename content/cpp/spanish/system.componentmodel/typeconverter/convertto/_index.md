---
title: ConvertTo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte el objeto a un tipo específico.
type: docs
weight: 53
url: /es/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) método

Convierte el objeto a un tipo específico.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) para convertir. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Tipo al que convertir. |

### Valor devuelto

Objeto convertido.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) método

Convierte el objeto a un tipo específico.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) información del contexto de conversión. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar al convertir objetos. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) para convertir. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Tipo al que convertir. |

### Valor devuelto

Objeto convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [TypeConverter](../)
* Clase [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Espacio de nombres [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)