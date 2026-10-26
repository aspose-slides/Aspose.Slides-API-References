---
title: ConvertTo()
second_title: Aspose.Slides for C++ API Referansı
description: Nesneyi belirli bir türe dönüştürür.
type: docs
weight: 14
url: /tr/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) yöntem

Nesneyi belirli bir türe dönüştürür.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) dönüşüm bağlamı bilgisi. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Nesneleri dönüştürürken kullanılacak kültür. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Dönüştürülecek bir nesne. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Dönüştürülecek tür. |

### Dönüş Değeri

Dönüştürülmüş nesne.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [FontConverter](../)
* Ad Alanı [System::Drawing](../../)
* Library [Aspose.Slides](../../../)