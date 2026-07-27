---
title: ConvertTo()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el objeto a un tipo específico.
type: docs
weight: 14
url: /es/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) método

Convierte el objeto a un tipo específico.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) información del contexto de conversión |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar al convertir objetos |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Un objeto a convertir. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Un tipo al que convertir. |

### Valor devuelto

Objeto convertido.

## Véase también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [ImageConverter](../)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)