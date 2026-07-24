---
title: ToType()
second_title: Aspose.Slides for C++ API Referansı
description: "Bu örneğin değerini, belirtilen System::Type'ın eşdeğer bir değerine sahip bir System::Object'e, belirtilen kültüre özgü biçimlendirme bilgilerini kullanarak dönüştürür."
type: docs
weight: 209
url: /tr/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) yöntemi

Bu örneğin değerini, belirtilen System::Type'ın eşdeğer bir değerine sahip bir [System::Object](../../object/)'ye, belirtilen kültüre özgü biçimlendirme bilgilerini kullanarak dönüştürür.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | Bu örneğin değerinin dönüştürüleceği System::Type. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Kültüre özgü biçimlendirme bilgilerini sağlayan bir [System::IFormatProvider](../../iformatprovider/) arabirim uygulaması. |

### Dönüş Değeri

Bu örnek değerine eşdeğer bir değere sahip, conversionType türünde bir [System::Object](../../object/) örneği.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Object](../../object/)
* Sınıf [TypeInfo](../../typeinfo/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [IConvertible](../)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)