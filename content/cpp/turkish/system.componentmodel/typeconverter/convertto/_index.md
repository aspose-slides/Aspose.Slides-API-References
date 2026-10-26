---
title: ConvertTo()
second_title: Aspose.Slides for C++ API Referansı
description: Nesneyi belirli bir türe dönüştürür.
type: docs
weight: 53
url: /tr/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metot

Nesneyi belirli bir türe dönüştürür.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) dönüştürmek için. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Dönüştürülecek tip. |

### Dönüş Değeri

Dönüştürülmüş nesne.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metot

Nesneyi belirli bir türe dönüştürür.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) dönüşüm bağlamı bilgileri. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Nesneleri dönüştürürken kullanılacak kültür. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) dönüştürmek için. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Dönüştürülecek tip. |

### Dönüş Değeri

Dönüştürülmüş nesne.

## İlgili Bölümler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [TypeConverter](../)
* Sınıf [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Ad alanı [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)