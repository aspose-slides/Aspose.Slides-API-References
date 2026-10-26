---
title: Format()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen formatı kullanarak geçerli nesne tarafından temsil edilen bir değerin dize temsili döndürür.
type: docs
weight: 1
url: /tr/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) metod

Belirtilen formatı kullanarak geçerli nesne tarafından temsil edilen bir değerin dize temsili döndürür.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | [System::String](../../string/) | Dize formatı |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | Biçimlendirilecek nesne |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Biçimlendirme bilgilerini sağlayan nesne |

### Dönüş Değeri

**arg** öğesinin, **format** ve **formatProvider** tarafından belirtilen formata göre biçimlendirilmiş dize temsili

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Object](../../object/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [ICustomFormatter](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)