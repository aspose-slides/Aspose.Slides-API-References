---
title: ConvertTo()
second_title: Referência da API Aspose.Slides para C++
description: Converte o objeto para um tipo específico.
type: docs
weight: 27
url: /pt/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) method

Converte o objeto para um tipo específico.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informação de contexto de conversão. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a ser usada ao converter objetos. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) para converter. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | Tipo para o qual converter. |

### Valor de retorno

Objeto convertido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [ImageFormatConverter](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)