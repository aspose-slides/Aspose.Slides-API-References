---
title: ConvertTo()
second_title: Aspose.Slides for C++ API Referansı
description: Nesneyi belirli bir türe dönüştürür.
type: docs
weight: 27
url: /tr/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) metot

Nesneyi belirli bir türe dönüştürür.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) dönüşüm bağlamı bilgisi. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Nesneleri dönüştürürken kullanılacak kültür. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) dönüştürmek için. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | Dönüştürülecek tür. |

### Dönüş Değeri

Dönüştürülmüş nesne.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [ImageFormatConverter](../)
* Ad Alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)