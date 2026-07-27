---
title: ConvertTo()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el objeto a un tipo específico.
type: docs
weight: 27
url: /es/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) method


Convierte el objeto a un tipo específico.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) información del contexto de conversión. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar al convertir objetos. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) a convertir. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | Tipo al que convertir. |

### Valor devuelto

Objeto convertido.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [ImageFormatConverter](../)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)