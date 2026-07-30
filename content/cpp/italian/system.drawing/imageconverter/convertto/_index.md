---
title: ConvertTo()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte l'oggetto a un tipo specifico.
type: docs
weight: 14
url: /it/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metodo

Converte l'oggetto a un tipo specifico.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informazioni sul contesto di conversione |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura da utilizzare durante la conversione degli oggetti |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Un oggetto da convertire. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Un tipo in cui convertire. |

### Return Value

Oggetto convertito.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [ImageConverter](../)
* Spazio dei nomi [System::Drawing](../../)
* Library [Aspose.Slides](../../../)