---
title: ConvertTo()
second_title: Referência da API Aspose.Slides para C++
description: Converte o objeto para um tipo específico.
type: docs
weight: 14
url: /pt/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) método

Converte o objeto para um tipo específico.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informações de contexto de conversão. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a ser usada ao converter objetos. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Um objeto a ser convertido. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Tipo para o qual converter. |

### Valor de Retorno

Objeto convertido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [FontConverter](../)
* Namespace [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)