---
title: ConvertFromString()
second_title: Aspose.Slides for C++ API Referansı
description: Dizgeyi nesneye dönüştürür.
type: docs
weight: 40
url: /tr/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) metodu

Dizgeyi nesneye dönüştürür.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Dönüştürülecek değer. |

### Dönüş Değeri

dönüştürülmüş nesne.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) metodu

Dizgeyi nesneye dönüştürür.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) dönüşüm bağlamı bilgisi. |
| text | const [System::String](../../../system/string/)\& | Dönüştürülecek değer. |

### Dönüş Değeri

dönüştürülmüş nesne.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) metodu

Dizgeyi nesneye dönüştürür.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) dönüşüm bağlamı bilgisi. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Nesneleri dönüştürürken kullanılacak kültür. |
| text | const [System::String](../../../system/string/)\& | Dönüştürülecek değer. |

### Dönüş Değeri

dönüştürülmüş nesne.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [TypeConverter](../)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)