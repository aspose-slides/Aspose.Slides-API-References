---
title: ConvertTo()
second_title: Aspose.Slides for C++ API Referansı
description: Nesneyi belirli bir türe dönüştürür.
type: docs
weight: 14
url: /tr/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metod

Nesneyi belirli bir türe dönüştürür.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) dönüşüm bağlamı bilgisi |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Nesneleri dönüştürürken kullanılacak kültür |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Dönüştürülecek bir nesne. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Dönüştürülecek bir tür. |

### Dönüş Değeri

Dönüştürülmüş nesne.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [ImageConverter](../)
* Ad alanı [System::Drawing](../../)
* Library [Aspose.Slides](../../../)